# CognitiveRobotics
##Installing a drone work environment
only with ros-noetic os-ubuntu-20.04
run the following comments:

git clone --recursive https://github.com/appie-17/tello_driver.git
sudo apt-get install ros-hydro-camera-info-manager-py
git clone https://github.com/ros-perception/camera_info_manager_py.git
sudo apt install ros-noetic-codec-image-transport
sudo apt install ros-neotic-tello-driver
pip install pyyaml
on the file tello_driver_node change the first line to: #!/usr/bin/env python3
