# DC_Power_Brick

## Two Channel DC Power Controller.
  - DRV8704 SPI based FET driver
  -  8..52V
  -  PWM 500kHz
  -  CSD18540Q5B FET 30 / 400A (peak)

[Datasheet Driver](./datasheets/drv8704.pdf)
[Datasheet FET](./datasheets/csd18540q5b.pdf)


## 2x Two Channel Precision Thermistor ADC
  - ADS1220
  - Configured for two channel 10K NTC thermistor measurements using internal current source and external reference 22k resistor.

[Datasheet ADS1220](./datasheets/ads1220.pdf)

![Scematics](./KiCad/Power_Brick/Power_Brick_Schematics/Power_Brick.svg)

![PCB](./KiCad/Power_Brick/Power_Brick_PCB/output.svg)

![3D](./KiCad/Power_Brick_front.png)
![3D](./KiCad/Power_Brick_back.png)
