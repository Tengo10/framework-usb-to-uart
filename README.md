# framework-usb-to-uart
USB to UART Expansion Card for the Framework Laptop

## Info
*Currently an early version, design untested*

A USB to UART converter based on the CP2102 chip by Silicon Labs, also includes an external 3.3V LDO for more power than the integrated on.

### Design Goals

 - almost no extended JLC SMT parts
 - no FTDI parts
 - at least 150 mA @ 3.3V

## Todo

- Do cost optimization
- find a good LDO (AMS out of stock)
- fix some SMT data

## Manufacture
Parts, PCB and Assembly at JLC PCB are about 24€ for 5 PCBs, 2 assembled.

## Legal
Based on the reference design by the Framework Team. Not responsible for anything. Design provided as is.
