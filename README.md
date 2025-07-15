# ESP8266-DCMOTOR
schematics for driving DC motors

This repository contains the schematics for driving a DC motor from the ESP8266.

## Notes:
It requires an external power source for driving the motors, usually +12V but it depends on your motor specs. Always check their current ratings as well.
In order to work the external power supply ground (GND) must be connected to the ESP8266 ground and if you plan to use it also to power the ESP8266 make sure to use a suitable voltage regulator.

The power MOSFET used is a logic level N-Channel suitable for the ESP8266 digital output (3.3V).

### BOM

Resistors (2): 220R, 10K

Flyback diode (1): 1N4007

N-Channel logic level power MOSFET (1): IRLB8721




If you want to know more about ESP8266 bare chip wiring there’s a great guide from Pieter P:
https://tttapa.github.io/ESP8266/Chap01%20-%20ESP8266.html

Let me know if I forgot to mention something .
Enjoy prototyping!

2025-07-15 CC-BY-SA 4.0 Stefano Manconi aka stziopa




