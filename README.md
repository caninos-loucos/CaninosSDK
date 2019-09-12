# CaninosSDK <DEPRECATED - FOR EARLY PROTOTYPES ONLY>

This repository contains the source code for Caninos Labrador Coreboard v1.x Operating System.
The kernel source code is located at the folder "kernel".
The u-boot source code is located at the folder "u-boot".
The armhf crosscompiler is located at the folder "toolchain".
The rootfs debian image is located at the directory "debian/system".

**Note** Before compiling, please download the Debian Buster rootfs image from "https://drive.google.com/open?id=1_O0hslsOzg2VRDqWIwkAxWR7VLPaAQ1m" and paste it in the folder "debian/system".

Environment setup (Debian): sudo apt-get install zlib1g-dev libncurses5-dev pkg-config bison flex libssl-dev git make build-essential gparted

# Firmware Creation

1) Go to the folder "owl"
2) Type ./config.sh and choose "debian" and "coreV2"
3) Type make all
4) The generated .fw image will be located at the folder "images" at "owl/out/labrador_debian_coreV2"

# Notes

It is expected that you have the `parted` program installed at location `/sbin/parted`.

