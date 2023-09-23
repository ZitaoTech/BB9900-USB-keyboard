# BB9900-USB-KBD
## About this Keyboard

This mini Keyboard is using the original Blackberry 9900 keyboard with Trackpad and powered by the Raspberry Pi Rp2040 Microcontroller and operates under QMK Firmware, which transforms itself into a USB HID Keyboard and Mouse combo. The device has a USB Type-C female port, allowing it to connect to a smartphone using a USB-C to USB-C cable or to a computer using a USB-A to USB-C cable. This Keyboard is universally compatible across all platforms, including Android and iOS smartphones, Windows, Linux, and macOS computers, as well as various tablets.

## Features
### Hardware:

The keyboard has not only keys but also includes an optical navigation trackpad, which located in the upper-middle area. This optical navigation sensor can function as a mouse or a scroll wheel. The whole keyboard has backlighting, and the optical navigation button area also has backlighting. In the default firmware, when the Caps Lock is enabled, the backlight for the optical navigation trackpad will be turned on; when Caps Lock is disabled, the backlight for the optical navigation will be turned off. Additionally, the keyboard backlight can be manually toggled on or off. On the side of the USB Type-C female port, there are two additional side buttons that provide extra key functions and enhance ergonomics.

Below is a key legend for the important keys on the default firmware's Layer 0:


### customize your own keymap:

Due to the limited number of keys on the keyboard, the default firmware has configured the two keys in the bottom right corner to serve as the second and third layer activation keys. Since everyone has its varying preferences and interpretations of their keyboard layouts, it may be necessary to customize the key layout and keycode for this keyboard. The default firmware supports online key remapping through [VIA](understanding_qmk.md).

## Default Layout and Layers
