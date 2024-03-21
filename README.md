# 271201-Project-Final
# Oran-Bot
this project use ros2 distro is humble.
# Getting started
1.Clone the repo:
```
git clone https://github.com/godmuay/271201-Project-Final.git
```
2.Navigate to your workspace:
```
cd ~/my_project_ws
```
5.Compile
```
colcon build
```
# Operating Instructions
After you build, remember to source the proper install folder...
```
source ~/my_project_ws/install/local_setup.bash
```
And then run the launch file...
```
ros2 launch articubot_one launch_sim.launch.py
```
After that run the this file to control robot
```
ros2 run articubot_one controller.py
