# AutoMine-Nav Dataset

A multimodal dataset for autonomous driving and robot navigation in mining environments.

## 📌 Dataset Overview

AutoMine-Nav is a comprehensive dataset collected from open-pit mining areas, designed for autonomous vehicle localization and navigation tasks. The dataset includes synchronized data from multiple sensors:

- Ouster OS1-64 LiDAR
- Stereo Cameras (Left & Right)
- GNSS/INS System
- IMU

## 📁 Data Structure

### Extrinsic Parameters
All sensor-to-sensor transformations are provided in the `docs/date_vehicle_type/` folder, including param.json and ROS_Left_Right.txt:
param.json
- LiDAR-to-Camera (Left & Right)
- IMU-to-LiDAR
- GPS-to-IMU
ROS_Left_Right.txt
- Stereo camera baseline

**Coordinate Convention**: ROS (Right-handed, X-forward, Y-left, Z-up)

## 📥 Download

The dataset is available via Baidu Cloud:
[Download Link](https://pan.baidu.com/s/1vrKBsuKGj-v3_toB8TGDAw?pwd=7tju)  
Extraction Code: `7tju`

@article{Li2024AutoMine,
  title={AutoMine: A Multimodal Dataset for Robot Navigation in Open-pit Mines},
  author={Li, Yuchen and Teng, Siyu and Wang, Junhui and Ai, Yunfeng and Tian, Bin and 
          Xuanyuan, Zhe and Bing, Zhenshan and Knoll, Alois and Wang, Fei-Yue and Chen, Long},
  journal={Journal of Field Robotics},
  year={2024}
}
