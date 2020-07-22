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
 
 
