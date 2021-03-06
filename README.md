# Leak protection system
The system is implemented as a group of interrelated devices (modules):
* NodeMCU main unit (ESP8266) - designed for direct control of the actuators (valves) for covering the fluid;
* wired module - wired water leakage detector;
* wireless (NRF24L01) module (STM32F030F4P6) - wireless leakage detector.

## System modules

### Main unit
Detailed sensor description https://github.com/leech001/LeakControl/tree/master/main_module

### Wired sensor
It is intended for leak detection.
Detailed sensor description https://github.com/leech001/LeakControl/tree/master/wired_module

### Wireless sensor
It is intended for leak detection and alarm signal transmission to the head unit.
Detailed sensor description https://github.com/leech001/rf-leak-module
