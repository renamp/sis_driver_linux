This is for Ubuntu 10.04 (Lucid Lynx), (32-bit):

1. Download files
2. Move them to /usr/lib/xorg/modules/drivers
(you may have to copy those to /usr/lib/xorg/modules/drivers/old_sis)
3. Add the following to your device section in /etc/X11/xorg.conf:
Code:

Driver "sis671"

4. Reboot your system (or restart gdm/Xorg)