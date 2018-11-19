# Ultimate ECP5 Board

## Key Features
 - Largest ECP5; LFE5UM5G-85F
 - PCIe 2.0 x2 card edge connector on two SERDES channels
 - Remaining two SERDES channels on SATA connectors
 - 1GByte x32 DDR3 chips
 - Dedicated HDMI output, probably using TFP410 serialiser
 - 1000BASE-T GbE connector with RGMII PHY
 - USB-A 2.0 host connector with ULPI PHY
 - 2nd USB-A connector directly connected to FPGA
 - FT2232H for debug JTAG and UART/FIFO with micro-B connector
 - PCIe or external 12V power input
 - 12 user LEDs, 4 user buttons, 8 user DIP switches
 - 128Mbit QSPI flash for boot and data
 - microSD card connector
 - Audio I/O with I2S codec
 - Dual PMOD connector
 - As many remaining IO as possible on high speed FFC connectors with a differential optimised pinout (4x 24 IO + ...). Selectable 1.8V/2.5V/3.3V

## Layout
 - PCIe card form factor
 - At least Ethernet, USB-A, micro-USB debug and HDMI out
 - Other connectors probably would have to be on other sides. FFC connectors probably on top so they can loop over to another card to form a 2-slot card (e.g. with ADCs/DACs for SDR/DAQ)

## Possible accessories using high-speed FFC connectors
 - MIPI DSI smartphone-style LCDs
 - MIPI CSI-2 cameras
 - High speed ADC/DAC
 - HDMI in/out, direct or using serialiser chip
 - LVDS video in/out for LCDs or block cameras
 - Breakout board to dual or triple PMOD
