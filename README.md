# ESP32 S3 Box 3

## esphome config for home assistant

- [config](config) - esphome config.
- https://github.com/sammcj/esphome-esp-s3-box-3-volume - custom volume control component.

## assistant illustrations

- [illustrations](illustrations) - custom assistant illustrations.

## GPIO Pinout

| GPIO    | Function                                    |
| ------- | ------------------------------------------- |
| GPIO-00 | MCU-BOOT                                    |
| GPIO-01 | Speaker Mute-Status                         |
| GPIO-02 | I2S MCLK                                    |
| GPIO-03 | Touch-Screen TT21100 Interrupt Pin          |
| GPIO-04 | ILI92xxx Display DC-Pin (SPI: CLK-Pin)      |
| GPIO-05 | ILI92xxx Display CS-Pin (SPI: MOSI-Pin)     |
| GPIO-06 | ILI92xxx Display SDA                        |
| GPIO-07 | ILI92xxx Display SCK                        |
| GPIO-17 | I2S_SCLK                                    |
| GPIO-40 | I2C_SCL (Temp & Hum) -- SENSOR v1.1 [AHT30] |
| GPIO-41 | I2C_SDA (Temp & Hum) -- SENSOR v1.1 [AHT30] |
