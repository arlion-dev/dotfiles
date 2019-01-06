# **dotfiles**

## Installation Linux

### Installation Uefi manjaro dualboot, deux disques

https://www.citizenz.info/installer-manjaro-en-multiboot-avec-window-10-en-uefi-gpt-avec-deux-disques-durs

```sudo efibootmgr -c -d /dev/sda -p 1 -L "manjaro" -l "\EFI\Manjaro\grubx64.efi" ```
 
### Discord

``` cd /tmp/ && yaourt -G libc++ && cd libc++ && makepkg -si --nocheck ```


## tests disque dur 

```
sudo smartctl -d sat -t short -c /dev/sdc

sudo smartctl -d sat -a /dev/sdc

sudo hdparm  --read-sector 56 /dev/sdc1
sudo hdparm  --write-sector 56 --yes-i-know-what-i-am-doing /dev/sdc

sudo smartctl -d sat -t long -c /dev/sdc
sudo badblocks -nvs /dev/sdc
 ```
 
 ## Wordpress
 
 
 
 
 
### Tuto :
 
   [Tuto](https://www.youtube.com/watch?v=2cbvZf1jIJM)
   
   [templates Tyler](http://www.tyler.com/)
   
   ### Plugins :
   
   Elementor
   OceanWP
   
   ### Site:
   
   [logomakr](https://logomakr.com/)
   
   [Pixabay Images](https://pixabay.com/)

 

 
  [ecrire sur github](https://help.github.com/articles/basic-writing-and-formatting-syntax/)
