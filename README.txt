=======================================================
Pullally Dataset
https://github.com/RAL-UC/Pullally_Dataset

Copyright 2024 (c) Robotics and Automation Laboratory
=======================================================

Description:

This respository contains the lidar scans and GNSS position
measurements of two field campaings at the Pullally experimental
fruit orchard located in central Chile.  Data was captured in 
summer and winter of the Southern hemisphere on the following
dates:

- February 15, 2023 (summer)
- August 20, 2023 (winter)

Data is stored in ROS bags (https://wiki.ros.org/Bags).

Assuming you have ROS installed, to visualize the data 
run the folling commands:
 >rosbag play filename


Sensors include:

Lidar: Velodyne VLP-16 (https://ouster.com/products/hardware/vlp-16)
GNSS: ArduSimple RTK3B Pro (https://www.ardusimple.com/product/simplertk3b-x5/)

Acquistion mobile platform consisted of a Unitree Go1 robot:
https://www.unitree.com/go1

