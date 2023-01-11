# pico_to_the_moon
Raspberry PICO Neopixel ring code inside the rocket.

A really litle project with a Raspberry Pico, a neopixel ring and few lines of code for the rocket or something else.

## Components
* one Raspberry Pi Pico
* one 16 or 24 LEDS neopixel ring, it works better with 16 then 24 or more LEDs
* one USB cable to power the Raspberry
* Thonny app to code the app and send it to the Rasp Pico

## Before to start
There is plenty of "f******* documentation" from people working with ZINDOWZ: f***!

With LINUX:
1. first point is to be sure of the cable: some USB cable are just for power; we need a power and DATA cable to program
2. second we need the UF2 file [from the Raspberry Fundation](https://www.raspberrypi.com/documentation/microcontrollers/micropython.html)
3. push the button BOOTSEL on the PICO and power the card
4. when the PICO file system is recognized, push the UF2 file on the RPI-RP2 Mass storage, it will reboot the Pico in programming mode
5. use Thonny to push the code, use icons Stop And Start to gain access to the PICO. Sometimes the PICO is disconnected, restart from point 3
6. first time using Thonny requires: 
* sudo usermod -a -G dialout renaud 
* or sudo chmod a+rw /dev/ttyACM0

## Documentation Links and books
* Raspberry:
https://www.raspberrypi.com/documentation/microcontrollers/micropython.html

![PICO](https://www.raspberrypi.com/documentation/microcontrollers/images/MicroPython-640x360-v2.gif)

* GPIO
![image](https://user-images.githubusercontent.com/9823965/211700097-bbbd6938-f06b-4433-bc5a-569afd6f75ff.png)


* A mix of source code from here
https://makersportal.com/blog/ws2812-ring-light-with-raspberry-pi-pico

* [Pierre Muth design](https://pierremuth.wordpress.com/2018/09/08/destination-moon/)

![Pierre Muth for the crazy 3D design](https://pierremuth.files.wordpress.com/2018/09/assembly.gif?w=625)

* Books & Magazines

![book](https://magpi.raspberrypi.com/storage/representations/redirect/eyJfcmFpbHMiOnsibWVzc2FnZSI6IkJBaHBBckFjIiwiZXhwIjpudWxsLCJwdXIiOiJibG9iX2lkIn19--f9c801f640680afdfbb1dd99a847f5e4650f3aaf/eyJfcmFpbHMiOnsibWVzc2FnZSI6IkJBaDdCem9MWm05eWJXRjBTU0lJYW5CbkJqb0dSVlE2RW5KbGMybDZaVjkwYjE5bWFYUmJCMmtCeURBPSIsImV4cCI6bnVsbCwicHVyIjoidmFyaWF0aW9uIn19--e422219c46ed7fd137fa095840c5061b4fc9e5f4/MicroPythonPico_Cover.jpg)

![119](https://magpi.raspberrypi.com/storage/representations/redirect/eyJfcmFpbHMiOnsibWVzc2FnZSI6IkJBaHBBdW9hIiwiZXhwIjpudWxsLCJwdXIiOiJibG9iX2lkIn19--91c5d48613097e7c7bf11dc7ee45a67824142b53/eyJfcmFpbHMiOnsibWVzc2FnZSI6IkJBaDdCem9MWm05eWJXRjBTU0lJYW5CbkJqb0dSVlE2RW5KbGMybDZaVjkwYjE5bWFYUmJCMmtCeURBPSIsImV4cCI6bnVsbCwicHVyIjoidmFyaWF0aW9uIn19--e422219c46ed7fd137fa095840c5061b4fc9e5f4/001_MagPi119_COVER_nospine.jpg)

![122](https://magpi.raspberrypi.com/storage/representations/redirect/eyJfcmFpbHMiOnsibWVzc2FnZSI6IkJBaHBBazBkIiwiZXhwIjpudWxsLCJwdXIiOiJibG9iX2lkIn19--6f88127109798ee592919ae47e71a60d96176390/eyJfcmFpbHMiOnsibWVzc2FnZSI6IkJBaDdCem9MWm05eWJXRjBTU0lJYW5CbkJqb0dSVlE2RW5KbGMybDZaVjkwYjE5bWFYUmJCMmtCeURBPSIsImV4cCI6bnVsbCwicHVyIjoidmFyaWF0aW9uIn19--e422219c46ed7fd137fa095840c5061b4fc9e5f4/001_MagPi122_COVER_v5_nospine.jpg)


![121](https://magpi.raspberrypi.com/storage/representations/redirect/eyJfcmFpbHMiOnsibWVzc2FnZSI6IkJBaHBBc1FiIiwiZXhwIjpudWxsLCJwdXIiOiJibG9iX2lkIn19--cf65d8c13983a3cb35d2e1b90cda9f5721e55fe5/eyJfcmFpbHMiOnsibWVzc2FnZSI6IkJBaDdCem9MWm05eWJXRjBTU0lJYW5CbkJqb0dSVlE2RW5KbGMybDZaVjkwYjE5bWFYUmJCMmtCeURBPSIsImV4cCI6bnVsbCwicHVyIjoidmFyaWF0aW9uIn19--e422219c46ed7fd137fa095840c5061b4fc9e5f4/001_MagPi121_COVER_v4_nospine.jpg)

