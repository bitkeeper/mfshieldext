# mfshieldext

mfshieldext is an mBlock extension for the Multi Function Shield, a generic IO shield for the Arduino. 
mBlock is a scratch like environment which support several hardware platforms, including the Arduino.

<img src="pictures/mfs.png" width="300">

The Multi Function Shield contains:
* 4x leds
* 3x push buttons
* 4x 7 segments display
* 1x buzzer
* 1x poteniometer
* and some interface for external sensors

For the Arduino IDE there is library available at https://www.cohesivecomputing.co.uk/hackatronics/arduino-multi-function-shield/.
You can also find a nice pdf manual for the use of it. This extension is based on version 1.2 of the multi-function-shield library.
## mBlock Blocks
You can the extension in the extension center under the name MF Shield.
It will add a tab called MFS to you block palete.

With the following blocks:
* beep [length] ms
* repeat [count] beep [length] ms and silent [length] ms
* set led [number] [on|off]
* blink led [number] [on|off]
* get button state
* is button [number] [state] in [value]
* get potentiometer
* display [text]
* blink display segement [number] [on|off]
* set display segement [number] to [raw value]



<img src="pictures/mBlock-mfshield-blocks.png" width="400">


## Example
An example project that demonstrates the use of most block is provided at https://ide.mblock.cc/#/?cloudProjectId=161721.

<img src="pictures/mBlock-example-flow.png" width="400">
