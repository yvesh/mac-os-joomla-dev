# Composer

### Installation (Global)

```
curl -sS https://getcomposer.org/installer | php
mv composer.phar /usr/local/bin/composer
```

With Brew installed you should not need to use sudo for moving composer into /usr/local

### Usage (Global)

```composer global require codegyre/robo```

### Add Composer Bin to Path

In order to use applications installed with composer you have to add the composer bin folder to your path.

For this we need to edit the .zshrc file in our home directory

```export PATH=~/.composer/vendor/bin:$PATH```
