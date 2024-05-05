![PWMlaserBoardTop](https://github.com/Ccecil/PWMBoard/assets/1588588/498f6eaf-d517-4298-8f3c-c33328c9ab75)

This board is to be used to expand the PWM header from a V2 Smoothieboard (or Gadgeteer) header.  

- 4 mosfet buffered PWM outputs with jumper options to select between Pullup voltages and/or disable the pullup resistor for Opendrain outputs.
- 2 Switch inputs which are debounced with passives and have optional pullup resistor/voltage.
- 1 Comparator probe input which increases the repeatability of probes and allows use of probe voltages from 3-45v (through jumper configs)
- Optional voltage input for using higher voltages on the PWM output pin3 (i.e. Running higher voltages to the servo motor or using different 5v source)

Comparator probe input jumper options

- J5 pin 3 input voltage set to
- 2.9v-5v (default)
- 5-24v (JP5-2 cut)
- 6-45v (JP5-2 and JP5-3 cut)

PWM output and Switch input jumpers.

- JP2: J6-J9 pin 3 optional voltage source select (J1 Pin 2 default, cut to use J2 Pin 1)
- JP3-1: J3 pin 1 and pin 3 pullup Voltage select
- JP3-2: J3 pin 3 pullup disable
- JP4-1: J4 pin 1 and pin 3 pullup Voltage select
- JP4-2: J4 pin 3 pullup disable
- JP5-1: J5 pin 1 Voltage select
- JP5-2: J5 pin 3 pullup cut (required for HV operation)
- JP5-3: J5 pin 3 Low/High voltage select (default low)
- JP6: J6 pin 1 pullup Voltage select
- JP7: J7 pin 1 pullup Voltage select
- JP8: J8 pin 1 pullup Voltage select
- JP9: J9 pin 1 pullup Voltage select

Jumper and connector numbers match their respective driving pin from the J1 header
