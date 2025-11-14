# Ultra-Precision Current & Voltage Measurement System

A precision measurement system built using an **STM32 microcontroller** to measure voltage (1–12V) and current (1µA–100mA) with minimal load on the Device Under Test (DUT).

## Features

* Voltage measurement: **1V–12V**
* Current measurement: **1µA–100mA**
* **Three measurement sub-circuits**: microamp, milliamp, voltage
* **I2C OLED display** for real-time readings
* **UART output** via FTDI for PC monitoring
* High‑resolution ADC with low‑noise signal conditioning
* Developed using **STM32CubeIDE**

## Hardware Overview

* STM32 microcontroller
* OLED Display (I2C)
* FTDI USB‑to‑UART converter
* Separate precision circuits for microamp/milliamp/voltage ranges
* Switch-based range selection

## Software Overview

* Embedded C (STM32CubeIDE)
* I2C driver for OLED
* UART communication for PC data visualization
* ADC sampling and filtering routines

## How It Works

1. User selects measurement range using switches.
2. Signal passes through corresponding precision circuit.
3. STM32 ADC measures and processes the signal.
4. Output is displayed on OLED and sent to PC via UART.

## Team members
Gihan chamara
Supun chamara
Manuja sandayuru
Sithira sanjula
Chiranji udantha
Dilakshitha manamperi

This project can be used for educational and research purposes.
