# AutoMine-Nav Dataset

A multimodal dataset for autonomous driving and robot navigation in mining environments.

## 📌 Dataset Overview

AutoMine-Nav is a comprehensive dataset collected from open-pit mining areas, designed for autonomous vehicle localization and navigation tasks. The collection platforms include one SUV, one wide-body truck and one mining truck. The SUV data includes synchronized data from multiple sensors:

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

The dataset is available via Baidu Cloud.
For SUV, four individual data flows are released. And each one is divided into 1K, 2K, and 3K frames.
SUV_01 1K data can be download via:
[Download Link](https://pan.baidu.com/s/1vrKBsuKGj-v3_toB8TGDAw?pwd=7tju)  
Extraction Code: `7tju`

SUV_01 2K data can be download via:
[Download Link](https://pan.baidu.com/s/1rvg8PIkjIiYyySfe0dGbKw?pwd=sk2y)  
Extraction Code: `sk2y`

We will upload all the data soon!

@article{Li2024AutoMine,
  title={AutoMine: A Multimodal Dataset for Robot Navigation in Open-pit Mines},
  author={Li, Yuchen and Teng, Siyu and Wang, Junhui and Ai, Yunfeng and Tian, Bin and 
          Xuanyuan, Zhe and Bing, Zhenshan and Knoll, Alois and Wang, Fei-Yue and Chen, Long},
  journal={Journal of Field Robotics},
  year={2024}
}
