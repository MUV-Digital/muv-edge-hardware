# Installation
1. Install the Balena OS downloaded from the `muv-edge-pro` fleet
2. Move the `dt-blob.bin` file to the `/boot` directory 
3. Move the `cellular` and the `ethernet` files to the `/system-connections` directory 
4. Move the `stmpe811.dtbo` file to the `/boot/overlays` directory
5. Connect the hardware via ethernet to the internet and wait for the automatic privisioning on Balena
6. Enable a new SIM card at the Swisscom CMP platfrom and insert it into the hardware