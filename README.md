# ATtiny OLED

## Description
This project is intended to challenge myself and be used as a way to explore and try new concepts in electrical hardware design. The current planned challenges are as follows
- Design and maintain a full PCB in KiCad
- Use 0402 components as much as possible (my current standard is 0603)
- Create a board that is easily testable and probe friendly (test pads galore)
- Add a 128x64 OLED driver and connector
- Add a coin-cell battery holder
- Add side-fire push-buttons for the UI
- Add I2c addressable RGB LEDs
- Add a SD card using a SPI interface to the host MCU
- Focus on low power consumption to preserve battery life
- Add FTDI bridge to give USB connectivity to the host MCU over UART

## Hardware
For this project I will be using an [ATtiny87 from Atmel/Microchip](https://www.microchip.com/wwwproducts/en/ATTINY87). The part has a limited feature set and a small amount of memory, but hopefully enough to implement everything desired and provide an adequate challenge. 
- 8KB of Flash
- 512B or SRAM
- 512B of EEPROM
- 1x UART
- 2x SPI
- 1x I2c

The project for the firmware can be found in the [tiny-oled.firmware](https://github.com/stephendpmurphy/tiny-oled.firmware) repository on my profile. The project will be created and managed using the open source electrical design suite, [KiCad](https://kicad-pcb.org/).
