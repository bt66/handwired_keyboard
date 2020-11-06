# bt66tech60

![bt66tech60](https://i.imgur.com/8eJ4liU.jpg)

How to use this repository?
1. make sure you have installed qmk_firmware
2. copy this repository to qmk_firmware/keyboard/

* Keyboard Maintainer: [bt66](https://github.com/bt66)
* Hardware Supported: *handwired, STM32*
* Hardware Availability: *anywhere*

Make example for this keyboard (after setting up your build environment):

    make bt66tech/bt66tech60:default

Flashing example for this keyboard:

   dfu-util -d 1eaf:0003 -a 2 -D "/path/to/firmware.bin"

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).
