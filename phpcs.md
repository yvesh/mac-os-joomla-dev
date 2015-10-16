# PHP Code Sniffer

With **phpcs** you can check if your code matches the [Joomla Coding Standards](http://joomla.github.io/coding-standards/)


### Installation

#### With Pear (not for El Capitan)

The current Joomla! code style rules still need version 1.5.6 of phpcs. Install it using pear with the following command:

```pear install PHP_CodeSniffer-1.5.6```

After that we have to install the Joomla code style rules:

```git clone https://github.com/joomla/coding-standards.git `pear config-get php_dir`/PHP/CodeSniffer/Standards/Joomla```

For more details see also the [Joomla Coding Standards Github repository](https://github.com/joomla/coding-standards)


#### Composer

First install composer (See chapter Composer)

composer global require squizlabs/php_codesniffer=1.5.6

If you added the composer binary directory to your $PATH you can now use phpcs as normal command.

#### Manual

You can also install it with curl

```curl -OL https://squizlabs.github.io/PHP_CodeSniffer/phpcs.phar
php phpcs.phar -h```

### Usage

You can use phpcs as *Üa standalone program, but most times you just want to integrate it into PHPStorm.

```phpcs --standard=/usr/lib/php/pear/PHP/CodeSniffer/Standards/Joomla path/to/code.php```