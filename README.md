#Setup Ubuntu

![Massacote Setup](./doc/img/setup.png)

##apt-get
* sudo apt-get install vim
* sudo apt-get install git
* sudo apt-get install ssh
* sudo apt-get install filezilla
* sudo apt-get install nodejs-legacy
* sudo apt-get install byobu
* sudo apt-get install htop

##git
* https://github.com/creationix/nvm

##.bashrc
* NVM - Node version control:
    * source ~/.nvm/nvm.sh
    * byobu

##.bash_aliases
[.bash_aliases](./.bash_aliases)

##npm
* sudo npm install -g grunt-cli
* sudo npm install http-server

##config
[Breve]

##install
* firefox
* google-chrome
* opera
* skype
* dropbox
* sublime

##mordern ie
* win7 - ie8
    * wget -i https://az412801.vo.msecnd.net/vhd/VMBuild_20131127/VirtualBox/IE8_Win7/Linux/IE8.Win7.For.LinuxVirtualBox.txt
* win7 - ie9
    * wget -i https://az412801.vo.msecnd.net/vhd/VMBuild_20131127/VirtualBox/IE9_Win7/Linux/IE9.Win7.For.LinuxVirtualBox.txt
* win7 - ie10
    * wget -i https://az412801.vo.msecnd.net/vhd/VMBuild_20131127/VirtualBox/IE10_Win7/Linux/IE10.Win7.For.LinuxVirtualBox.txt
* win7 - ie11
    * wget -i https://az412801.vo.msecnd.net/vhd/VMBuild_20131127/VirtualBox/IE11_Win7/Linux/IE11.Win7.ForLinuxVirtualBox.txt

* win8 - ie10
    * wget -i https://az412801.vo.msecnd.net/vhd/VMBuild_20131127/VirtualBox/IE10_Win8/Linux/IE10.Win8.For.LinuxVirtualBox.txt
* win8.1 - ie11
    * wget -i https://az412801.vo.msecnd.net/vhd/VMBuild_20140402/VirtualBox/IE11_Win8.1/Linux/IE11.Win8.1.For.LinuxVirtualBox.txt

#### problems
#####accentuation problem
Remove Ibus Framework.

* sudo apt-get remove --purge ibus

#####gnome interface problem
* sudo apt-get install [--]
