# u6809

## Project Description

This project allowed me to follow along with Ben Eater's 6502 series while still doing original work.
Architecturally, both systems are similar in scope, but use different components.

I originally intended for this to be a breadboard computer forever, but the temptation to tweak the design was too strong.
Solidifying it as a PCB allowed me to feel "done" with it.

## Primary Components

1. Motorola MC6809E (microprocessor)
2. Motorola MC6821 (peripheral interface adapter)
3. Motorola MC6840 (programmable timer module)
4. Motorola MC6850 (asynchronous communications interface adapter)
5. Alliance AS6C6264 (8 KB SRAM)
6. Winbond W27C512 (64 KB EEPROM)

## Project Status

I froze the design sometime in early Spring 2024 in order to focus on other things. It works well enough to blink some lights, but I haven't tested everything, especially the ACIA.
