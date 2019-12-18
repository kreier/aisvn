# API drive()

The function drive(int speed_l, int speed_r) provides a standardized software interface for the connection to the motors, be it a cheap DC motor, a geared DC motor with encoder or a stepper motor or servo.

## Definition

The drive function maps the input values for speed_r and speed_l from -1023 to 1023 to the respective speeds of the control unit. Positive values are forward, negative values are backward.

## Arduino Leonardo and Motorshield L298P

We used the Arduino Leonardo and the [Motorshield L298P](https://www.mantech.co.za/Datasheets/Products/EX029.pdf) in our [T300](../../T300) robot project. Here is the code.

## ESP8266 and Motorshield

For our T400 we switched to esp8266 for faster performance, more storage and build in WiFi. The motor control board is pretty cheap at 1.50$ or 30.000 VND.
