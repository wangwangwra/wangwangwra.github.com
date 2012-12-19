---
layout: post
title: linux boot
description: boot file, boot flow related
categories: [kernel]
tags: [boot, kernel]
---

+ vmlinux [v][v]
+ vmlinuz
    + zImage
    + bzImage [b][b]
+ system.map [s][s]
+ initrd [i1][i1] [i2][i2] [i3][i3]
+ bootloader
    + GRUB
    + LILO
+ Linux startup process [l][l]
    + BIOS
    + boot loader
        + GRUB
        + LILO
    + kernel
        + kernel loading stage
        + kernel startup stage
    + init process

[v]: https://en.wikipedia.org/wiki/Vmlinux "wiki"
[b]: https://en.wikipedia.org/wiki/File:Anatomy-of-bzimage.png 
    "wiki"
[s]: https://en.wikipedia.org/wiki/System.map "wiki"
[i1]: https://en.wikipedia.org/wiki/Initrd "wiki"
[i2]: https://www.ibm.com/developerworks/cn/linux/l-k26initrd "ibm"
[i3]: https://www.ibm.com/developerworks/cn/linux/l-initrd.html "ibm"
[l]: https://en.wikipedia.org/wiki/Linux_startup_process "wiki"
