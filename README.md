# orb_slam3_ros_noetic

sudo apt install ros-noetic-cv-bridge
sudo apt install ros-noetic-image-transport
sudo apt install ros-noetic-camera-info-manager
sudo apt install ros-noetic-codec-image-transport

Pangolin: 
cd 
git clone -b v0.8 --recursive https://github.com/stevenlovegrove/Pangolin.git
cd Pangolin
./scripts/install_prerequisites.sh recommended
cmake -B build
cmake --build build 

Eigen3:
cd 
git clone -b 3.4.0 https://gitlab.com/libeigen/eigen.git
cd eigen
mkdir build
cd build
cmake ..
sudo make install
sudo ldconfig

OpenCv:
python3
import cv2
cv2.__version__
exit()

ORB-SLAM3:
git clone https://github.com/UZ-SLAMLab/ORB_SLAM3.git ORB_SLAM3
etc(continuar ...)
