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
 
4.	Enter the command 
roscore
rosrun turtlesim turtlesim_node
 
5.	Write the rosrun turtlesim draw_square comman in new terminal
  

 
6.	Write the rostopic echo /turtle1/pose command in the new terminal to see the change in position
 

