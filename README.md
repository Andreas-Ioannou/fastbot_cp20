Fastbot_Setup
This package contains the necessary launch and configuration files to bring up the FastBot robot in a ROS 2 environment.

📦 How to Download and Use This Package
Follow these steps to clone the repository and use the fastbot_bringup package in your ROS 2 workspace:

1. Clone the Repository
cd ~/ros2_ws/src git clone https://github.com/Andreas-Ioannou/fastbot_cp20.git

2. Build the Workspace
cd ~/ros2_ws colcon build

3. Source the Setup File
source install/setup.bash

4. Launch FastBot
ros2 launch fastbot_bringup bringup.launch.py
