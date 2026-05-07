# esp-water-meter
Diehl Hydrus water meter esphome config for a ESP32 with a CC1101 device working at 868Mhz

## Check esphome version first

`esphome --version`

## Install esphome via pip if needed

`pip3 install esphome==2026.4.4`

## Compile the project

`esphome compile esp32-hydrus.yaml`

## Upload to the esp32 device

`esphome upload esp32-hydrus.yaml --device $ESPHOME_IP`

## Check logs

`esphome logs esp32-hydrus.yaml --device $ESPHOME_IP`

## In case of a new build and image not being updated cleanup old build data

`esphome clean esp32-hydrus.yaml`

`rm -rf .esphome/`
