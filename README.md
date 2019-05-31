# change software source first

```bash
sudo apt-get update
```

# install software

```bash
sudo apt-get install vim vim-nox cscope exuberant-ctags thunderbird gnome-terminal chromium-browser gedit git fcitx meld gnome-calculator git-email
```

# change to guake

# remove the software

```bash
sudo apt-get remove epiphany-browser epiphany-browser-data maya-calendar noise audience pantheon-calculator scratch-text-editor pantheon-terminal pantheon-mail simple-scan onboard onboard-common gnome-orca ibus ibus-gtk ibus-gtk3 printer-driver-brlaser printer-driver-c2esp  printer-driver-foo2zjs printer-driver-foo2zjs-common printer-driver-hpcups printer-driver-m2300w printer-driver-min12xxw printer-driver-ptouch printer-driver-pxljr  printer-driver-sag-gdi printer-driver-splix io.elementary.code io.elementary.camera io.elementary.print
sudo apt-get autoremove
```

# install sogou

# config git

```bash
git config --global user.email "zhaozhanxu@163.com"
git config --global user.name "zhaozhanxu"

git config --global credential.helper store

git config --global sendemail.smtpserver smtp.163.com
git config --global sendemail.smtpserverport 465
git config --global sendemail.smtpencryption ssl
git config --global sendemail.smtpuser zhaozhanxu@163.com
git config --global sendemail.smtppass haha_secret
```

## git patch

```bash
git format-patch -n_commits --cover-letter -M origin/master -o outgoing
```

## modify cover-letter content

```bash
git send-email --to=need_email outgoing/*
```

# install netease-music

# options, install play software

```bash
sudo apt-get install clementine smplayer
```

# options, install shadowsocks

```bash
sudo add-apt-repository ppa:hzwhuang/ss-qt5
sudo apt-get install shadowsocks-qt5
```
