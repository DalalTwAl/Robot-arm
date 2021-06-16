# Robot-arm
Welcome to the Robot-arm wiki!

to upload the robot arm package you need a workspace since I'm using a website to do the task

the workspace is already there

FIRST we need to add the package to the workspace (Simulation)

$ cd~/simulation_ws/src 
$ sudo apt install git 
$ git clone https://github.com/smart-methods/arduino_robot_arm

After that we need to install all the dependencies, since I'm using melodic we'll install theses:

$ sudo apt-get install ros-melodic-moveit
$ sudo apt-get install ros-melodic-joint-state-publisher ros-melodic-joint-state-publisher-gui
$ sudo apt-get install ros-melodic-gazebo-ros-control joint-state-publisher 
$ sudo apt-get install ros-melodic-ros-controllers ros-melodic-ros-control

Then we will compile the package and open it

$ roslaunch robot_arm_pkg check_motors.launch
