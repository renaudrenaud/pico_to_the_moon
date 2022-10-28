# pico_to_the_moon
Raspberry PICO Neopixel ring code inside the rocket.

A really litle project with a Raspberry Pico, a neopixel ring and few lines of code for the rocket.

## Components
* one Raspberry Pi Pico
* one 16 LEDS neopixel ring, it works better with 16 then 24 or more LEDs
* one USB cable to power the Raspberry
* Thonny app to code the app and send it to the Rasp Pico

## Before to start
There is plenty of "fucking documentation" from people working with ZINDOWZ: fuck!

So with LINUX:
1. first point is to be sure of the cable: some USB cable are just for power; we need a power and DATA cable to program
Yeah there is nothing just strait to the main point
2. second we need the UF2 file [from the Raspberry Fundation](https://www.raspberrypi.com/documentation/microcontrollers/micropython.html)
3. push the button BOOTSEL on the PICO and power the card
4. when the PICO file system is recognized, push the UF2 file on the RPI-RP2 Mass storage, it will reboot the Pico in programming mode
5. use Thonny to push the code, use icons Stop And Start to gain access to the PICO. Sometimes the PICO is disconnected, restart gfrom point 3

## Documentation
* Raspberry:
https://www.raspberrypi.com/documentation/microcontrollers/micropython.html

![PICO](https://www.raspberrypi.com/documentation/microcontrollers/images/MicroPython-640x360-v2.gif)

* A mix of source code from here
https://makersportal.com/blog/ws2812-ring-light-with-raspberry-pi-pico

* [Pierre Muth design](https://pierremuth.wordpress.com/2018/09/08/destination-moon/)

![Pierre Muth for the crazy 3D design](https://pierremuth.files.wordpress.com/2018/09/assembly.gif?w=625)


