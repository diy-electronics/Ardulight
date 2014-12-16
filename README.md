Ardulight
=========

Ardu(ino)(Ambi)light: An arduino based ambilight controller for WS2801 based digital rgb led pixels.

Example-Video:<br />
<a href="http://www.youtube.com/watch?feature=player_embedded&v=HK8IQF8XRPc
" target="_blank"><img src="http://img.youtube.com/vi/HK8IQF8XRPc/0.jpg" 
alt="Example" width="300" /></a>

Images
------

<img src="https://github.com/jneureuther/Ardulight/blob/master/pcb/img/pcb.jpg" width="300px"/>&nbsp;&nbsp;&nbsp;<img src="https://github.com/jneureuther/Ardulight/blob/master/pcb/img/pcb_back.jpg" width="300px" />

Assembly
--------

Assembly instructions including a BOM (bill of materials) can be found [here](../master/pcb).<br />
The pcb has to be soldered by hot air or by reflow due to the qfp package of the atmega32u4.

Wiring
------

For a detailed wiring guide look [here](https://learn.adafruit.com/adalight-diy-ambient-tv-lighting/wiring-1).<br />
The LED-Strip has to be powered from an external power source, using e.g. a connector like [this](https://www.adafruit.com/products/368).<br />
You only have to connect GND, CLK (SCK) and DAT (MOSI).  

Firmware
--------

The firmware can be found [here](../master/firmware/firmware.pde)<br />
You can flash this firmware using an isp-programmer.<br />
Alternatively you can first flash the arduino leonardo bootloader with an isp-programmer and then flash the firmware directly over usb since the ambilight controller is compatible with the arduino leonardo.

Software
--------

The ambilight controller works with [Prismatik from woodenshark](https://github.com/woodenshark/Lightpack/releases/latest) (Alternative download [here](http://lightpack.tv/downloads)).

License
-------

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.<br />
The firmware is licensed under a GNU Lesser General Public, see <http://www.gnu.org/licenses/>.<br />
