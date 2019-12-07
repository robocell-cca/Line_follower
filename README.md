# Line follwer

The code is in .ino format which is to be run on microcontroller units like Arduino and NodeMCU, which follows a black line on white surface, or a white line on black background.

# Basic Functioning:
 1. If during the operation, the left IR sensor senses a black surface, and right sensor senses white, the  wheels are controlled in a manner using the motor driver, that the robot moves left till the left sensor detects white.
 
 2. If left IR senror detects white and right IR detects black, the robots moves right till the right IR detects white.
 
 3. If both IR detects white the robot moves forward.
 
 # Real world applications :
 1. As an industrial application, it can be used as automated equipment carriers replacing traditional conveyor belts.
 2. An automated car which follows embedded magets on road using a hall effect sensor.
