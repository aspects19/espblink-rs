# ESP blinky rs
### Introduction

This is a blinking esp32's internal LED implimentation in lust the no_std way (bare metal).

### Target hardware
- **Chip** ESP32 
- **LED pin** GPIO02

### Installation 

To reproduce this project locally you need to:

1. Setup the environment for MCU programing using 
  ```sh
    rustup update
    # stable setup
    rustup toolchain install stable --component rust-src
  ```
2. Then setup the target
  ```
    # Change to your target mcu 
    rustup target add xtensa-esp32-none-elf
  ```
