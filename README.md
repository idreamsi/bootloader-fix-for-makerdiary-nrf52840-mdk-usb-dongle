# bootloader-fix-for-makerdiary-nrf52840-mdk-usb-dongle
SEGGER JLINK-OB JTAG is a low-cost debug probe. It can be used to program and debug the application software running on Arm Cortex Microcontrollers.

# How to use
1. Connect it to nRF52840 MDK USB Dongle according to the image below.

2. Download the [JLink Windows v7.94g](https://www.segger.com/downloads/jlink/) program and run ```JFlashLite.exe``` from its installation path.

3. Select ```nRF52840_xxAA``` from the device section and select ```SWD``` in the interface section. Click ```OK``` and select the firmware file from the ```Data File (bin/hex/mot/...)``` section in the new window. At the end, press the ```Program Device``` key.
