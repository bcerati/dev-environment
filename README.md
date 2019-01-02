# Shell

You'll find in the [shell directory](./shell) my configuration files for theses tools:

* zsh
* screen
* vim

# Screen

Have a look [here](https://linuxize.com/post/how-to-use-linux-screen/#starting-named-session) for the commands I use.

# VS Code

For my daily JavaScript codes I'm using VS Code. You can find my configuration in Github by following this link: [Gist](https://gist.github.com/bcerati/fa30f6ea4e9c896cb594d561ea1e30d0)

# Soft I am installing on my machines

- [Ubuntu LTS](https://ubuntu-fr.org/telechargement)
- [Google Chrome](https://www.google.com/chrome/)
- [Sublime Text 3](https://www.sublimetext.com/3)
- [Hot Corners for Ubuntu](https://www.fosslinux.com/4184/how-to-enable-hot-corners-in-ubuntu-18-04.htm/)
- [PHPStorm](https://www.jetbrains.com/phpstorm/download/#section=linux)
* [Discord](https://discordapp.com/download)
* [VSCode](https://code.visualstudio.com/download)

## Some tools

* ```sudo apt install -y curl keepass2 git vlc zsh kate vim fonts-powerline tilda python3-pip python-pip net-tools openssh-server openssh-client```

## zsh

* ```sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"```

* ```chsh -s $(which zsh)```

[Bullet train for zsh](https://github.com/caiogondim/bullet-train.zsh)

## PHP 7.3

```bash
sudo add-apt-repository ppa:ondrej/php
sudo apt-get update
sudo apt install php
sudo apt-get install -y php7.0 php7.1 php7.2
sudo apt-get install php7.0-curl php7.2-curl php7.1-curl php7.3-curl
sudo apt-get install php7.0-xml php7.2-xml php7.1-xml php7.3-xml
sudo apt-get install php7.0-ldap php7.2-ldap php7.1-ldap php7.3-ldap
sudo apt-get install php7.0-mysql php7.2-mysql php7.1-mysql php7.3-mysql
```

### Composer

[Install Composer](https://getcomposer.org/doc/00-intro.md#globally)

```bash
composer global require hirak/prestissimo
```

## Docker

* [Docker](https://docs.docker.com/install/linux/docker-ce/ubuntu/#upgrade-docker-ce)
* [docker-compose](https://docs.docker.com/compose/install/#prerequisites)

## NodeJS

* [NodeJS](https://github.com/nodesource/distributions/blob/master/README.md#debinstall)

```bash
sudo npm install -g n nodemon yarn
```

## Android Studio

```bash
sudo snap install android-studio --classic
```

Then accept licences of SDK tools

```bash
sdkmanager --licenses
```

# Icons

## PHPStorm

```bash
#!/usr/bin/env xdg-open  

[Desktop Entry]
Version=1.0
Name=PHPStorm
GenericName=Text Editor
Exec=/home/boris/Documents/softwares/PhpStorm-183.4886.46/bin/phpstorm.sh
Terminal=false
Icon="/home/boris/Documents/softwares/PhpStorm-183.4886.46/bin/phpstorm.png"
Type=Application
Categories=TextEditor;IDE;Development
Icon[en_US]=/home/boris/Documents/softwares/PhpStorm-183.4886.46/bin/phpstorm.png
X-Ayatana-Desktop-Shortcuts=NewWindow
```

## Sublime Text

```bash
#!/usr/bin/env xdg-open  

[Desktop Entry]
Version=1.0
Name=Sublime Text 3
GenericName=Text Editor
Exec=/home/boris/Documents/softwares/sublime_text_3/sublime_text
Terminal=false
Icon="/home/boris/Documents/softwares/sublime_text_3/Icon/32x32/sublime-text.png"
Type=Application
Categories=TextEditor;IDE;Development
Icon[en_US]=/home/boris/Documents/softwares/sublime_text_3/Icon/32x32/sublime-text.png
X-Ayatana-Desktop-Shortcuts=NewWindow
```