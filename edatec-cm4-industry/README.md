# Installation
## Preparation
* Install `rpiboot` on your device
    * For Windows users, install the [rpiboot installer](https://github.com/raspberrypi/usbboot/raw/master/win32/rpiboot_setup.exe)
    * For Mac & Linux users, follow the [build instructions](https://github.com/raspberrypi/usbboot#building)
* Install the [Balena Etcher](https://etcher.balena.io/#download-etcher) on your device

## Flash
1. Download the Balena OS from the [muv-edge-pro](https://dashboard.balena-cloud.com/fleets/2036289) fleet
2. Plugin the mini USB cable into the device (inside of the device)
3. Plug in the power
4. Execute `rpiboot` (the drive should be visible now, if not power off and on again and re-run the `rpiboot`)
5. Flash the image with the `Balena Etcher`

## Configuration
1. Plugin the mini USB cable into the device (inside of the device)
2. Plug in the power
3. Execute rpiboot.exe (the drive should be visible now, if not power off and on again and re-run the rpiboot.exe)
4. Install the Balena OS downloaded from the `muv-edge-pro` fleet
5. Move the `dt-blob.bin` file to the `/boot` directory 
6. Move the `cellular` and the `ethernet` files to the `/system-connections` directory 
7. Move the `stmpe811.dtbo` file to the `/boot/overlays` directory
8. Connect the hardware via ethernet to the internet and wait for the automatic privisioning on Balena
9. Enable a new SIM card at the Swisscom CMP platfrom and insert it into the hardware