# business-card-1
LED business card with a 15 x 5 LED matrix. Using ATMega168PB microcontroller, and real time clock chip. Powered by single CR2032 coin cell. All SMD parts, so if you're having PCBs made with this design I'd strongly suggest also buying a stencil to make it a LOT easier to solder! In my code I'm using deep sleep, with the button triggering a pin change interrupt to wake it. I use a 10khz timer interrupt to multiplexthe LEDs, which gives a good brightness, and allows for at least 16 greyscale levels.

![Image of card](https://www.smashcat.org/av/businesscard-1.jpg)
