# rofi-powermenu-alpine
powermenu for alpine linux

copied from https://github.com/adi1090x/rofi
apk add rofi-wayland doas

permit nopass :wheel as root cmd /sbin/poweroff
permit nopass :wheel as root cmd /sbin/reboot

