# Robot arm simulation in ROS2 humble and MoveIt
## Install requirements:
Check System Requirements:
Ensure that your system meets the requirements for ROS2 installation. (Ubuntu 22.04 or above).
### 1. Installing ROS2:
Follow the official ROS2 installation guide to set up the sources on your system
[ROS humble installation](https://docs.ros.org/en/humble/Installation.html)
This involves adding the ROS 2 apt repository to your sources list.
### 2. Installing MoveIt:
First, install the binary version of MoveIt, Please refer to the official website [MoveIt installation](https://moveit.ros.org/install-moveit2/binary/)
```
sudo apt-get update
sudo apt install ros-humble-moveit
```
Then, Follow the official MoveIt installation guide to set up the sources on your system [MoveIt getting started](https://moveit.picknik.ai/humble/doc/tutorials/getting_started/getting_started.html)

### 3. Run the Rviz simulation environment
```
sudo apt-get update
source ~/ws_moveit2/install/setup.bash
ros2 launch moveit2_tutorials demo.launch.py rviz_config:=panda_moveit_config_demo_empty.rviz

```


