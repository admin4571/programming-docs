
# SUMMARY

## Actuators

![alt text](https://github.com/frc4571/programming-docs/raw/master/images/image-rel.JPG "FRC Actuators")

### Speed Controllers ( Control the motors )
  - Victors ( Victor, Victor SP )
  - Talons ( Talon, Talon SRX )
  - Jaguars

### Motors ( Moves the attached component )(???)
  - Servos
  - Steppers

### Relays ( Control solenoids, lights, custom circuits )(???)
  - Spike H-Bridge Relay

### Solenoids ( Operate pneumatic cylinders )
  - Single Solenoid
  - Double Solenoid

## Sensors

![alt text](https://github.com/frc4571/programming-docs/raw/master/images/sensors.JPG "FRC Sensors")

### Counting Sensors ( Rotations, Pulses etc )
  - Gear Tooth Sensor [ Direction sensing ]
  - Ultrasonic sensor [ Count time of pulse flight ]
  - Encoders [ Rate of rotation, distance wheel has turned ]
    - Optical Encoder (Quadrature Encoders) { Assigned to FPGA module based on type of encoding }

### Direction Sensors ( Direction of robot movement )
  - Gyro
    - Analog Gyro
    - Digital Gyro (ADXRS450)

### Distance Sensors ( Distance from a surface )
  - Ultrasonic sensor
    - Ping-Response (ex. Devantech SRF04, VEX Ultrasonic Rangefinder) { Ultrasonic.java }
    - Analog  (ex. Maxbotix LV-MaxSonar-EZ1)
    - Digital (ex. Maxbotix I2CXL-MaxSonar-EZ2) communicate via I2C, SPI, Serial
  - Encoders

### Switches ( Controlling behavior - 1 || 0 )
  - Limit Switches

### Accelerometers ( Acceleration and Tilt )
  - 2 axis analog accelerometer
  - ADXL345 Accelerometer
  - Built-in accelerometer

### Potentiometers ( Joint angle or linear motion )
  - Analog sensor

# DETAILS

## Actuators

### Speed controllers

#### What are speed controllers?

https://en.wikipedia.org/wiki/Electronic_speed_control

### Types of Speed controllers

#### Victors v/s Talons vs/ Jaguar

https://content.vexrobotics.com/vexpro/pdf/Victor-SP-Talon-SRX-Info-Sheet-20140819.pdf

### Solenoids

https://en.wikipedia.org/wiki/Solenoid

#### What are solenoids

#### Single solenoid vs Double solenoid

https://www.chiefdelphi.com/forums/showthread.php?t=33594

## Sensors

### Speed Sensors

#### Gear tooth sensor

https://www.youtube.com/watch?v=Az98AoYmd4Y

### Power

#### Power distribution Panel

http://wpilib.screenstepslive.com/s/4485/m/13809/l/219414-power-distribution-panel

### Direction sensors

#### Gyro

http://wpilib.screenstepslive.com/s/4485/m/13810/l/241871?data-resolve-url=true&data-manual-id=13810

http://www.analog.com/media/en/technical-documentation/data-sheets/ADXRS450.pdf

### Distance Sensors

#### Ultrasonic Sensors
- Ping/response : http://www.acroname.com/robotics/parts/R93-SRF04.html
                  http://www.vexrobotics.com/276-2155.html
- Analog : http://www.maxbotix.com/Ultrasonic_Sensors/MB1010.htm
- Digital : http://www.maxbotix.com/Ultrasonic_Sensors/MB1222.htm

#### Communication channels

- I2C : http://www.i2c-bus.org/i2c-bus/
- SPI : https://learn.sparkfun.com/tutorials/serial-peripheral-interface-spi
- Serial : https://en.wikipedia.org/wiki/Serial_communication

### Relays

- Spike H-Bridge Relay : http://www.vexrobotics.com/217-0220.html

# Appendix

## CAN

- https://en.wikipedia.org/wiki/CAN_bus
- http://www.ni.com/white-paper/2732/en/

### CAN Devices

- Jaguar speed controllers
- CAN-Talon speed controllers
- Power Distribution Panel (PDP)
- Pneumatics Control Module (PCM)
