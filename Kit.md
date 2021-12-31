# Car Kit Contents


Assuming you have the missing components, the included instructions were sufficient for assembly. 

An improvised battery solution required some velcro, hot glue, and creativity.

### Included in Kit
- Basic setup instructions
- Pre-configured 32GB SD card 
- USB SD card reader/writer
- Car chasis, wheels, nuts, standoffs
- 4 brushed motors with gearboxes
- 2 led headlights
- Wifi camera 
- Camera tilt servo
- Ultrasonic sensors
- STM32 control board

### Not Included in Kit
- Raspberry Pi 
- 5v battery 
- USB C cable for power (plugs into STM32 board)

### Complaints

- Lack of a standard 18650 battery mount is unfortunate. An old 10000 mAh lipo phone backup battery velcroed to the bottom worked reasonably well for me. 

- The low speed torque is too low to move the car at slower speeds for scanning video or obstacle detection. Better would be slow, higher torque motors at 125RPM or so. Speed is not as important as movement accuracy for this car.

- Ultrasonic sensor is fixed facing front. It would be better on a servo to pan left and right.