# Linux hid-cougar kernel driver

A functional Linux driver for the Cougar 500k Gaming Keyboard.

This driver solves the bug described here: https://bugs.launchpad.net/ubuntu/+source/linux/+bug/1511511

# Installation and usage

Copy hid-cougar-0.7 to /usr/src.
# cp -rf hid-cougar-0.7 /usr/src

Then use dkms to install the driver
# dkms install hid-cougar/0.7
