vision_opencv
=============

.. image:: https://travis-ci.org/ros-perception/vision_opencv.svg?branch=indigo
    :target: https://travis-ci.org/ros-perception/vision_opencv

Packages for interfacing ROS with OpenCV, a library of programming functions for real time computer vision.


todo:
used with 
```
https://github.com/dusty-nv/jetson-containers
```

And to use cv_bridge do

```
apt-get update
apt-get install -y libopencv-dev python3-opencv

git clone -b noetic https://github.com/ros-perception/vision_opencv.git 

src/vision_opencv/cv_bridge/CMakeLists.txt -> linje 11 fra python3 til python3

catkin_make
```

todo: incorporate this repo instead
