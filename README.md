Ardulight
=========

An arduino based ambilight controller for WS2801 based digital rgb led pixels.

Example-Video:<br />
<a href="http://www.youtube.com/watch?feature=player_embedded&v=HK8IQF8XRPc
" target="_blank"><img src="http://img.youtube.com/vi/HK8IQF8XRPc/0.jpg" 
alt="Example" width="240" height="180" border="10" /></a>

![](../master/img/pcb.jpg)
![](../master/img/pcb_back.jpg)

Assembly
--------

Assembly instructions including a BOM (bill of materials) can be found [here](../master/assembly).<br />
The pcb has to be soldered by hot air or by reflow due to the qfp package of the atmega32u4.

Firmware
--------

The ambilight controller works with the [Adalight Firmware from Adafruit](https://github.com/adafruit/Adalight/tree/master/Arduino/LEDstream).<br />
You can flash this firmware using an isp-programmer.<br />
Alternatively you can first flash the arduino leonardo bootloader with an isp-programmer and then flash the firmware directly over usb since the ambilight controller is compatible with the arduino leonardo.

Software
--------

The ambilight controller works with [Prismatik from woodenshark](https://github.com/woodenshark/Lightpack/releases/latest) (Alternative download [here](http://lightpack.tv/downloads)).

License
-------

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
