# arduinogotchi
Tamagotchi with Arduino Uno or Mega or Nano

I used an Mega 2560 for this!

 # You need:
an Arduino Uno or Mega or Nano
an Analog Joystick 
An I2C Oled 128x32 (You can rewrite the code so it works on 128x64)
Optinal: An Passive Buzzer (Passive Buzzer only works in V2)

# Wiring:

Analog Joystick:

GND - GND
+5V - 5V
VRx - A0

I2C Oled 128x32:

GND - GND
VCC - 3.3V/3V3
SCK - SCL (Check Arduino Pins Layout)
SDA - SDA (Check Arduino Pins Layout)

Optinal: Passive Buzzer:

Pin 11

# READ THIS:

there are two versions. V1 and V2

V1 has no GameOver and No Passive Buzzer
V2 has an GameOver and has Support for Passive Buzzer but its not great!
