# Config Aurora Sofle v2 PCB Kit 

![ABFEECCD-25C7-4F1B-B112-243E7AD99D48_1_102_a](https://github.com/Traxmaxx/zmk-config/assets/320272/235f34a0-26d6-4285-a514-ffe47be3d2c8)

## Configuration
Cherry MX Hot Swap sockets with nice!nano

## Specs
- nRF52840 chip on board with 1MB of Flash and 256KB of RAM
- Adafruit Bootloader loaded offering DFU flashing as well as flashing via UF2 storage (similar to dragging a file to a flash drive!)
- Programmable indicator (blue) LED as well as a charging indicator (orange) LED
- Battery voltage reader to report battery percentage to main device
- External power can be cut off using an on board MOSFET saving power from LEDs (each can draw 1mA when off!)
- 5 extra GPIO pins (3 thru holes and 2 pads on the back) offering a total of 23 GPIO pins
- 3.3V out of the VCC pin to power external features
- 32.768 kHz oscillator on board for real-time clock capabilities
