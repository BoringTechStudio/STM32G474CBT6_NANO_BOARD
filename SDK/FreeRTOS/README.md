# FreeRTOS Applications (STM32G474CBT6 / G4C_NANO)

9 FreeRTOS applications ported from `STM32Cube_FW_G4_V1.6.3/Projects/STM32G474E-EVAL/Applications/FreeRTOS`
to the G4C_NANO board. Each project is standalone (AC6 V6.21, Keil MDK, local `Drivers` + `Middlewares`).

## Applications

FreeRTOS_ThreadCreation, FreeRTOS_Mail, FreeRTOS_Queues, FreeRTOS_Semaphore,
FreeRTOS_SemaphoreFromISR, FreeRTOS_Signal, FreeRTOS_SignalFromISR,
FreeRTOS_Mutexes, FreeRTOS_Timers.

## LED / button mapping (E-EVAL -> this board)

| E-EVAL | This board |
| --- | --- |
| LED1 (green) | LED_GREEN (PA1) |
| LED2 (MFX) | LED_BLUE (PA2) |
| LED3 (red) | LED_RED (PA0) |
| LED4 (MFX) | LED_RED (PA0) |
| BUTTON_USER (PC13) | BUTTON_RST (PG10) |

RGB pins are selected automatically by the board macro `G4C_NANO` in the boring BSP.

All 9 projects compile with 0 errors / 0 warnings on AC6.
