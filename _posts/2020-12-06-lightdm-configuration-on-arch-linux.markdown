---
layout: post
title:  "Lightdm Configuration on Arch Linux"
date:   2020-12-06 12:28:00 -0400
categories: linux
---

After an Arch Linux minimal install and when installing LightDM, one should activate the
```
logind-check-graphical=true
```
line on file
```
/etc/lightdm/lightdm.conf
```
as true before starting the LightDm service. This configures your system to check first if graphics are active before starting the display manager. If you encounter a blank screen and are unable to go to a tty, boot with Arch install media, chroot into your installation and mark this line as true. This solved the problem for me.
