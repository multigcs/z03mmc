
# my devboard

## pinout
| header pin | test pin | mcu pin | function | alt func. |
| --- | --- | --- | --- | --- |
| 1  | P16 |     |     |    |
| 2  | P15 | PC3 | I2C_SCK | PWM1/UART_RX/I2C_SCK/XC32K_I/PGA_N1 |
| 3  | P18 |     |     |   |
| 4  | P2  |     |     |   |
| 5  | P13 | PC2 | I2C_SDA | PWM0/7816_TRX(UART_TX)/I2C_SDA/XC32K_O/PGA_P1 |
| 6  | RST | PA5 | SW1 | DM |
| 7  | P7  | PD7 | SW2 | SPI_CK/I2S_BCK/7816_TRX(UART_TX) |
| 8  | P17 |     |     |  |
| 9  | P3  |     |     |  |
| 10 | P9  | PC4 | LED | PWM2/UART_CTS/PWM0_N/sar_aio<8> |
| 11 | P8  | PA6 | SW3 | DP(SWS) |
| 12 | P5  |     |     |  |
| 13 | P14 | PA7 |     | SWS/UART_RTS |
| 14 | P10 | PB6 | ?   | SDM_P1/SPI_DI/UART_RTS/lc_comp_ain<6>/sar_aio<6> |
| 15 | 3V3 | 3V3 |     |  |
| 16 | GND | GND |     |  |
|    | B1  | PB7 |     | SDM_N1/SPI_DO/UART_RX/lc_comp_ain<7>/sar_aio<7> |


| header pin | PROGRAMMER |
| --- | --- |
| B1 | RX |
| B2 | TX |
| B3 | 3V3 |
| B4 | GND |

