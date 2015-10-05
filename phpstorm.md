# Jetbrains PhpStorm

PhpStorm  is a (commercial) editor with many of features and used by most Joomla developers.

### Installation

Just download and install from [JetBrains website](https://www.jetbrains.com/phpstorm/) (There is also a 30 day trial).

### Configuration

First download the Joomla PhpStorm configuration (from the Coding Standards github repo) and copy it to your PhpStorm config directory:

```
cd ~/Library/Preferences/WebIde90/codestyles && \ 
wget -O joomla.xml https://raw.githubusercontent.com/joomla/coding-standards/master/IDE/joomla_phpstorm.xml
```

Now open the Preferences (PhpStorm -> Preferences) and select Editor -> Code Style.

Choose "Joomla" in the Scheme select and apply the changes.

### Code Sniffer

In the Preferences navigate to Languages & Frameworks -> PHP -> Code Sniffer and click on ... next to the select. 

In it set the phpcs path to ```/usr/bin/phpcs``` and click on validate.

Set the maximimum number of messages to 100 and the total process time to 30.

### Alternatives

Netbeans, Eclipse, vi or any other editor