# GLIC-Calib
## GLIC-Calib: Targetless and One-Shot Spatial-Temporal Calibration of LiDAR-IMU-Camera for Ground Vehicles

## 1. Abstract
Accurate spatial-temporal parameters of LiDAR, IMU and camera, including extrinsic parameter and time offset, is the key to ensure multi-sensor fusion performance for ground vehicles. Compared with target-based calibration method, targetless method does not need artificial targets which is more convenient and flexible. Most existing targetless calibration methods cannot apply to ground vehicles with the LiDAR-IMU-camera combination system. To address this issue, in this paper we propose GLIC-Calib: a carefully designed targetless and one-shot spatial-temporal calibration method of LiDAR-IMU-camera for ground vehicles. First, we recover the real-time camera scale by constant camera height and visual ground points. Then we initialize 6-DoF extrinsic of LiDAR-IMU and camera-IMU as well as their time offsets by raw motion measurements and ground constraints. Finally we refine spatial-temporal parameters of LiDAR-IMU and camera-IMU by high accurate LiDAR-camera extrinsic parameter obtained from environmental association. Experiments conducted on the self-collected datasets with different sensor configurations show the effectiveness, efficiency and robustness of the proposed methods compared with others. We open-sourced our methods on GitHub for the contribution to the community.

## 2. Related video
The presatation video is available on [**Bilibili**](https://www.bilibili.com/video/BV1W8sUzWEud/)

## Paper and code will be released soon!
