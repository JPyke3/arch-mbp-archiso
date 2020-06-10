# arch-mbp-archiso
## Introduction
These are the build scripts for compiling an Arch Linux iso image using the kernel patches by [@MCMrARM](https://github.com/MCMrARM). This build script has only been tested with 2018 MacBook pro 13" Models, as such further testing needs to take place on newer models.

## Downloads
Any of the ISO Files I have personally compiled can be found in the releases section

## How-To (Compile Yourself)
clone the repository
```
git clone https://github.com/JPyke3/arch-mbp-archiso
```
cd and build 
```
cd arch-mbp-archiso
sudo ./build.sh -v
```

The compiled ISO file will be located in the `out` directory. You can then flash this to a USB and enjoy Arch Linux :)

A gist detailing the installation proccess on the mbp can be found [here](https://gist.github.com/TRPB/437f663b545d23cc8a2073253c774be3)

## Thanks
Thanks goes to: 
 * [@MCMrARM](https://github.com/MCMrARM) for building the patches
 * [@aunali1](https://github.com/aunali1) for hosting the kernel on his repository
