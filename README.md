# ROS-WEEK4-T1
Launch TurtleBot navigation 
The task is lunch a turtleBot 
U need UBUNTU 20.04 ROS 1 Installing turtlesim package
1.	Write su and enter the password 
2.	Then enter 
sudo apt update 
sudo apt install ros-noetic-turtlesim
in the terminal 
3.	Then enter 
roscore
rosrun turtlesim turtlesim_node
if it didn’t work try writing and there massage says "The following packages have unmet dependencies:
 rosbash : Depends: catkin but it is not going to be installed
E: Unable to correct problems, you have held broken packages."
Write < apt install ros-noetic-catkin>
 https://1drv.ms/i/s!AlN58SaXWz6Wg5RIDovaRVxioGA8_Q?e=REfjto

4.	Enter the command 
roscore
rosrun turtlesim turtlesim_node
 https://1drv.ms/i/s!AlN58SaXWz6Wg5RJ7yV2TPSsNuU0Mw?e=F1gYYq

 
5.	Write the rosrun turtlesim draw_square comman in new terminal
https://1drv.ms/i/s!AlN58SaXWz6Wg5RKx_yolOsBwP1cNw?e=SSfVdb

https://1drv.ms/i/s!AlN58SaXWz6Wg5RLUCs3cDTdZQ7ceA?e=zzj9pI

 
6.	Write the rostopic echo /turtle1/pose command in the new terminal to see the change in position
 https://1drv.ms/i/s!AlN58SaXWz6Wg5RMhspdpt9n_nCUOw?e=gx3H7U


