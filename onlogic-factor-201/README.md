# Installation

## RS-485
`sudo apt install libconfuse-dev libusb-1.0-0-dev`
`sudo apt install cmake build-essential`
Copy the libftdi1-1.5.tar.bz2
`tar -xf libftdi1-1.5.tar.bz2`
`mkdir libftdi1-1.5/build && cd libftdi1-1.5/build`
`cmake -DCMAKE_INSTALL_PREFIX="/usr" ../`
`make && sudo make install`
`wget static.onlogic.com/resources/firmware/documentation/configs/FR200_RS485.conf`
`sudo ftdi_eeprom --flash-eeprom FR200_RS485.conf`
`sudo ftdi_eeprom --flash-eeprom FR200_RS485.conf`
`sudo ftdi_eeprom --flash-eeprom FR200_RS485.conf`
`sudo shutdown -r now`