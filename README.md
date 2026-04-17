# Industrial Environmental Monitoring System

# Overview

This project presents an industrial environmental monitoring system using an STM32 microcontroller. It measures air quality, temperature, and humidity using MQ135 and DHT11 sensors and transmits data using Modbus RTU over RS485.

# Components Used

* STM32 Microcontroller
* MQ135 Gas Sensor
* DHT11 Temperature & Humidity Sensor
* MAX485 (RS485 Communication)
* Custom PCB (Altium Design)

## Communication

* Protocol: Modbus RTU
* Interface: UART
* Physical Layer: RS485

# Working Principle

1. Sensors collect environmental data
2. STM32 processes the data
3. Data is converted into Modbus format
4. MAX485 transmits via RS485
5. Master device reads the data

# Project Structure

* `Code/` → STM32CubeIDE project files
* `PCB_Design/` → Altium design files and PCB images
* `Images/` → Setup, output, and PCB photos
  
#Features

* Real-time monitoring
* Industrial communication using Modbus RTU
* Reliable long-distance RS485 communication
* Custom PCB implementation

# Applications

* Industrial environmental monitoring
* Air quality monitoring systems
* Smart factories (Industry 4.0)

---

# Author

Suthan S
ECE Student
