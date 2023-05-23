# sevensegment
Display a two-digit integer to two seven segment displays from the RP2040.

## Requirements
- RP2040 MCU
- Raspberry Pi Pico SDK

## How to use
GPIO pins 0-13 are used to connect to each segment of both displays. The least significant digit is displayed with pins 0-6 and the most significant digit is displayed with pins 7-13.

The pinout for each segment of both displays is as follows:
### Least Significant Digit Display:

| GPIO Pin | Segment | 
|----------|---------|
| GP0 | A |
| GP1 | F |
| GP2 | E | 
| GP3 | B |
| GP4 | G |
| GP5 | C |
| GP6 | D | 

### Most Significant Digit Display:

| GPIO Pin | Segment | 
|----------|---------|
| GP7 | A |
| GP8 | F |
| GP9 | E | 
| GP10 | B |
| GP11 | G |
| GP12 | C |
| GP13 | D | 

Assuming the following seven segment display layout:

![Seven segment display layout](https://www.noumansaleem.com/assets/7_Segment_Display_with_Labeled_Segments.svg)
