# hypr-arch-usb-live
Arch Linux live USB with hyprland

- Clone repo
- Create an `iso` directory
- `cd path/to/iso`
- `sudo mkarchiso -v path/to/repo`
- umount USB (Check with lsblk)
- `sudo -s`
- `ls -l /dev/disk/by-id/usb-*`
- `cd out`
- `cat archlinux-version-x86_64.iso > /dev/disk/by-id/usb-My_flash_drive`
