Ardulight
=========

An arduino based ambilight controller for WS2801 based digital rgb led pixels.
Example-Video: https://www.youtube.com/watch?v=HK8IQF8XRPc

Assembly
--------

Assembly instructions including a BOM (bill of materials) can be found [here](../assembly).
The pcb has to be soldered by hot air or by reflow due to the qfp package of the atmega32u4.

Firmware
--------

The ambilight controller works with the [Adalight Firmware from Adafruit](https://github.com/adafruit/Adalight/tree/master/Arduino/LEDstream).
You can flash this firmware using an isp-programmer.
Alternatively you can first flash the arduino leonardo bootloader with an isp-programmer and then flash the firmware directly over usb since the ambilight controller is compatible with the arduino leonardo.

Software
--------

The ambilight controller works with [Prismatik from woodenshark](https://github.com/woodenshark/Lightpack/releases/latest) (Alternative download [here](http://lightpack.tv/downloads)).
