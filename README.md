# Minimal Reference Example for displaying text on Waveshare e-ink display using GxEPD2

A simple minimal example demonstrating the use of full and partial refresh of a paper display.

1. Executes a single initial full refresh of the screen, displaying some text
2. Displays a number counter using only partial refreshes of the screen
3. Clears the display at the end

## Reference Specs
**Cloud Module Used**: https://www.waveshare.com/2.13inch-e-paper-cloud-module.htm

**Board**: ESP32-WROOM-32 

**Board Library Used**: ESP32-WROOM-DA

**Screen**: WaveShare 2.13in(V3) Black and White (FPC-7528B)
**Colors**: Black and White
**Gray Scale**: 2
**Resolution**: 250 x 122 px
**Full Refresh Time**: 2 seconds
**Partial Refresh Supported**: Yes
**Interface**: SPI


**Screen Details** (inferred from GxEPD): DEPG0213BN  128x250, SSD1680, (FPC-7528B), TTGO T5 V2.4.1, V2.3.1

**Screen Hat Spec Sheet**: https://files.waveshare.com/upload/5/59/2.13inch_e-Paper_V3_Specificition.pdf

## Running
1. Acquire required reference hardware
2. Install Arduino IDE
3. Install board library for ESP32-WROOM-DA
4. Install GxEPD2 using Library Manager in Arduino IDE
5. Load and run example using Arduino IDE
