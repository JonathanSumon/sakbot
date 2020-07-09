# Sakbot
An Autonomous Indoor Bot with a circular base which uses 2 Arduino Uno for Getting the Encoder Data and to get values from an MPU 9250 and using a Raspberry Pi as the brain. 

The bot can Teleop, Map the environment and autonomously Traverse with the help of a Lidar using the ROS Navigation Stack. Localization is done using both AMCL (After Mapping) and robot_localization package fusing the odometry from the wheels and the IMU.


Lidar: Rplidar A1 (Indoor Mapping)
Motor Driver: Cytron Mdd10
Motors: Rhino 60 RPM DC Encoder Servos
IMU : MPU 6050
