# DC_Power_Brick

## Two Channel DC Power Controller.
  - DRV8704 SPI based FET driver
  -  8..52V
  -  PWM 500kHz
  -  CSD18540Q5B FET 30 / 400A (peak)

[Datasheet Driver](./datasheets/drv8704.pdf)
[Datasheet FET](./datasheets/csd18540q5b.pdf)
<img src="./datasheets/drv8704.png" alt="DRV8704" width="500" />


## 2x Two Channel Precision Thermistor ADC
  - ADS1220
  - Configured for two channel 10K NTC thermistor measurements using internal current source and external reference 22k resistor.

[Datasheet ADS1220](./datasheets/ads1220.pdf)
<img src="./datasheets/ads1220.png" alt="ADS1220" width="500" />

## PCB Design

![Scematics](./KiCad/Power_Brick/Power_Brick_Schematics/Power_Brick.svg)

<img src="./KiCad/Power_Brick/Power_Brick_PCB/output.svg" alt="PCB" width="500" />

<img src="./KiCad/Power_Brick_front.png" alt="3D" width="500" />
<img src="./KiCad/Power_Brick_back.png" alt="3D" width="500" />


