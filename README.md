# GRIPPER BOT
## Robot Simulation with Gripper and GUI. 
<br>

<img src="https://img.shields.io/github/license/nilutpolkashyap/gripper_bot?style=for-the-badge">&nbsp;<img src ="https://img.shields.io/github/languages/code-size/nilutpolkashyap/gripper_bot?style=for-the-badge">

___________________________________________________________________________

# **Details About Project**

## Software Used
- Fusion360 -> For designing the 3D Model of the robot.
- [fusion2urdf](https://github.com/syuntoku14/fusion2urdf) -> Fusion360 script to export urdf from fusion 360 directly. 
- ROS (Robot Operating System) 
- Gazebo 
- Rviz 
- [QT Designer](https://doc.qt.io/qt-5/qtdesigner-manual.html) -> For GUI

Robot Drive Plugin Used - [Skid Steering Drive - Gazebo](http://gazebosim.org/tutorials?tut=ros_gzplugins#SkidSteeringDrive)

## Fusion360 Model
<div align="center">
<img  alt="Fusion360 Model" width="70%" src="images/gripper_bot_image.png" />
<br />
</div>

<!-- ## Final Rendered Fusion360 Model
<div align="center">
<img  alt="Final Rendered Fusion360 Model" width="70%" src="https://raw.githubusercontent.com/nilutpolkashyap/gripper_bot/main/images/gripper_bot.png" />
<br />
</div>

## Gazebo Simulation
<div align="center">
<img  alt="Gazebo Simulation" width="70%" src="https://raw.githubusercontent.com/nilutpolkashyap/gripper_bot/main/images/image1.JPG" />
<br />
</div> -->

<!-- ## GUI 
To control **Arm** and **Gripper** of robot. <br/>
**GUI** Designed using **QT Designer** software.
<div align="center">
<img  alt="GUI" width="50%" src="https://raw.githubusercontent.com/nilutpolkashyap/gripper_bot/main/images/robot_gui.JPG" />
<br />
</div> -->

## Clone this repository inside your ROS Workspace:
```
cd ~/catkin_ws/src/
git clone https://github.com/nilutpolkashyap/gripper_bot.git
cd ~/catkin_ws/
catkin_make
source devel/setup.bash
```

## Launch the simulation
Type the command in a terminal to launch the Gripper Bot world simulation:
```
roslaunch gripper_bot_description spawn.launch
```
<div align="center">
<img  alt="robot simulation" src="images/gripper_bot_simulation.JPG" /></div><br />

Type the command in another terminal to run the GUI:
```
cd ~/catkin_ws/src/gripper_bot/gripper_bot_description/src
python3 gui.py
```
<div align="center">
<img  alt="gui" src="images/gui.JPG" /></div>

## Output
<div align="center">
<img  alt="Gazabo Output" width="80%" src="https://raw.githubusercontent.com/nilutpolkashyap/gripper_bot/main/images/results1.JPG" />
<br />
</div>

## RQT Graph Output
<div align="center">
<img  alt="RQT Graph" width="100%" src="https://raw.githubusercontent.com/nilutpolkashyap/gripper_bot/main/images/rosgraph.png" />
<br />
</div>
