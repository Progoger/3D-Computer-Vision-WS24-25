# 3D-Computer-Vision-WS24-25

Dense 3D reconstruction

Project for lecture course on 3D Computer Vision in winter semester 2024-2025.

Input Data: 9 RGB images, 9 Depth images, Camera calibration parameters, Camera movement matrices, 7 Features.

Output Data: dense point cloud reconstruction saved in .ply format.

Main steps:
1) Setup and Cofiguration
2) Correcting Camera Distortion (using Inverse Sampling)
3) Camera Pose Estimation and 3D Reconstruction
4) Depth to Point Cloud Conversion
