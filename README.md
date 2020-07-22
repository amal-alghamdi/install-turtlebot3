# Install-turtlebot3 on ros noetic

## Turtlebot3 is programmable robot using the ros OS.

### Open a terminal copy the following steps:

---

gedit ~/.bashrc

export TURTLEBOT3_MODEL=burger

---

### Save and close.

---

source ~/.bashrc

cd ~/catkin_ws/src/

git clone https://github.com/ROBOTIS-GIT/turtlebot3_simulations.git

cd ~/catkin_ws && catkin_make

roslaunch turtlebot3_fake turtlebot3_fake.launch

roslaunch turtlebot3_teleop turtlebot3_teleop_key.launch

 --- 
 
 ### A problem may occur when (cd ~/catkin_ws && catkin_make):
 
 ---
 
 ![make](https://user-images.githubusercontent.com/66622418/88215354-310db800-cc64-11ea-8ab4-544f5fef7286.jpg)

--


### Solution
#### 1- open files delete ros catkin_ws , catkin_ws and workspace.
#### 2- open terminal and write 
---

gedit ~/.bashrc

---

### 3- then delete 

---

source ~/catkin_ws/devel/setup.bash

export TURTLEBOT3_MODEL=burger

---
### 4-[ create workspace ](http://wiki.ros.org/catkin/Tutorials/create_a_workspace) after finish go back repeat the previous steps

## to more details
* [here](https://automaticaddison.com/how-to-launch-the-turtlebot3-simulation-with-ros/#gazebo)

