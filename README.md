## Adafruit CH552 QT Py - 8051 Dev Board with STEMMA QT PCB

<a href="http://www.adafruit.com/products/5960"><img src="assets/5960.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit CH552 QT Py - 8051 Dev Board with STEMMA QT. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/5960

### Description

What a cutie pie! Or is it... a QT Py? This diminutive dev board comes with a throwback processor - an 8-bit 8051! This tiny core is a big change from something like the the ESP32-S3 QT Py with two 240MHz 32-bit cores, but there's lots of folks interested in the CH552 and given the smol size, it is a nice matchup for a smol board.

The CH552  is an 'enhanced' E8051 core microcontroller, compatible with MCS51 instruction set but with 8~15 times faster instruction execution speed. You can run this core at 16MHz and 3.3V logic, and it's gotbuilt-in 16K program FLASH memory and, 256-byte internal RAM plus 1K-byte internal xRAM (xRAM supports DMA. It's also got some cute tricks up it's sleeve, like 4 built-in ADC channels, capacitive touch support, 3 timers / PWM channels, hardware UART, SPI, and a full-speed USB device controller. The last one means it can act like a native USB device such as CDC serial or mouse/keyboard HID.

If you're interested in playing with this chip, we've wrapped it up in a QT Py format. The pinout and shape is Seeed Xiao compatible, with castellated pads so you can solder it flat to a PCB. It comes with our favorite connector - the STEMMA QT, a chainable I2C port that can be used with any of our STEMMA QT sensors and accessories. We also added an RGB NeoPixel and both a reset button and 'bootloader enter' button.

Please note! This is a minimal 8-bit microcontroller, and it definitely does not run CircuitPython or Micropython. It also doesn't really run Arduino. There's an Arduino 'board support package' we recommend, but the compiler is for C not C++, which means you cannot use any Arduino libraries. It's very very bare-bones and for hacking/experimenting with this '40 cent chip'

* Same size, form-factor, and pin-out as Seeed Xiao
* USB Type C connector - If you have only Micro B cables, this adapter will come in handy!
* CH552 8-bit 8051 microcontroller core with 3.3V power/logic. Internal 16 MHz oscillator.
* Native USB
* Built in RGB NeoPixel LED
* 10 GPIO pins:
	* A2 pin is the same as MOSI pin (it's the hardware SPI port and one of only 4 ADC pins)https://github.com/DeqingSun/ch55xduino 4 x 8-bit analog inputs on A0, A1, A2, and A3
	* 3 x PWM outputs
	* I2C port with STEMMA QT plug-n-play connector
	* Hardware UART
	* Hardware SPI
	* 4 x Capacitive Touch with no additional components required, on A0-A3 pins
* 3.3V regulator with 600mA peak output
* Reset switch and bootloader for starting your project code over or entering USB ROM bootloader mode
* Really really small

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
