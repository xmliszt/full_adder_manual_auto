# full_adder_manual_auto
Mojo program to control a full adder to perform in AUTO mode and MANUAL mode
---

## IO_LEDs indicating A/B/C three inputs
io_led[1][2]: Input A
io_led[1][3]: Input B
io_led[1][4]: Input Carry-in

## IO_LEDs indicating Sum and Carry-out
io_led[1][0]: Sum
io_led[1][1]: Carry-out

## output PINs input to the full-adder circuits
PIN6: Input A
PIN12: Input B
PIN16: Input C

## input PINs take in signals from Sum and Carry-out
PIN5: Sum
PIN11: Carry-out
