##change software source first
sudo apt-get update
sudo apt-get install software-properties-common
sudo add-apt-repository ppa:philip.scott/elementary-tweaks
sudo apt-get update
##install software
sudo apt-get install bleachbit elementary-tweaks vim vim-nox cscope exuberant-ctags thunderbird guake chromium-browser gedit git libreoffice fcitx meld gnome-calculator
##change to guake
##remove the software
sudo apt-get remove epiphany-browser epiphany-browser-data maya-calendar noise audience pantheon-calculator scratch-text-editor pantheon-terminal pantheon-mail simple-scan onboard gnome-orca ibus ibus-gtk ibus-gtk3 printer-driver-foo2zjs printer-driver-foo2zjs-common
sudo apt-get autoremove
##install sogou, must modify /etc/os-release
##config git
git config --global user.email "my@mail.com"
git config --global user.name "myname"
git config --global credential.helper store
##install netease-music
##options, install play software
sudo apt-get install clementine smplayer
##options, install shadowsocks
sudo add-apt-repository ppa:hzwhuang/ss-qt5
sudo apt-get install shadowsocks-qt5
##options, install themes
sudo sh -c "echo 'deb http://download.opensuse.org/repositories/home:/Horst3180/xUbuntu_16.04/ /' > /etc/apt/sources.list.d/arc-theme.list"
sudo apt-key adv --recv-keys --keyserver keyserver.Ubuntu.com BEB6D886
sudo apt-get update
sudo apt-get install arc-theme -y