# Sensor Interfacing & Actuator Control with STM32

## Overview
This project demonstrates the fundamental concepts of embedded control systems: reading environmental data from a sensor and using that data to drive an actuator. 

## Technical Implementation
* **Sensing:** Interfaced sensors (e.g., Ultrasonic, Potentiometer, or LDR) using GPIO and ADC (Analog-to-Digital Conversion).
* **Processing:** Implemented threshold logic and signal conditioning within the STM32 firmware.
* **Actuation:** Controlled actuators (e.g., Servo Motors, DC Motors via H-Bridge, or Relays) using PWM (Pulse Width Modulation) and digital output signals.
* **Interrupts:** Utilized External Interrupts (EXTI) for real-time responsiveness to sensor triggers.

## Hardware Stack
* **Microcontroller:** STM32F103 (Blue Pill) / STM32F4 Discovery
* **Peripherals:** ADC, Timers (PWM mode), UART (for debugging)
* **Components:** Servo Motor/DC Motor, Sensor Modules, Breadboard, and Jumper wires.

## Software
* **Language:** C
* **Environment:** STM32CubeIDE / Keil uVision
* **Driver Layer:** HAL (Hardware Abstraction Layer)
