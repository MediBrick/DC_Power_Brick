# Power Brick

The Power Brick can control power to resistive heater, thermo electric cooler/heater or DC motor.
It requires 8V or larger input and might be able to handle 30A (4 oz copper).

## Two Channel DC Power Controller.
  - DRV8704 FET driver
  -  8..52V
  -  SPI interface for  monitoring
  -  PWM 500kHz
  -  CSD18540Q5B FET 30 / 400A (peak)

[Datasheet Driver](./datasheets/drv8704.pdf)
[Datasheet FET](./datasheets/csd18540q5b.pdf)

### Overview
<img src="./datasheets/drv8704.png" alt="DRV8704" width="500" />

### Control Logic
<img src="./datasheets/drv8704-control_diagram.png" alt="DRV8704-diagram" width="500" />
<img src="./datasheets/drv8704-control.png" alt="DRV8704-control" width="500" />


## 2x Two Channel Precision Thermistor ADC
  - ADS1220
  - Configured for two channel 10K NTC thermistor measurements using internal current source and external reference 22k resistor.

[Datasheet ADS1220](./datasheets/ads1220.pdf)

<img src="./datasheets/ads1220.png" alt="ADS1220" width="500" />

This design requires that both temperature sensors are attached. If one is not populated, the measurement circuit is interrupted and no temperature is reported.

## Power Brick PCB Design

The following files were created for this project using KiCad.

<img src="./KiCad/Power_Brick/Power_Brick/Power_Brick_Schematics/Power_Brick.svg" alt="Schematics" width="500" />

<img src="./KiCad/Power_Brick/Power_Brick/Power_Brick_PCB/PCB.png" alt="Schematics" width="500" />
<img src="./KiCad/Power_Brick_front.png" alt="3D" width="500" />
<img src="./KiCad/Power_Brick_back.png" alt="3D" width="500" />


