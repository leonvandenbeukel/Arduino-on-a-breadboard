# Arduino on a breadboard

This is a simple schematic on how to create an Arduino on a breadboard and connect it via a CP2102 TTL UART Serial Converter Module. Download the Fritzing file if you want to re-use or change this schema. I could not find a proper CP2102 in Fritzing so I've created a part for it myself. The svg files are also added to this repository.

![alt tag](https://raw.githubusercontent.com/leonvandenbeukel/Arduino-on-a-breadboard/master/Arduino%20on%20a%20breadboard%20with%20a%20atmega328p%20and%20cp2102.png)

To test it with the Arduino 'Blink' example add a 220 ohm resistor from pin PB5 to the anode (+) of an LED and attach the cathode (-) of the LED to ground. Load the sketch, compile and upload. Make sure to also check the [ATmega168/328-Arduino Pin Mapping](https://www.arduino.cc/en/Hacking/PinMapping168) page
