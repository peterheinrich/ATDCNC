# GRBL Compatible Controller

This tiny desktop CNC will use GRBL to interpret G-Code.

## PoC Breadboard Setup
* Uses now obsolete L6208N (PDIP) stepper driver. L6208D is still available for SMD design iteration. Basically any step/dir driver will do!
* 1.5A max phase current with a 20V supply for sufficient headroom.
* ATMega328 microcontroller for step generation.
* 2.54mm (100mil) design restriction for easy breadboard prototyping.
