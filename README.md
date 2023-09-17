# ebrp
Enes Batur Recovery Project

NOTE/EN: This project is just a joke\
NOT/TR: Bu proje mizah amaçlı yaplılmıştır.\

**Features**\
No american english, use british\
enes batur :sunglasses:\

**Installation**\
flash it\

**Porting**\
1- Clone this repo\
2- download android image kitchen https://forum.xda-developers.com/t/tool-android-image-kitchen-unpack-repack-kernel-ramdisk-win-android-linux-mac.2073775/\
3- download a WORKING twrp img for your device\
4- ```cd AIK-Linux```\
5- ```./unpackimg.sh path/to/your/twrp.img```\
6- ```rm -rf ramdisk/twres/*```\
7- ```cp -r /path/to/ebrp/repo/* ramdisk/twres```\
8- ```./repackimg.sh```\
9- tada! image-new.img is your shiny ebrp image.\

**Current devices**
sagit\
