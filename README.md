TWRP device configuration for Xiaomi Mi 6
==============

The Xiaomi Mi 6 (codenamed _"sagit"_) is a high-end smartphone from Xiaomi.

It was announced and released in April 2017.

## How to build
Check https://forum.xda-developers.com/showthread.php?t=1943625 

build using omni

To get started with OMNI sources to build TWRP, you'll need to get
familiar with [Git and Repo](https://source.android.com/source/using-repo.html).

To initialize your local repository using the OMNIROM trees to build TWRP, use a command like this:

    repo init -u git://github.com/minimal-manifest-twrp/platform_manifest_twrp_omni.git -b twrp-7.1
    
To initialize a shallow clone, which will save even more space, use a command like this:

    repo init --depth=1 -u git://github.com/minimal-manifest-twrp/platform_manifest_twrp_omni.git -b twrp-7.1

Then to sync up:

    repo sync

Then to build:
    place this repo into <source-dir>/device/xiaomi/sagit folder
    
    cd <source-dir>; . build/envsetup.sh; lunch omni_<device>-eng; mka recoveryimage

## Device specifications

Basic   | Spec Sheet
-------:|:-------------------------
CPU     | Octa-core (4x2.45 GHz Kryo & 4x1.9 GHz Kryo)
Chipset | Qualcomm MSM8998 Snapdragon 835
GPU     | Adreno 540
Memory  | 6 GB RAM
Shipped Android Version | 7.1.1
Storage | 64/128 GB
Battery | Li-Po 3350 mAh battery
Display | 1080 x 1920 pixels, 5.15 inches (~428 ppi pixel density)
Rear Camera  | Dual 12 MP (27mm, f/1.8, OIS 4-axis & 52mm, f/2.6), phase detection autofocus, dual-LED (dual tone) flash


## Device picture

![Xiaomi Mi 6](https://xiaomi-mi.com/uploads/CatalogueImage/xiaomi-mi-6-exclusive-edition-6gb128gb-dual-sim-ceramic-black-01_15554_1492602917.jpg "Xiaomi Mi 6 in black")
