
rosdep install --from-paths src --ignore-src -r -y --rosdistro humble

source ~/dexi_ws/install/setup.bash

ros2 launch dexi_robot_description display.launch.py
