# Stair Light - Controller [IN PROGRESS]

This project contain 3 boards for making a LED light controller for using with stairs, corridors, or anything where people can cross, and you want to control light effects automatically.

Boards:

1. Stair Light - Controller
2. Stair Light - Controller MicroSD/USB-C
3. Stair Light - Controller PSU

These boards are made for install them inside a BHT-100GA thermostat. I think It can be difficult to find it now, because I bought it 5 years ago for making a WiFi thermostat but finally I discarded my initially idea.


![BHT-100GA](https://raw.githubusercontent.com/giltesa/stair-light-controller/master/3.%20Documentation/BHT-100GA%20-%20Plastic%20case/BHT-100GA_1.jpg)


Anyway, you can use the circuit in your own case if you want.

The circuit contains a ESP32 as microcontroller and WiFi/Bluetooth communication, it also has a RS485 controller to connect to the slave sensors to detect people who cross. This is the full list specification:

- **Microcontroller**: ESP32-WROOM / ESP32-WROVER-B (with auto-boot).
- **Communications**: WiFi, Bluetooth, RS485 3V3.
- **Programming port**: USB-C by CP2104.
- **User interface**: IPS round screen, LED status, Switches: Buzzer, Menu, Up, Down, Ok, Reset and Boot.
- **Storage**: MicroSD
- **Others**:
  - Real time clock DS3231 with li-ion battery LIR2032 (or not rechargeable CR2032).
  - Temperature and humidity sensor HTU21D
  - External connector to connect the PSU board (power, NeoPixel and RS485 communication).


![Stair Light - Controller](https://raw.githubusercontent.com/giltesa/stair-light-controller/master/4.%20SketchUP/Controller%20top.jpg)

![Stair Light - USB](https://raw.githubusercontent.com/giltesa/stair-light-controller/master/4.%20SketchUP/USB%20top.jpg)

![Stair Light - PSU](https://raw.githubusercontent.com/giltesa/stair-light-controller/master/4.%20SketchUP/PSU%20top.jpg)


## License

This project is licensed under a **Creative Commons** license:
**[Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0) ](https://creativecommons.org/licenses/by-nc-sa/4.0/)**

Check the [LICENSE.md](LICENSE.md) for more information.