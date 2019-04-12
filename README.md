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
- Integrated USB to Serial for programming and debugging using CH340C
- Built-in TP4056 Li-Po charger
- Touchscreen, yes resitive touchscreen of ili9341 now connected to ESP32 GPIO
- I2C port for expandable function
- 3,5mm Headphone jack
- Smaller Size, PCB only 100 x 50 mm.

Firmwares
---------
Currently no firmware release for this board but it's fairly easy to port from Esplay repository or odroid go. Later i'll add software support for this hardware.
