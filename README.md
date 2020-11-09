# uPPico 
> **uP** stands for Uncle Pi <br />
> Pronounced: "U. Pi Pico"  /yə/ /pī/ /pikō/ 

![Photo of a uPPico connnected to a battery](https://github.com/MGZ-LLC/uPPico/blob/main/media/uPPico-nRF51422.jpg)

## About

The **uPPico** by [MGZ](https://github.com/MGZ-LLC/MGZ-LLC/blob/main/README.md) was designed to be a generic wearable BLE device that was originally created to fulfil the needs of two different projects. 

- One project was for posture detection (with haptic feedback to the user)
- The second was to use two **uPPico**s to measure sports movement

The major features are that the device is complete with an accelerometer and magnetometer IMU (acting as a compass or independently), one IO already wired to control haptic vibrator, 2MB storage of flash memory (persistent), 5V power supply and 1 cell LiPo battery charger circuit on board. 

The board also offers the standard feature set of Arduino including one LED, UART, I2C, SPI, 2 additional GPIO pins available.

### Open platform

Every time we add a new feature for a project (that we are allowed to share) it will be added to the public repo as a library.

The **uP** environment is an open platform, currently there are two versions - **uPTiny** and **uPPico**. The **uPPico** has higher performance and is smaller than the **uPTiny**. However the **uPTiny** is cheaper and includes a micro-USB port for UART whereas the **uPPico** requires an external development board to connect the UART.



## Specifications
#### MCU
SoC: nRF51422 xxac (capable of BLE and ANT)
Core: ARM Cortex-M0, 32 MHz 
Memory: 32 kB RAM, 256 kB ROM 
Clock & Power: 1.8 V, 32 MHz 
Communication: SPI, UART, I2C

#### Additional

2MB memory via SPI
IMU with magnetometer
Battery charging and control circuit is included



#### Dimensions (uPPico)

- 12.3mm x 18mm x 6mm for the board (battery excluded)
