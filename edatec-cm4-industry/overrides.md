# config.txt

## DT overlays
dtoverlay=spi1-1cs,cs0_pin=16

dtoverlay=jedec-spi-nor,flash-spi1-0

dtoverlay=i2c-rtc,pcf8563

dtoverlay=ads1015,cha_gain=1,chb_gain=1,chc_gain=1,chd_gain=1

dtoverlay=uart3

dtoverlay=uart4

dtoverlay=uart5

## OTG
otg_mode=1

## GPIO
gpio=7=ip,pu

gpio=6=ip,pu