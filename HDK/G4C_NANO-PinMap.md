# STM32G474CBT6 板级引脚映射 / Board Pin Map（PinMap）

> 本文件定义 G4C_NANO 板级引脚与功能映射，供查阅与开发参考。
> This file defines the G4C_NANO board pin / function mapping for reference and development.

## RGB LED 三色灯 / RGB LED

| 功能 Function | 引脚 Pin | 说明 Description |
|------|------|------|
| RED 红 | **PA0** | 红色 LED / Red LED |
| GREEN 绿 | **PA1** | 绿色 LED / Green LED |
| BLUE 蓝 | **PA2** | 蓝色 LED / Blue LED |

## 按键 / Key

| 功能 Function | 引脚 Pin | 说明 Description |
|------|------|------|
| RST_KEY | **PG10** | 复位按键，EXTI10 / Reset key, EXTI10 |
| BOOT0_KEY | **PB8** | BOOT0 按键，EXTI8 / BOOT0 key, EXTI8 |

## SPI LCD 屏 / SPI LCD

| 功能 Function | 引脚 Pin | 说明 Description |
|------|------|------|
| LCD_PWR | **PB7** | 电源 / Power |
| LCD_RST | **PB6** | 复位 / Reset |
| LCD_DC | **PB4** | 数据/命令 / Data / Command |
| LCD_SDA | **PB5** | 数据 / Data (MOSI) |
| LCD_SCL | **PB3** | 时钟 / Clock |
| LCD_CS | **PA15** | 片选 / Chip select |

## USB

| 功能 Function | 引脚 Pin | 说明 Description |
|------|------|------|
| DM | **PA11** | USB DM |
| DP | **PA12** | USB DP |

## SPI Flash 闪存 / SPI Flash

| 功能 Function | 引脚 Pin | 说明 Description |
|------|------|------|
| CLK | **PB13** | 时钟 / Clock |
| CS | **PB12** | 片选 / Chip select |
| MOSI | **PB14** | 主机输出 / Master out |
| MISO | **PB15** | 主机输入 / Master in |
