# ebrp
Enes Batur Recovery Project

NOTE/EN: This project is just a joke\
NOT/TR: Bu proje mizah amaçlı yaplılmıştır.

**Features**\
No american english, use british\
enes batur :sunglasses:\
masterpiece turkish translation

**Installation**\
flash it

**Screenshots**
![IMG_20230917_161214](https://github.com/tw0xa/ebrp/assets/98216123/0bbecc75-8fa3-48a9-aca7-03290af231db)
![IMG_20230917_161203](https://github.com/tw0xa/ebrp/assets/98216123/5219be71-dd43-43bd-9fcb-87d4bba7967b)
(broken power button, so no ss :(( )
(bad lighting tho)
(i broke the screen with throwing the phone to some random stone road)

**Porting**\
1- Clone this repo\
2- download android image kitchen https://forum.xda-developers.com/t/tool-android-image-kitchen-unpack-repack-kernel-ramdisk-win-android-linux-mac.2073775/ \
3- download a WORKING twrp img for your device\
4- ```cd AIK-Linux```\
5- ```./unpackimg.sh path/to/your/twrp.img```\
6- ```rm -rf ramdisk/twres```\
7- ```cp -r /path/to/cloned/ebrp/twres ramdisk/```\
8- ```./repackimg.sh```\
9- tada! image-new.img is your shiny ebrp image.

**Current devices**\
https://github.com/tw0xa/ebrp/blob/main/DEVICES.md

**Publish your build**\
1- Fork repo\
2- add your device to DEVICES.md\
example: ```codename: https://github.com/tw0xa/ebrp/releases/download/twrpversion/ebrp-twrpversion-codename.img \
3- upload your ebrp image to smth like gdrive/sourceforge \
4- create a pull request with the link of your ebrp image and a photo with ebrp running on the phone.\
5- wait\
6- When your pr is approved, we will upload your ebrp image to releases page and you will become cool.
