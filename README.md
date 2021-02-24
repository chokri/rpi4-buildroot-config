# Raspberry PI 4 config for buildroot

## Get Buildroot

make sure the rpi4 folder have to be in same directory with buildroot.

```
$ wget http://www.buildroot.org/downloads/buildroot-2020.02.tar.bz2 
$ tar xf buildroot-2020.02.tar.bz2
```


## Create the Image

This repository contains configs to quickly create a custom os for `Raspberry PI 4` with debug tools. If you want to reconfigure it just run:

```
$ make menuconfig
```
If you want to recreate this from buildroot, just run:

```
$ make O=../build-pi4 raspberrypi4_defconfig 
```
