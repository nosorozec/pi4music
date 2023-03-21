# installation

* https://archlinuxarm.org/platforms/armv8/broadcom/raspberry-pi-4
* addition software
```sh
$ su -
# pacman-key --init
# pacman-key --populate archlinuxarm
# pacman -Syu --noconfirm
# pacman -S --noconfirm sudo git vim mpd shairport-sync alsa-utils rpi-eeprom man ncmpcpp mpc sox mc zsh tmux
# usermod -aG audio alarm
```
* install https://ohmyzsh.sh
