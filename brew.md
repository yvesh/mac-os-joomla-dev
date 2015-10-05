# Brew

Homebrew is an advanced package manager for the Mac OS command line (like Apt on Debian or Yum on RHEL). It installs software to /usr/local and needs root for the installation / setup only.

It's written in ruby and needs the XCode command line tools.

## Install

Just run as normal user:

ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

This runs curl to get the installer script from GitHub and uses ruby (pre-installed on Mac OS) to install it for you.

## Usage 

Just type brew to see a basic list of commands. It's pretty straight forward and if you know Apt you are going to feel home instantly.

Let us start by installing wget, a simple tool for downloading files. 

```brew install wget```

##Alternatives

Fink, Macports
