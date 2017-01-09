##change software source first
##install software
sudo add-apt-repository ppa:mpstark/elementary-tweaks-daily
sudo add-apt-repository ppa:numix/ppa
sudo apt-get update
sudo apt-get install vim vim-nox cscope exuberant-ctags thunderbird guake chromium-browser gedit git libreoffice fcitx meld gnome-calculator elementary-tweaks numix-icon-theme numix-icon-theme-circle
##change to guake
##remove the software
sudo apt-get remove midori-granite maya-calendar maya-calendar-common noise audience pantheon-calculator scratch-text-editor pantheon-terminal geary simple-scan onboard gnome-orca ibus ibus-gtk ibus-gtk3 printer-driver-foo2zjs printer-driver-foo2zjs-common
sudo apt-get autoremove
##install sogou, must modify /etc/os-release
##config git
git config --global user.email "my@mail.com"
git config --global user.name "myname"
git config --global credential.helper store
##install netease-music
##options, install play software
sudo apt-get install clementine smplayer
