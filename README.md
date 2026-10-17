# STM32 Button-Controlled LED

A beginner STM32 project using the NUCLEO-C031C6 and STM32 HAL.

## What it does

Turns the onboard LD4 LED on while the user button is pressed, and off when released.

## Hardware pins

- User button: PC13 (active low)
- LD4 LED: PA5

## Tools

- STM32CubeIDE
- STM32 HAL
- Wokwi simulator

## What I learned

- Read a GPIO input with `HAL_GPIO_ReadPin`
- Control an LED with `HAL_GPIO_WritePin`
- Handle an active-low button
