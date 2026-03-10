# linefollower_robot
A Line Follower Robot is an autonomous robot that follows a path marked by a black or white line using IR sensors. The sensors detect the line and send signals to a microcontroller like Arduino, which controls the DC motors through a motor driver to move forward or turn, keeping the robot on the path automatically.
# Aim
To design and build a Line Follower Robot that can automatically detect and follow a line path using IR sensors and an Arduino microcontroller.
# Components Required

Arduino Uno

IR Sensor Module (2 or more)

L298N Motor Driver Module

DC Motors (2)

Robot Chassis with Wheels

Caster Wheel

Battery (7.4V / 9V / 12V)

Jumper Wires

Breadboard (optional)
# Connections

# IR Sensors

VCC → 5V (Arduino)

GND → GND (Arduino)

OUT1 → Arduino Digital Pin 2

OUT2 → Arduino Digital Pin 3

# Motor Driver (L298N)

IN1 → Arduino Pin 8

IN2 → Arduino Pin 9

IN3 → Arduino Pin 10

IN4 → Arduino Pin 11

# Motors

Left Motor → OUT1 & OUT2 (Motor Driver)

Right Motor → OUT3 & OUT4 (Motor Driver)

# Power

Motor Driver VCC → Battery

Motor Driver GND → Arduino GND
# Procedure

Assemble the robot chassis and fix the DC motors and wheels.

Mount the IR sensors at the front of the robot facing the ground.

Connect the IR sensors to the Arduino pins.

Connect the motor driver module to the Arduino and DC motors.

Upload the line follower program to the Arduino using Arduino IDE.

Place the robot on a track with a black line on a white surface.

Power the system and observe the robot follow the line automatically.
