# Piano_Tiles
Piano Tiles game utlizing Custom PCB. 

Microprocessor: STM32F09 (ARM Cortex-M0)
Programming: C
Internal Peripherals: GPIO Timers SPI DAC
External Peripherals: GPIO SPI Analog

Description:
The MSP2202 TFT LCD to show the player the note we want them to play (SPI).
8 Push-buttons to collect user input (GPIO).
The SOC1602A OLED to display instructions and score (SPI).
The notes being shown on the TFT display will be played using our own encoding.
Audio Barrrel Jack for sound (DAC).
