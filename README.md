# EsPlay Micro Hardware
This board is micro version (smaller device but same as powerfull as big brother EsPlay Hardware), an ESP 32 Based portable gaming console.

![bottom_layer](https://raw.githubusercontent.com/pebri86/esplay_micro_hardware/master/docs/esplay_micro_bottom.png)

![top_layer](https://raw.githubusercontent.com/pebri86/esplay_micro_hardware/master/docs/esplay_micro_top.png)

Featured
--------
- ESP32 WROVER, Dual core processor with Integrated 4MB Flash + 4MB PSRAM
- Integrated WIFI and Bluetooth 4 BLE
- 2,4" ILI9341 TFT Panel
- More button (expanded via PCF8574 I2C GPIO)
- Micro SD slot connected to SDMMC Host in 1 Line Mode for save GPIO pin
- Integrated I2S DAC via UDA1334A
- Integrated USB to Serial for programming and debugging using CH340C/G
- Built-in ~~TP4056~~ LTC4054 Li-Po charger
- ~~Touchscreen, yes resitive touchscreen of ili9341 now connected to ESP32 GPIO~~
- I2C port for expandable function
- 3,5mm Headphone jack
- Smaller Size, PCB only 100 x 50 mm.

Firmwares
---------
Firmware available visit my repository [here](https://github.com/pebri86/esplay-retro-emulation) for firmware and emulators.

Changelogs
----------
### 27 Aug 2019
- Remove touchscreen control due to other function that more important
- Audio amplifier shutdown
- Audio amplifier chip change to PAM8304
- Change li-po charger with LTC4054
- Add Charger management sensing (USB plug and Chrge state)
- Add ESD Protection on SDCard
- Add status LED (charging) controlled via ESP32 GPIO

### 06 May 2019
- Add amplifier circuits for internal speaker.
- Add ground for EXP pin ESP32 Wrover module.
- Connect micro usb shield to ground.
- Remove some unnecessary vias.
