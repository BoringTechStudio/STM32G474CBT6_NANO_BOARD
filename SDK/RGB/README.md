# RGB

Independent STM32CubeMX / Keil MDK example for STM32G474CBT6 (G4C_NANO board, LQFP48).

## Behavior

Prints hello world! over USART1, echoes received bytes, and toggles the RGB LEDs together every 500 ms.

## Connections

| Signal | Pin | Configuration |
| --- | --- | --- |
| Red LED | PA0 | Push-pull output, active low |
| Green LED | PA1 | Push-pull output, active low |
| Blue LED | PA2 | Push-pull output, active low |
| USART1 TX | PA9 | 115200 baud serial output |
| USART1 RX | PA10 | 115200 baud serial input |

## Build and use

Open the .uvprojx in MDK-ARM with Keil MDK, build, and program the target. The STM32G474CBT6.ioc file contains the matching CubeMX configuration.