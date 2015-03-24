

# Some pictures of the main hardware #

A clone board called the freeduino, some headers were missing when I took pictures:

![http://opengauge.org/obduino/hardware/freeduino_front.jpg](http://opengauge.org/obduino/hardware/freeduino_front.jpg)
![http://opengauge.org/obduino/hardware/freeduino_back.jpg](http://opengauge.org/obduino/hardware/freeduino_back.jpg)


The LCD screen with its wires attached, note the transistor and the resistor, covered by (not yet heated) shrink tube, on the right side:

![http://opengauge.org/obduino/hardware/lcd.jpg](http://opengauge.org/obduino/hardware/lcd.jpg)
![http://opengauge.org/obduino/hardware/lcd_back.jpg](http://opengauge.org/obduino/hardware/lcd_back.jpg)


Example of the Freeduino and LCD attached:

![http://opengauge.org/obduino/hardware/duino_lcd.jpg](http://opengauge.org/obduino/hardware/duino_lcd.jpg)

# ISO Diagram #

Here's the proposed diagram of the [Arduino](http://arduino.cc) board, the LCD screen, and the [ISO interface](OBDuinoInterface.md).

![http://opengauge.org/obduino/diagram/obduino.gif](http://opengauge.org/obduino/diagram/obduino.gif)

## Hardware for ISO ##

You need:
  1. a duino clone board, serial or USB, your choice
  1. an HD44780 compatible LCD screen 2x16
  1. a transistor 2N3906 or NTE159
  1. three small push buttons
  1. a 220 ohms resistor
  1. a Freescale MC33290 ic
  1. a 510 ohms resistor
  1. a DB9 male

Freeduino, LCD, ISO interface:

![http://opengauge.org/obduino/hardware/obduino.jpg](http://opengauge.org/obduino/hardware/obduino.jpg)