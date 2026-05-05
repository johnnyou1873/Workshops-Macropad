# Workshops-Macropad
A custom 6-key keyboard with rotary encoder, 3D-printed case with integrated plate mounting, and VIA firmware.

## Note
RGB is implemented on the PCB but has not been tested. To leverage the GPIO pins fully, custom firmware is needed.

## Bill of Materials
### Required
 - 1x XIAO RP2040
 - 6x MX hotswap sockets
 - 7x 1N4148 small signal diodes
 - 1x EC11 rotary encoder with push button
 - 4x M3x12 screws (support M3x8 - M3x14)

### Optional for RGB
 - 6x SK-6812 MINI-E reverse-mount RGB LEDs
 - 6x 100n 0805 decoupling capacitors
 - 2x 10k 0805 pull-up resistors
 - 1x BSS138 N-channel MOSFET

### Optional for GPIO
 - 4x 2.54mm pitch male right-angle pin headers
