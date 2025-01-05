# Non-destructive Energy Meter

Record Pulses


## Requirements
Accurately see each pulse

Must run on battery

## Solution Overview

Count the number of pulses every x minutes
Multiply by ZZZ factor to give kWh energy used during the xx minutes
Calculate current power use Watt
Possibly calculate dailiy energy conumption and reset at midnight
BLE to reduce power consumption (no Wifi since it consumes too much power)
Probably can't sleep because it needs to read the pulses, but perhaps there is a sleep mode for when BLE is off

## Circuit Design
LDR    
ESP32, BLE
Battery

### Battery sizing


## Firmware Components and Libraries

C++
Adruino Framework
BTHome
Other libraries



