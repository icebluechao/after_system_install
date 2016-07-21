#1. add sudo 
chmod +w /etc/sudoers
add "myname ALL=(ALL:ALL) ALL" to /etc/sudoers
chmod -w /etc/sudoers

#2. delete software
sudo apt-get remove aisleriot bijiben brasero brasero-cdrkit brasero-common empathy empathy-common eog evolution evolution-common five-or-more four-in-a-row gnome-chess gnome-contacts gnome-documents gnome-dictionary gnome-klotski gnome-mahjongg gnome-maps gnome-mines gnome-music gnome-nibbles gnome-robots gnome-sudoku gnome-system-monitor gnome-tetravex hamster-applet hitori iagno lightsoff polari quadrapassel rhythmbox rhythmbox-data simple-scan swell-foop tali totem totem-common transmission-gtk transmission-common vinagre xboard gimp gimp-data imagemagick imagemagick-common system-config-printer system-config-printer-udev 

#3. add software source and update

#4. install software
sudo apt-get install docky vim vim-nox exuberant-ctags cscope git chromium gnome-shell-extensions guake fcitx numix-icon-theme-circle numix-gtk-theme

#5. install (dash to dock) Hide Dash X and Dynamic panel transparency in iceweasel

#6. install nvidia (option)
sudo apt-get install make gcc build-essential linux-headers-$(uname -r) nvidia-kernel-dkms nvidia-glx nvidia-settings nvidia-xconfig

#7. delete software
sudo apt-get remove iceweasel gnome-terminal gnome-terminal-data
