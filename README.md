# irobot_create
Package to connect iRobot Create 1 with ROS. Control the robot, publish the odometry and sensors feedback.
Modification http://wiki.ros.org/irobot_create_2_1 to ROS indigo

## Install
- Clone the package folder

		$ cd ~/catkin_ws/src
		$ git clone https://github.com/LCAD-UFES/p3dx_navigation.git
		$ cd ..
		$ catkin_make

# Run
1. Connect the pioneer in USB port

2. Open 3 terminal

		$ sudo chmod 777 /dev/ttyUSB0
		$ roscore
		$ rosrun irobot_create driver.py


