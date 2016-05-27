# Circuits
This repository contains the schematics and simulation of some useful circuits.

## Battery Backup Circuit
This circuit provides a battery backup when the main power is out.
In addition, it includes a voltage comparator that determines if the battery backup is being used.
This voltage comparator could be sent to a GPIO on a microcontroller.

![alt text][backup]

## Interface Relay with a Microcontroller
In this circuit, a microcontroller digital output is used to interface a relay.

![alt text][relay]

[backup]: ./BatteryBackup/BatteryBackup.png "Battery Backup Circuit"
[relay]: ./Interface-Relay-MCU/Relay-MCU.png "Relay interfaced with a GPIO"
