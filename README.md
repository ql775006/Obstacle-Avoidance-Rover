# Obstacle-Avoidance-Rover

## Brief Overview
4WD robot made with a plywood chassis that uses a ToF sensor mounted on a servo that can turn left, right, or 180 using differential drive

## Finished Project

![finishedproject](media/GIF/Fin-.gif)


## Project Goals
- Design a 4WD robot that performs basic obstacle avoidance
- Use a ToF sensor to judge distance mounted on a servo to perform basic "scanning"
- Design the chassis out of stiff ploywood instead of flimsy cardboard
- Learn how to measure and fabricate by hand before CAD and 3D printing

## Mechanical Components
- 3mm plywood sheets
- General SuperGlue
- Motor screw mounts
- 3mm steel rods
- M3 screws
- Wooden dowels
- Mounting tape

## Electronics
- Arduino Nano
- DRV8833 Driver module
- Buck Converter
- 7.4 LiPo 2s 35C

## Software
- Arduino IDE

## How Does It Work?
Robot constantly takes readings from the ToF sensor to detect whether there is an obstacle in front of it (a set threshold). The robot comes to a halt and scans, starting from the left, and will turn if it has found a path. If there is no path, the robot will reverse and do a 180.

## Timeline/Milestones

1. Designed first cardboard prototype
   > - Good for gauging rough dimensions
   > - Was difficult to maintain consistent contact between the wheels and floor
   > - Cardboard was too flimsy, offset was noticeable
   > - A lot of hot glue 
   > - As a result, the car could not go straight or turn properly

   ![proto1](media/pictures/proto1_medium.jpeg)  ![proto1](media/GIF/proto1test.gif)

----------------------------------

2. Prototype #2 (plywood chassis)
   > - First prototype to feature a plywood chassis carved from 3mm plywood sheets
   > - Less hot glue and used super glue for less of a mess and stronger bonding
   > - Added plywood supports at the bottom for more precise mounting
   > - Better alignment but there was still a tiny offset
   > - More consistent in going straight but struggled turning
   > - Was rather wide and bulky

   ![proto2](media/pictures/proto2_medium.jpeg). ![proto2](media/GIF/proto2test.gif)

----------------------------------

3. Prototype #3
   
   
  
  
