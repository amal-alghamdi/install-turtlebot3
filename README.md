#### Install-turtlebot3 on ros noetic

### Turtlebot3 is programmable robot using the ros OS.

## Open a terminal copy the following steps:

---

gedit ~/.bashrc

export TURTLEBOT3_MODEL=burger

---

# Save and close.

---

source ~/.bashrc

cd ~/catkin_ws/src/

git clone https://github.com/ROBOTIS-GIT/turtlebot3_simulations.git

cd ~/catkin_ws && catkin_make
 
 --- 
 
 # A problem may occur :
 
 ---
 
 ![make](https://user-images.githubusercontent.com/66622418/88215354-310db800-cc64-11ea-8ab4-544f5fef7286.jpg)


---
 
 
