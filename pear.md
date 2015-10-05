# PEAR - PHP Extension and Application Repository

PEAR is still one of the most used package managers (Like CPAN for Perl) for PHP.

### Installation 

On Mac OS PHP is installed by default, but PEAR is not. You can now either download the latest version of the installer script or use the one which is supplied with Mac OS. 

####Mac OS El Capitan

Because of the new system integrity protection it is currently not possible to use the integrated install script. 

For disabling it (you can enable it again after the installation) see [this guide](http://www.macworld.com/article/2986118/security/how-to-modify-system-integrity-protection-in-el-capitan.html).

#### Mac OS installer

Start up a Terminal session and navigate to the PHP library folder

```cd /usr/lib/php```

In it the PEAR install tool is located. Let's execute it with PHP as Super User:

```sudo php install-pear-nozlip.phar```

### Usage

Run ```pear ``` for a list of commands.

