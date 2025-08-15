# ESP32-CNC
An ESP32-based CNC router/3D printer controller board designed for FluidNC

[OSHWLab URL](https://oshwlab.com/arcaegecengiz/picostep)

<img width="1328" height="873" alt="Screenshot_20250815_024137" src="https://github.com/user-attachments/assets/93a41342-dcba-402f-9ae5-29812afae3aa" />

## Features
- 4 DRV8825 stepper motor drivers capable of up to 2.5A 24V each (with the ability to set the maximum current)
- 4 high-current MOSFETs, up to 30A at 24V per MOSFET, designed for controlling spindles or hotends
- 8 switch connections (7 general purpose/limit switches and 1 emergency stop, though this can be used as a general purpose switch too)
- Ability to configure microstepping using DIP switches
- 4 WS2812B addressable RGB LEDs for status indication
- USB-C port
- Detailed silkscreen

## Schematics & board layout
<img width="1920" height="1360" alt="image" src="https://github.com/user-attachments/assets/222f87f0-b013-4642-881c-df1cac1aac36" />

<img width="1920" height="1360" alt="image" src="https://github.com/user-attachments/assets/92e01074-6338-47f3-8ddf-7718408789a8" />

Thank you to [JLCPCB](https://jlcpcb.com) and [Hack Club](https://hackclub.com) for making this project possible
