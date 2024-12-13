# auto_search

This repository contains the package for an autonomous controller that allows a turtlebot to explore a maze. This controller can be used in a webots simulation by running the following commands:<br />
cd ros2_ws/<br />
source /opt/ros/humble/setup.bash<br />
export WEBOTS_HOME=/mnt/c/Program\ Files/Webots <br />
<br />
Clone the repository to your system using the command:<br />
git clone<br />
<br />
colcon build --packages-select auto_search<br />
source install/setup.bash<br />
<br />
Launch the simulation on webots using:<br />
ros2 launch auto_search launch.py<br />
<br />
On a separate terminal run the following commands:<br />
cd \ros2ws<br />
source /opt/ros/humble/setup.bash<br />
source install/setup.bash<br />
ros2 run auto_search controller<br />
