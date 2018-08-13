# Linux hid-cougar kernel driver

A functional Linux driver for the Cougar 500k Gaming Keyboard.

This driver solves the bug described here: https://bugs.launchpad.net/ubuntu/+source/linux/+bug/1511511

This driver contains small changes from the original Cougar 500K driver written by Daniel M. Lambea (https://github.com/dmlambea/linux-cougar-500k-drv). Please check his repository. 


# Installation and usage

Copy hid-cougar-0.7 to /usr/src:

cp -rf hid-cougar-0.7 /usr/src

Then use dkms to install the driver:

dkms install hid-cougar/0.7
