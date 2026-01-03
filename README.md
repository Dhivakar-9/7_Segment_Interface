# 7_Segment_Interface
This project demonstrates interfacing a 4-digit 7-segment display with the LPC2129 (ARM7) microcontroller, programmed in Embedded C using Keil µVision IDE. The display uses a multiplexing technique, where each digit is enabled one at a time while sharing common segment lines. A lookup table (LUT) is used to map decimal digits to segment patterns. The program continuously displays the number 1234 by rapidly refreshing each digit, creating the appearance of a steady display. This project helps in understanding multiplexed displays and GPIO control in ARM7 embedded systems.

![Uploading image.png…]()
