# Voice to Push
This repo is for designing a physical, general-purpose pushbutton actuator that can be acutated through voice commands. The three major components are: the actuator, a wifi enabled microcontroller, and the command interface.

# Requirements
- User needs to be able to push a computer power button through voice commands.
- User should be able to push button without voice commands if need be.
- Must be securley attached to the device and not break the connection, the device, or the actuation motor during actuation.

# Design Notes
Microcontroller: Adafruit HUZZAH ESP8266 breakout
  - has wifi built in
  - can use arduino IDE

Servo: tower pro micro servo 9g
  - small
  - simple range of motion

Linear motion: Scotch yolk

Communication: Use IFTTT

Surface connection: velocro? screws? adhesive?

Power: USB to the computer. Does it need backup power?
