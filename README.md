This repository contains the package for an autonomous controller that allows a turtlebot to explore a maze. This controller can be used in a webots simulation by running the following commands:

cd \ros2ws

source /opt/ros/humble/setup.bash
export WEBOTS_HOME=/mnt/c/Program\ Files/Webots

Clone the repository to your system using the command:
git clone

colcon build --packages-select auto_search
source install/setup.bash

Launch the simulation on webots using:
ros2 launch auto_search launch.py


On a separate terminal run the following commands:

cd \ros2ws
source /opt/ros/humble/setup.bash
source install/setup.bash
ros2 run auto_search controller





