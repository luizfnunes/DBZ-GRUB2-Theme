# DBZ Theme

DBZ GRUB2 Theme
Created in 2016 by LuizFNunes

Install

1 - Copy the contents of the folder "dbz-theme" for your grub directory of topics. I recommend creating the directory "/ boot / grub / themes"

sudo cp -R dbz-theme/ /boot/grub/themes

2 - add or modify the next line in the file /etc/default/grub:

GRUB_THEME="/boot/grub/themes/dbz-theme/theme.txt"

3 - Update the configurations:

sudo update-grub

Supported Resolutions
800x600
1024x768
1366x768
