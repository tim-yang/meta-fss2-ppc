# FSS2Linux

![N|FssLinux](http://www.fujitsu.com/global/resources/design/stylesheets/images/css_images/fujitsu/symbolmark.gif)

FSS2 Linux is based of poky 1.6, 3.x kernel and hosted on public github server maintained by Fujitsu organization. 
Following describes workflow and steps to download FSS2Linux from public github and create a working build environment.

## Layer scape
This directory contains following folder

| directory    | Purpose                                                         |
| ------------ | --------------------------------------------------------------  |
| conf         | Provides machine types, default layer.conf                      |
| recipe-kernel| Contains files for kernel config, dts, uboot scripts and patches|
| patches      | Contains patches for yocto/poky                                 |

License
----

[GPLv2](https://github.com/FujitsuNetworkCommunications/meta-fss2-ppc/blob/master/LICENSE.md)
