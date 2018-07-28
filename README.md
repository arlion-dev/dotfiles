# dotfiles

## Installation Linux

## Installation Uefi manjaro dualboot, deux disques

https://www.citizenz.info/installer-manjaro-en-multiboot-avec-window-10-en-uefi-gpt-avec-deux-disques-durs
 sudo efibootmgr -c -d /dev/sda -p 1 -L "manjaro" -l "\EFI\Manjaro\grubx64.efi"
 
## Discord

``
yaourt -G libc++ && cd libc++ && makepkg -si --nocheck
