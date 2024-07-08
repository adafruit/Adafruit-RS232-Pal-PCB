## Adafruit RS232 Pal - Two Channel UART to RS-232 Level Shifters - MAX3232E PCB

<a href="http://www.adafruit.com/products/5987"><img src="assets/5987.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit RS232 Pal - Two Channel UART to RS-232 Level Shifters - MAX3232E. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/5987

### Description

If you're looking to interface with telco, retro or industrial equipment you'll probably run into RS-232 interfaces. The Adafruit RS232 Pal - Two Channel UART to RS-232 Level Shifters is your friend in such cases, giving you two duplex channels of level shifting and taking care of the high/negative voltage generation all in a low cost breakout board. We use the trusty MAX3232E, a classic chip that is part of the MAX232 lineage so you know it will work great for all your RS-232 needs, up to 250Kbps.

RS-232 is what we had before USB: a 9 or 25 pin D-Sub connector that would allow data plus flow control lines. Many folks may remember these interfaces were used for mice, modems, barcode scanners, tele-types and more. We still find devices sold that have RS-232 ports, although many folks use a USB to RS-232 adapter these days.

If you want to use a microcontroller or microcomputer to chat with a RS-232 then thankfully all you need is a serial port / UART (something just about any microcontroller has) and a level shifter. The level shifter is required because while most UARTs are 0-3.3V or 0-5V logic level, RS-232 requires +-6 to +-10V, yep the signal voltage goes negative! That means a specialized shifter is required, one that can generate the extra high and low voltages and also safely convert the logic levels.

Sure you could buy a raw MAX232 chip and wire up the necessary capacitors, but this board does it all for you plus it can run on 3.3V power and logic, which many older chips can't do. It also can do 2 duplex channels, so you can have both RX and TX plus two flow control pins like RTS and CTS.

This breakout comes fully assembled with a UART side for low voltage power/logic level and an RS-232 side for high voltage signals plus the doubled and negative voltage rails in case you need to reference them. We also include a bit of header so you can solder it to a breadboard in a few minutes.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
