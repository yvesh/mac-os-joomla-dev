# Zsh

Mac OS by default uses Bash as Terminal emulator.

Why should you use Zsh?

First, the bash version that Mac OS ships is pretty old (just take a look at bash --version) and zsh offers a lot of nice features and extensions that makes your life a lot easier.

See ["Why Zsh is Cooler than your shell"](http://de.slideshare.net/jaguardesignstudio/why-zsh-is-cooler-than-your-shell-16194692) for more on this topic.


### Installation

Use brew to install it

```brew install zsh zsh-completions```

#### [Oh my Zsh](https://github.com/robbyrussell/oh-my-zsh)

This is an very useful compilation of addons and themes for the Zsh.

Install it with:

```sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"```

By default the robbyrussell theme is used, but there a lot of different ones to choose from (Change it in the .zshrc).


### Configuration

Similar to the bas there is a hidden file (starting with dot) in your home directory called:

.zshrc

In it you can set up you can set the theme and other options for the zsh. Or setup any other task which should get executed, when you open a new instance (like aliases, exporting editor etc.)


### Switch to Zsh

Change your default shell with

chsh -s /bin/zsh


### Alternatives

Bash, Sh, Kornshell
