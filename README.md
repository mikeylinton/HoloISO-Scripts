# HoloISO-Scripts

#### On Fresh install

```bash
sudo pacman -Syu
sudo cp /etc/pacman.conf /etc/pacman.conf.backup
sudo wget https://github.com/HoloISO/holoiso/blob/stable/pacman.conf -O /etc/pacman.conf
```

> **reboot** system before continuing

```bash
sudo pacman-key --init
sudo pacman-key --populate
sudo pacman-key --refresh-keys
sudo pacman -Syyu
sudo steamos-update check
sudo steamos-update now
sudo holoiso-grub-update
```


