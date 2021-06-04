# Lenovo GRUB Theme
A simple grub theme with Lenovo branded background designed for my Lenovo U330p notebook. Since I use it with dual boot option I wanted to have a nice looking boot manager :)
## Features
The theme provides icons for menu entries like Ubuntu, Windows, UEFI setup, restart and shutdown. It also brings a progress bar on the bottom screen border for visualizing the set up timeout.

## Installation
Place this theme in the following directory: **/boot/grub/theme**

Add or uncomment the following line

```
GRUB_THEME="/boot/grub/theme/lenovo_grub_theme/theme.txt"
```

After this, execute

```bash
sudo update-grub
```

## Additional things
For a in my eyes cleaner look I modified some GRUB config files which lies under **/etc/grub.d/** , for example the file *"30_os-prober"*, to have the proper Windows name displayed. This tweaks are up to you and are not shipped with this theme.

## Licence
This theme.txt file stands under the GPLv3 licence. All images and icons are (licence) free and are not affected by this licence.