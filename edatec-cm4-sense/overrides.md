# config.txt
## DT overlays

dtoverlay=ed-sdhost

dtoverlay=i2c-rtc,pcf8563

dtoverlay=spi1-1cs,cs0_pin=18,cs0_spidev=disabled

dtoverlay=ed-mcp2515-spi1-can0

dtoverlay=uart2

dtoverlay=uart3

dtoverlay=uart4

dtoverlay=uart5

## UART

enable_uart=1

## GPIO

gpio=11=op,dl

## DT params

dtparam=ant2