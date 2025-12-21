# Pullally_Dataset

## Introduction
This repository documents a lidar dataset acquired in Valparaíso Region, Chile, for localization, mapping, and crop monitoring tasks in agricultural robotics. The data were collected in August 2023 (austral winter) using a quadruped mobile robot operating in an agricultural environment. The key features are: 
- Lidar and GNSS-RTK measurements
- Three repeated runs of the same trajectory through tree fields
- Multiple tree species at different growth stages
- Distinct planting patterns and varying daylight conditions
- Approximately 3 hours of operation, with total distance covered of 450 m, and 75 GB of data.

The raw LiDAR data are hosted in the cloud, while this repository provides the associated documentation and example usage.

## Dataset Description

This dataset comprises raw terrestrial lidar 3D point clouds representing tree structures and surrounding forest vegetation. The data are intended to support research and development in areas such as environmental perception, vegetation analysis, and robotic mapping, as well as educational use.

### Geographic Coverage 

A satellite image of the orchard section employed for the acquisition campaign showing the robot’s reference path marked in red is presented in Fig.

- **Location:** Chile, Valparaiso region, Pullally
- **Coverage area:** ~ 6.5 km²
- **Bounding box (WGS84):**
  - Up_point:     32°26'38"S 71°20'18"W
  - Down_point:   32°26'40"S 71°20'18"W
  - Up_point_1:   32°26'37"S 71°20'21"W
  - Down_point_1: 32°26'39"S 71°20'23"W


### Sensor and Acquisition
This dataset was collected by the authors using a Unitree Go1 quadruped robot. The robot was equipped with a Velodyne VLP-16 lidar, and an ArduSimple RTK3BPro GNSS-RTK system paired with a calibrated Survey GNSS Tripleband+L-band antenna. Ground-truth positions were recorded at 1~$Hz$ with sub-centimeter accuracy using a stationary RTK base station.

- **Platform:** Unitree Go1 quadruped robot [link text](https://shop.unitree.com/products/unitreeyushutechnologydog-artificial-intelligence-companion-bionic-companion-intelligent-robot-go1-quadruped-robot-dog?variant=42363559674089)
- **Sensor:** Velodyne VLP-16 lidar [link text]([https://example.com](https://ouster.com/products/hardware/vlp-16))
              ArduSimple RTK3BPro GNSS-RTK [link text](https://www.ardusimple.com/user-guide-simplertk3b-pro/)
- **Acquisition date(s):** 2023-08-06


### File Formats and Sizes
- **Format:** .bag (rosbags)
- **Total dataset size:** ~ 75 GB
- **Example file:** `2023-08-06-12-18-23_25.bag`


## Data Access
The full dataset is hosted externally:

- **Cloud storage:** One drive
- **Download link:** [link text](https://uccl0-my.sharepoint.com/:f:/r/personal/mtorreto_uc_cl/Documents/Datasets/Pullally_Dataset?csf=1&web=1&e=dwRVnG)
