# Contents
- [Base Network](#base-network)
- [Datasets](#datasets-and-simulators)
- [Interest Point](#interest-point)
- [Local Descriptor](#local-descriptor)
- [Pose Estimation](#pose-estimation)
  - [Multi-Sensor](#multi-sensor)
- [Detection](#detection)
- [Registration](#registration)
- [Mapping System](#mapping-system)
  -[Semantic Mapping](#Semantic-Mapping)
- [Scence Flow](#scence-flow)

# Base Network
- CVPR2017, PointNet [paper](https://arxiv.org/pdf/1612.00593.pdf) [review](https://github.com/bin70/3D-Vision-Paper-Reading/issues/2) [pytorch](https://github.com/fxia22/pointnet.pytorch)
- NIPS2017, PointNet++ [paper](https://papers.nips.cc/paper/7095-pointnet-deep-hierarchical-feature-learning-on-point-sets-in-a-metric-space.pdf) [review](https://github.com/bin70/3D-Vision-Paper-Reading/issues/3) 
- CVPR2017, ECC [review](https://github.com/bin70/3D-Vision-Paper-Reading/issues/4) [code](https://github.com/mys007/ecc)

# Datasets and Simulators
* nuScenes : public large-scale dataset for autonomous driving [[dataset](https://www.nuscenes.org/overview)]
* A LiDAR Point Cloud Generator: from a Virtual World to Autonomous Driving [[pdf](https://arxiv.org/pdf/1804.00103.pdf)]
* Ford Campus Vision and Lidar Data Set [[pdf](http://robots.engin.umich.edu/uploads/SoftwareData/Ford/ijrr2011.pdf), [dataset](http://robots.engin.umich.edu/SoftwareData/Ford)]
* Oxford RobotCar dataset [dataset](https://robotcar-dataset.robots.ox.ac.uk/) 1 Year, 1000km: The Oxford RobotCar Dataset [pdf](https://robotcar-dataset.robots.ox.ac.uk/images/robotcar_ijrr.pdf)
* Udacity based simulator [[link](http://wangyangevan.weebly.com/lidar-simulation.html), [git](https://github.com/EvanWY/USelfDrivingSimulator)]
* Tutorial on Gazebo to simulate raycasting from Velodyne lidar [[link](http://gazebosim.org/tutorials?tut=guided_i1)]
* Udacity Driving Dataset [[link](https://github.com/udacity/self-driving-car/tree/master/datasets)]
* Virtual KITTI [[link](http://www.europe.naverlabs.com/Research/Computer-Vision/Proxy-Virtual-Worlds)]
* LiDAR-Video Driving Dataset: Learning Driving Policies Effectively [[pdf](http://openaccess.thecvf.com/content_cvpr_2018/papers/Chen_LiDAR-Video_Driving_Dataset_CVPR_2018_paper.pdf)]
* KAIST Complex Urban Data Set Dataset [[dataset](http://irap.kaist.ac.kr/dataset/download_1.html)]
* Semantic KITTI [[dataset](http://semantic-kitti.org/)]
* A*3D: An Autonomous Driving Dataset in Challeging Environments [[dataset](https://github.com/I2RDL2/ASTAR-3D)], [[video](https://www.youtube.com/watch?v=QtK0VIywrmM&feature=youtu.be)]

# Interest Point
- ICCV2019, UnsuperPoint: End-to-end Unsupervised Interest Point Detector and Descriptor [paper](https://arxiv.org/pdf/1907.04011.pdf) [review]()

# Local Descriptor
- DELIGHT: An efficient descriptor for global localisation using LiDAR intensities [review](http://blog.leanote.com/post/jinbin_tan@icloud.com/845884a33010)

# Pose Estimation
# Multi-Sensor
- Joint Ego-motion Estimation Using a Laser Scanner and a Monocular Camera Through Relative Orientation Estimation and 1-DoF ICP [paper](http://www.ipb.uni-bonn.de/wp-content/papercite-data/pdf/huang2018iros.pdf) [review](http://blog.leanote.com/post/jinbin_tan@icloud.com/Paper-Reading-Joint-Ego-motion-Estimation)
- Selective Sensor Fusion for Neural Visual-Inertial Odometry [paper](http://openaccess.thecvf.com/content_CVPR_2019/html/Chen_Selective_Sensor_Fusion_for_Neural_Visual-Inertial_Odometry_CVPR_2019_paper.html) [review](http://blog.leanote.com/post/jinbin_tan@icloud.com/%E5%9F%BA%E4%BA%8E%E6%B7%B1%E5%BA%A6%E5%AD%A6%E4%B9%A0%E7%9A%84%E5%8F%AF%E9%80%89%E6%8B%A9VIO)
- A General Optimization-based Framework for Global Pose Estimation with Multiple Sensors [paper]() [review](http://blog.leanote.com/post/jinbin_tan@icloud.com/dfb4fdf4e398) [code](https://github.com/HKUST-Aerial-Robotics/VINS-Fusion) 

# Detection
- CVPR2017, MV3D: Multi-View 3D Object Detection Network for Autonomous Driving [paper](https://arxiv.org/abs/1611.07759) [review](https://github.com/bin70/3D-Vision-Paper-Reading/issues/1) [tensorflow](https://github.com/leeyevi/MV3D_TF)

# Registration
## Loop Detection
- CVPR2017, BB+ICP: Efficient Global Point Cloud Alignment using Bayesian Nonparametric Mixtures [paper](http://openaccess.thecvf.com/content_cvpr_2017/papers/Straub_Efficient_Global_Point_CVPR_2017_paper.pdf) [code](https://github.com/jstraub/bbTrans)
- SegMatch Segment based place recognition in 3D point clouds [paper](https://www.researchgate.net/publication/318693876_SegMatch_Segment_based_place_recognition_in_3D_point_clouds) [review](http://blog.leanote.com/post/jinbin_tan@icloud.com/SegMatch) [code](https://github.com/ethz-asl/segmatch)


# Mapping System
- Design, Calibration, and Evaluation of a Backpack Indoor Mobile Mapping System [paper](https://www.mdpi.com/2072-4292/11/8/905/pdf-vor) [review](http://blog.leanote.com/post/jinbin_tan@icloud.com/2127337f63e5)
## Semantic Mapping
- Lidar Mapping Optimization Based on Lightweight Semantic Segmentation [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8723606) [review]()

# Scence Flow
