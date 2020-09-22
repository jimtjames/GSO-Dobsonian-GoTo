# GSO-Dobsonian-GoTo
Hardware and software for GSO Dobsonian (Apertura, Zhumell, etc.) GoTo upgrade

## Mechanics 
Many of the mechanics are laser cut, though a few are handmade. The modifications were designed to require as little altering to the original base as possible to avoid damage. As such, you shouldn't have to drill many holes to have a working setup, and you should be able to revert all modifications.

## Electronics
The electronics in use are from the OnStep MaxPCB with a Teensy 4.1. Uses both encoders and geared NEMA 17 stepper motors.

## GoTo Software
For GoTo functionality, we utilize OnStep.

## PushTo Software
The included Arduino sketch is used for Push-To functionality. Uses encoders tensioned to the pulleys with springs for maximum accuracy, as well as a matrix transformation to align coordinate systems.
