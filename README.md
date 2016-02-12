# irobot_create
Package to connect iRobot Create 1 with ROS. Control the robot, publish the odometry and sensors feedback.
Modification http://wiki.ros.org/irobot_create_2_1 to ROS indigo

## Install
- Clone the package folder

		$ cd ~/catkin_ws/src
		$ git clone https://github.com/LCAD-UFES/p3dx_navigation.git
		$ cd ..
		$ catkin_make

# Run with Joystick
1. Connect the Create robot in USB port and joystick

2. Open 4 terminal

		$ sudo chmod 777 /dev/ttyUSB0
		$ sudo chmod 777 /dev/input/js0		
		$ roscore
		$ rosrun irobot_create driver.py
		$ rosrun joy joy_node
		$ rosrun irobot_create irobotJoyTeleop.py

If a problem occurs, check the ports


