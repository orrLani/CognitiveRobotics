# CognitiveRobotics
##Installing a drone work environment
only with ros-noetic os-ubuntu-20.04
run the following comments:

git clone --recursive https://github.com/appie-17/tello_driver.git \n
sudo apt-get install ros-hydro-camera-info-manager-py \n
git clone https://github.com/ros-perception/camera_info_manager_py.git\n
sudo apt install ros-noetic-codec-image-transport\n
sudo apt install ros-neotic-tello-driver\n
pip install pyyaml\n
on the file tello_driver_node change the first line to: #!/usr/bin/env python3
