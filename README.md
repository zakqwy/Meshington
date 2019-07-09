## Meshington
![Meshington image](/HARDWARE/Meshington.png)

A tiny km-range mesh-networked T9ish communicator. Uses a pair of OLED displays to show the currently editing message and a common chatroom.
## Parts
- MCU: Microchip SAMD51
  - P/N ATSAMD51J20A-MUT
  - 1 MB flash, 256 kB ram, 64VQFN
  - https://www.digikey.com/product-detail/en/microchip-technology/ATSAMD51J20A-MUT/ATSAMD51J20A-MUTCT-ND/7390203
- Radio: HopeRF RFM95W
  - P/N RFM95W
  - LoRa, SX1276 compatible
  - https://www.ebay.com/itm/HopeRF-RFM95W-915Mhz-LoRa-Ultra-Long-Range-Transceiver-SX1276-compatible/181442612615
- Battery: Li-Ion AAA/14500
  - 3.7 V, 800ish mAh
  - https://www.batteryjunction.com/xtar-14500-800.html
  - SMD PCB clips
    - https://www.digikey.com/product-detail/en/mpd-memory-protection-devices/BK-53-TR/BK-53-TR-ND/3029218
    - https://www.digikey.com/product-detail/en/mpd-memory-protection-devices/BK-57-TR/BK-57-TR-ND/8119238
- Switches: ALPS SKPMAPE010
  - https://www.mouser.com/ProductDetail/alps/skpmape010/?qs=m0BA540hBPdYNRJ%252bk9MGoQ%3D%3D&countrycode=US&currencycode=USD
- Displays: 128x64 and 128x32 OLED
  - I2C mode (two addresses)
  - Bare displays with connector FPC
  - SSD1306 controller
  - https://www.buydisplay.com/default/white-1-inch-small-oled-display-module-128x32-i2c-arduino-connector-fpc
  - https://www.buydisplay.com/default/white-1-3-inch-oled-i2c-arduino-ssd1306-display-module-connector-fpc
- Mech
  - 3-PCB stack with button & display cutouts
  - Use four M3 screws / acorn nuts at corners
- Misc
  - Ref Adafruit Feather and Metro M4 Express
  - Incl. chg mgt, LDO, SWD connector, etc
  - UF2 bootloader + Circuit Python
