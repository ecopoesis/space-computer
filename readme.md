# Space Computer

Build a real, useful 3039p34

## Components

- Rectangle switches
  - NKK Smartswitch ISF15ACP4 
  - https://www.digikey.com/en/products/detail/nkk-switches/ISF15ACP4/5056758
  - 23.13mm x 20.59mm 

- Round switches
  - Rugged Metal Pushbutton - 16mm 6V RGB Momentary
  - https://www.adafruit.com/product/3350
  - 16mm

- Display
  - Waveshare 5.5inch Capacitive Touch AMOLED Display, 1080×1920
  - 121.76mm x 68.70mm (140.40mm x 74.76mm)

## Design

- QMK for keyboard side
  - Teensy?
  - 21 possible keys
  - Two encoders

- Raspberry Pi for screen

- HDMI switch
  - Pi
  - External monitor

## Open questions

- Better round buttons
  - Prefer neopixel/dotstar like things

- If using individual LEDs, how to control?
  - QMK with charlieplexed driver?

- How to set OLED button images?
  - Drop on Pi and SPI?
  - How to coordinate page switching between QMK and Pi land?

- Power?
  - Prefer internal power supply
