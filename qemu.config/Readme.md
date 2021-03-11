# QEMU-only version of Buildroot
This folder contain the Buildroot *.config* file to build a small Buildroot image with just *qemu-system-i386*
## What is this version of Buildroot used for?
This Buildroot can be used to run VMs with QEMU on a smallest Linux OS possible.
## How to build?
You can clone Buildroot and then copy the *qemu.config* file to the Buildroot dir and then rename it to *.config* and ```make oldconfig``` to load the file and then ```make```
<br>Or you can just download the pre-build iso (<b><i>Unstable</i></b>) at <a href="https://github.com/raspiduino/.config/releases">Release</a>
