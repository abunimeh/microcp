# MicroCP
Low-cost USB to UART board using CP2102N

# Features
* Open Source
* USB to UART bridge for development and debugging
* Data transfer rates up to 3M baud
* Small footprint 0.6" x 0.6"
* Four programmable GPIOs
* 5V output from USB port
* 3.3V output from integrated regulated proving 100mA
* Programmable clock output (93.75KHz to 24MHz)
* Flexible GPIO voltages (1.8V to 5.0V)
* Low operating current : 9.5mA
* Remote wakeup for waking a suspended host
* 16 Standard 0.1" headers to access all CP2102N pins
* Easy solder-jumper configuration identical to [MicroFTX][ftx]
* Cross platform support by SiLabs
* No firmware development required, royalty-free Virtual COM port drivers, and Simple GUI-based configurator by SiLabs
* See CP2102N datasheet

# History
[MicroFTX][ftx] is a nifty little gadget using FTDI chips to create a USB to serial interface. This work is based on MicroFTX, however, it uses SiLabs' CP2102N chip.

License
----
[CERN OHL v1.2][CERN_OHL]

[ftx]: <http://jim.sh/ftx/>
[ftdi]: <http://www.ftdichip.com/>
[CERN_OHL]: <http://www.ohwr.org/cernohl>