WOW Kid's Museum Jeep Kiddie Ride
==============================================

![Moving car ride](<Kiddie Car moving.gif>)

This is a repo for the repair log of the Jeep kiddie ride made by Falgas (Spain) at the [WOW Children's Museum](https://wowchildrensmuseum.org/) in Lafayette, CO.

![Falgas Jeep Kiddie Ride](<WOW Jeep Kiddie Ride.png>)

The coin receiver has been bypassed so that money is not needed to start the ride. The start button connects to the sound/money controller. That sends a signal to the transformer box that has TI part TIC263M triac that turns on/off the motor. The transformer also provides 12V at 5A and 2A (both fused) to run the sound/money controller and the lights.

The transformer housing contains various fuses and protections including Weber Protection T11-043. There is also a small board that has a triac to turn on/off the drive motor with the following wires:

* Brown - 5V or GND into MOC3021's LED
* Red - 5V or GND insto MOC3021's LED
* Blue - AC output to motor
* Green - AC input from wall


The drive mechanism is made up of two large belts and two small belts:
* Small belts: 24 x 13 x 610 Pirelli
* Large belts: 4L350W

![Falgas Exploded View](<Parts Diagram - Exploded View.png>)

The manual for this jeep can be downloaded [here](<llibret complert6.pdf>). 

---------------

2024-August

The Jeep stopped working. One of the two small belts had broken and jammed in place. The motor was tested and working, as was the coin controller.

The triac board has been replaced with a [solid-state relay](https://www.sparkfun.com/products/13015) which is nearly identical, just with modern parts and larger heatsinking.

The two large drive belts were replaced (preventative maintenance). A bearing puller will be needed to get access to the two smaller belts.

![Broken wire harness](<2024-08-26 11.03.34.jpg>)

The connecting cable between the coin controller to the transformer (and motor solid-state relay) was found to be damaged causing the motor not to start. One wire out of 8 is a no-connect. Ran a new cable from the coin controller to the SSR. Jeep is running again on one small belt.


