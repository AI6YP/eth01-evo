### eth01-evo board

![](assets/top-bot.webp)

![](assets/pinout.webp)

![](assets/bd.webp)

### DM9051

Davicom DM9051 SPI Ethernet Controller

https://www.dacomwest.de/en/?view=article&id=207:dm9051-en

https://www.dacomwest.de/en/component/edocman/dm9051-i-12-mco-ds-p01-03302015/download

| DM9051 | signal   | esp32 |
|--------|----------|-------|
| 17     | SPI_CN   | IO9   |
| 18     | SPI_CLK  | IO7   |
| 19     | SPI_MOSI | IO10  |
| 10     | SPI_MISO | IO3   |
| 24     | INT      | IO8   |
| 27     | RSTB     | IO6   |

### Ethernet Driver

https://docs.espressif.com/projects/esp-idf/en/latest/esp32c3/api-reference/network/esp_eth.html#spi-ethernet-module

### RJ45 connector

![](assets/esp32-passive-poe-ethernet-jack.png)

https://pcbartists.com/design/embedded/esp32-passive-poe-power-over-ethernet-design-schematic


### WT32C3-S5 module

http://en.wireless-tag.com/product-item-18.html

https://img01.71360.com/file/read/www2/M00/6A/08/rBwBEmSBkI6AUYJDABeEbPVIioE463.pdf?dl=1&dlf=WT32C3-S5+Datasheet+V1.0.3.pdf

https://templates.blakadder.com/wireless_tag_WT32C3-S5.html


### ESP32-C3 MCU

https://www.espressif.com/sites/default/files/documentation/esp32-c3_datasheet_en.pdf

https://docs.espressif.com/projects/esp-idf/en/latest/esp32c3/

https://docs.espressif.com/projects/esp-idf/en/latest/esp32c3/get-started/establish-serial-connection.html

### Other

https://github.com/esphome/feature-requests/issues/2427
