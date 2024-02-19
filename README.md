# Bootloader Fix for Makerdiary nrf52840 mdk USB dongle
SEGGER JLINK-OB (Of course [Clone Version](https://www.aliexpress.com/item/1005003670186319.html)) is a low-cost debug probe. It can be used to program and debug the application software running on Arm Cortex Microcontrollers.

# How to use
1. Connect the two boards as shown below.
<p align="center">
  <img width="750" height="380" src="https://github.com/idreamsi/bootloader-fix-for-makerdiary-nrf52840-mdk-usb-dongle/blob/main/wiring.jpg?raw=true">
</p>

2. Download the [JLink Windows v7.94g](https://www.segger.com/downloads/jlink/) program and run ```JFlashLite.exe``` from its installation path.

3. Select ```nRF52840_xxAA``` from the device section and select ```SWD``` in the interface section. Click ```OK``` and select the [firmware file](https://github.com/idreamsi/bootloader-fix-for-makerdiary-nrf52840-mdk-usb-dongle/blob/main/firmware/uf2_bootloader/0.7.1/uf2_bootloader-nrf52840_mdk_usb_dongle-0.7.1-s140_6.1.1.hex) from the ```Data File (bin/hex/mot/...)``` section in the new window. At the end, press the ```Program Device``` key. Before starting the process, make sure that the ```JLINK-OB drivers``` are installed.
