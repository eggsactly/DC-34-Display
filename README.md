# About
DC-34-Display contains proof of concept, code, and design files for the 
Crtstalfontz 240x320 2.4" Resistive Touchscreen TFT Display Part Number: 
CFAF240320A0-024SR.

![Example](https://i.imgur.com/8GHt3mU.jpeg)

# Resources
Manufacturers product page
[https://www.crystalfontz.com/product/cfaf240320a0024sr-240x320-resistive-touchscreen-tft-display](https://www.crystalfontz.com/product/cfaf240320a0024sr-240x320-resistive-touchscreen-tft-display)

# Structure 
- DisplayPrototype/ contains an Arduino sketch for driving the display
- DisplayPrototypeSketch.fzz contains a fritzing diagram for how to wire the 
display, which is also displayed in the Schematic section of this README.

# Schematic 
![Circuit Schematic](https://i.imgur.com/WbbEaF8.png)

# Software Setup
Sketch > Include Library > Manage Libraries...

Install: 
- ILI9341 library (version 1.6.3)
- Adafruit_GFX library (version 1.12.6)

![Software Installs](https://i.imgur.com/VvfBFyT.png)

Tools > Board > Boards Manager... 

Install: 
- Arduino ESP32 Boards (version 2.0.18-arduino.5)

Select the right board:
Tools > Board > Adafruit Feather ESP32-S3 No PSRAM 

Then click:
 
Sketch > Verify/Compile

