# Description

Chapter 3 : Starting a C module - LED driver

## Requirements

- The LED driver controls 16 two states LEDS
- The driver can turn ON and OFF individual LEDS
- The driver car turn all LEDS ON and OFF with a single interface call
- The user of the dirver can query the state of any LED
- At Power on, the hardware default should is for LEDs to be latched on. They must be turned off by the software
- The LEDs are memory mapped to a 16 bit word (at an address to be determined)
- A 1 in a position lights should corresponds to LED 1; The MSB corresponds to LED 16

## Test List 

- [ ] All LEDs are off after the driver is initialized
- [ ] A single LED can be turned ON
- [ ] A single LED can be turned OFF
- [ ] Multiple LED can be turned ON/OFF
- [ ] Turn ON all LEDs
- [ ] Turn OFF all LEDs
- [ ] Query LED state
- [ ] Check boundary values
- [ ] chec out of bounds values

