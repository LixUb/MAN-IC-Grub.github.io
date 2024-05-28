# MAN-IC-BATAM-boot-loader

## Debian/Ubuntu

### Manually
- Clone this repository
```
git clone https://github.com/LixUb/MAN-IC-Grub.github.io.git
```
- Copy the folder to your boot partition: (for info: `-ruv` = recursive, update, verbose)
```
cd ./MAN-IC-Grub.github.io-main
sudo cp -ruv ./MAN-IC-Grub.github.io-main /boot/grub/themes/
```
- Change/add this line in your `/etc/default/grub`:
```
GRUB_THEME=/boot/grub/themes/MAN-IC-Grub.github.io-main/theme.txt
```
- Update your live grub config by running
```
sudo grub-mkconfig -o /boot/grub/grub.cfg
sudo update-grub
```
- follow @rayyhfz_
