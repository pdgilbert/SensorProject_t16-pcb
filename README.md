# SensorProject_t16-pcb
Connect multiple temperature sensors to an analog digital converter.

##  Status: Prototype.

## Summary

Kicad project WIP.

PCB design to connect multiple (up to 16) thermistor temperature sensors to an ads1115 with I2C
output to connect to an MCU. Connectors are  2-pin JST XH_B2B-XH-A, as commonly used on NTC 10K 3950 sensors.
These sensors are inexpensive and easily available in lengths up to 3m. 
The MCU socket is arranged for a blackpill module.

Related software is in repository https://github.com/pdgilbert/SensorProject_t16.

The `.png` files are produced from kicad  in the `3D Viewer`  with `File > Export Current View as PNG`.
![alt text](Graphics/t16-bk_pill-top1.png)

![alt text](Graphics/t16-bk_pill-top2.png)

![alt text](Graphics/t16-bk_pill-bottom1.png)

## History

 - Version 0.1.1 2025-01 has pull up resistors added but has not been manufactured/tested.

 - Version 0.1.0 2024-05 needs manual addition of pull up resistors on the I2C lines. 
   With this modification it works with `blackpill` `stm32f401` or `stm32f411` inserted.
