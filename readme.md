# Proyecto de comunicación PIC85F4550*

Utilizando protocolos I2C, SPI, UART.

## Información
- [Datasheet](https://ww1.microchip.com/downloads/aemDocuments/documents/OTH/ProductDocuments/DataSheets/39632e.pdf)

## Master SSP (MSSP) Module Overview (tomado del capítulo 19 de la datasheet)
The Master Synchronous Serial Port (MSSP) module is a serial interface, useful for communicating with other peripheral or microcontroller devices. These peripheral devices may be serial EEPROMs, shift registers, display drivers, A/D converters, etc. The MSSP module can operate in one of two modes:
• Serial Peripheral Interface (SPI)
• Inter-Integrated Circuit (I2C™)
- Full Master mode
- Slave mode (with general address call)
The I2C interface supports the following modes in hardware:
• Master mode
• Multi-Master mode
• Slave mode
