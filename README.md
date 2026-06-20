The original Waveshare example for the Nucleo-F103RB is here:

https://www.waveshare.com/wiki/2.4inch_LCD_Module#STM32_Hardware_Connection

https://www.waveshare.com/wiki/2.4inch_LCD_Module#Using_with_STM32

I adopted it for the Nucleo-F767ZI.

![](/Doc/IMG_E6319.JPG)


Connections (https://os.mbed.com/platforms/ST-Nucleo-F767ZI/)


| LCD      | Port     | Function     |
|----------|----------|------------- |
| VCC      | 3,3V     | Vcc          |
| GND      | GND      | GND          |
| DIN      | PA7      | SPI1_MOSI    |
| CLK      | PA5      | SPI1_CLK     |
| CS       | PB6      | Chip Select  |
| DC       | PA0      | Data/Command |
| RST      | PB9      | Reset        |
| BL       | -        | Backlight    |


Hardware

LCD: https://www.waveshare.com/wiki/2.4inch_LCD_Module?srsltid=AfmBOoqtv3bq-mZfPtsi2BxiewwQnIkomXrloIzpVwGw_HnrOcmvQZar

Nucleo-STM32767ZI: https://www.st.com/en/evaluation-tools/nucleo-f767zi.html

YouTube-Video: https://youtube.com/shorts/c0dqOxOgvbQ?feature=share
