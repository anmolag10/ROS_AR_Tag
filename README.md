# ROS_AR_Tag
AR TAG Detection using ROS and Gazebo

# Requirements:

ROS (melodic)

Rviz

Gazebo

ar_track_alvar pkg
```bash 
sudo apt-get install ros-melodic-ar-track-alvar
```

# How To Run:

Clone Repository and run following commands:

```bash
git clone https://github.com/Blebot0/ROS_AR_Tag.git

catkin_make

source devel/setup.bash

roslaunch gazebo_bot world.launch
```

# Pose Of AR TAG

Run ar_pose.py

PATH: ar_tag/src/gazebo_bot/scripts

```bash 

cd ~/ar_tag/src/gazebo_bot/scripts

chmod +x ar_pose.py

python3 ar_pose.py
```

Open New Terminal and Run:

```bash 
rviz
```





