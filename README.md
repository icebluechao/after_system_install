#1. change software source first
sudo apt-get update
sudo apt-get install software-properties-common
sudo add-apt-repository ppa:wiznote-team
sudo add-apt-repository ppa:hzwhuang/ss-qt5
sudo add-apt-repository ppa:philip.scott/elementary-tweaks
sudo apt-get update
sudo apt-get install shadowsocks-qt5
#2. install software
sudo apt-get install shadowsocks-qt5 elementary-tweaks vim vim-nox cscope exuberant-ctags thunderbird guake chromium-browser gedit git libreoffice fcitx meld gnome-calculator
#3. change to guake
#4. remove the software
sudo apt-get remove epiphany-browser epiphany-browser-data maya-calendar noise audience pantheon-calculator scratch-text-editor pantheon-terminal pantheon-mail simple-scan onboard gnome-orca ibus ibus-gtk ibus-gtk3 printer-driver-foo2zjs printer-driver-foo2zjs-common
sudo apt-get autoremove
#5. install sogou, must modify /etc/os-release
#6. config git
git config --global user.email "my@mail.com"
git config --global user.name "myname"
git config --global credential.helper store
#7. install netease-music
#8. options, install play software
sudo apt-get install clementine smplayer
