 Wheeled Obstacle Avoider Robot

The Wheeled Obstacle Avoider Robot is an autonomous robot designed to detect and avoid obstacles in its path. It is powered by an Arduino microcontroller and utilizes ultrasonic sensors for obstacle detection. The robot uses a combination of motors, sensors, and a motor driver to autonomously navigate its environment.

 Overview

The obstacle-avoiding robot is equipped with an Arduino Uno, ultrasonic sensors, and a set of motors controlled by the L298N motor driver. The robot is designed to automatically sense and avoid obstacles using real-time feedback from the sensors, ensuring smooth and efficient navigation.

 Features

- Autonomous Navigation: The robot automatically navigates and avoids obstacles without human intervention.
- Obstacle Detection: Ultrasonic sensors continuously measure the distance to obstacles in the path.
- Efficient Power Usage: Powered by 18650 Li-ion batteries, providing long operational time.
- Simple and Easy to Build: The project uses basic components, making it a great choice for learning about robotics and sensors.

 Components Used

- Arduino Uno: The main controller that processes sensor data and drives the motors.
- L298N Motor Driver: Controls the motors for movement in various directions.
- Wheels (4x): Provides movement and support for the robot.
- TT Gear Motors (4x): Drives the wheels, enabling motion.
- Servo Motor: Controls the steering of the robot.
- Ultrasonic Sensor: Detects obstacles in the robot's path.
- 18650 Li-ion Batteries (2x): Provides power for the robot's operation.
- 18650 Battery Holder: Holds the Li-ion batteries securely.
- Male and Female Jumper Wires: For connecting various components.
- Acrylic Car Floor: The base platform for assembling the components.
- DC Power Switch: Used to power the robot on and off.

 Working Principle

1. Obstacle Detection: The ultrasonic sensor emits sound waves to measure the distance to nearby obstacles. If an obstacle is detected within a predefined range, the robot will alter its path to avoid a collision.
   
2. Motor Control: The Arduino processes the sensor data and sends appropriate commands to the L298N motor driver, which controls the motors to move the robot forward, stop, or turn as needed.

3. Steering: The servo motor controls the robot's steering mechanism, helping it navigate around obstacles by turning in the direction needed.

4. Power Supply: The robot is powered by two 18650 Li-ion batteries, ensuring sufficient power for all components. The DC power switch allows for easy on/off control.

 Assembly Instructions

 1. Hardware Setup

- Mount the Arduino Uno on the acrylic car floor.
- Connect the L298N Motor Driver to the Arduino and wire it to the motors.
- Attach the TT Gear Motors to the wheels.
- Position the Ultrasonic Sensor at the front of the robot.
- Fix the Servo Motor to control steering.
- Secure the 18650 Li-ion Batteries in the battery holder.
- Connect the power switch to control the robot's power.

 2. Wiring Overview

- Connect the Arduino Uno to the motor driver, ultrasonic sensor, and servo motor.
- Attach the motors to the L298N Motor Driver, ensuring the correct polarity.
- Wire the ultrasonic sensor to the designated Arduino pins for trigger and echo.
- Use jumper wires to make all necessary connections between the components.

 3. Powering the Robot

- Ensure that the 18650 Li-ion batteries are securely placed in the battery holder and connected to the power supply lines.
- Use the DC power switch to turn the robot on or off.

 Testing and Calibration

Once the robot is assembled, test it by powering it on. The robot should begin moving forward and avoid obstacles automatically. If necessary, adjust the positioning of the ultrasonic sensor for more accurate detection or calibrate the motor speeds for smoother movement.

 Troubleshooting

- Motors not working: Check the motor connections and ensure that the motor driver is correctly wired.
- Sensor not detecting obstacles: Ensure the ultrasonic sensor is positioned correctly and not obstructed.
- Robot not turning: Check the servo motor connections and ensure it is properly controlled by the Arduino.

 Conclusion

This Wheeled Obstacle Avoider Robot is a great project for learning the basics of robotics, including motor control, sensor integration, and autonomous navigation. It's an ideal project for beginners looking to explore mobile robotics and can be further expanded with more advanced features such as remote control or additional sensors.


 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.E](LICENSE) file for details.
