# Mecatron-EE-Probation-Task
- MCM EE Design (KiCad)

## Description

Design a Schematic + PCB for Motor Control Module

## Overview

The MCM has 2 functions:
1. Receive and transform a command matrix into nominal PWM signals for motors
2. Generate PWM signals required for driving of motors

<img width="2659" height="488" alt="image" src="https://github.com/user-attachments/assets/c17a4496-5a70-4d76-8873-1da8e5298a79" />



## Electronics Components

Design the **schematic** for the PCB that can drive 4x micro-motors, bi-directionally. in a very small form factor
- Power Supply: 1S Lipo battery
- MCU: [STM32C031G6U6](https://www.st.com/resource/en/datasheet/stm32c031g6.pdf)
- Motor Driver: [DRV8837](https://www.ti.com/lit/ds/symlink/drv8837.pdf?ts=1759236119849&ref_url=https%253A%252F%252Fwww.ti.com%252Fproduct%252FDRV8837)
- LDO (3.3V): [MCP1700 SOT-23](https://ww1.microchip.com/downloads/en/DeviceDoc/MCP1700-Low-Quiescent-Current-LDO-20001826E.pdf)
