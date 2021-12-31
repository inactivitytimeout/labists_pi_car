# Car Kit Contents

Assuming you have the missing components, the included instructions were sufficient for assembly.

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

### What's Good

- The car's aesthetic design, with the black top cover, looks nicer than others on the market

- $80 price is reasonable for a kit

- Fairly easy to assemble
  
- You can program and customize car behavior in Python with some extra work

### Complaints

- Lack of a standard 18650 battery mount is unfortunate. An old 10000 mAh lipo phone backup battery velcroed to the bottom worked reasonably well for me.

- Too little torque at low speed to move the car. This makes processing video and obstacle detection difficult. Better would be slow, higher torque motors running around 125RPM or so.

- Ultrasonic sensor is fixed facing front. It would be nicer to have a servo to pan left and right.

- Camera tilt servo is way too sensitive - small adjustments jerk it back and forth 
