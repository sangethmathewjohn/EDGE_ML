## Machine Vision SDK

The machine vision (MV) SDK is a C programming API comprised of a binary library and some header files. It is targeted towards robotics developers looking to utilize the full capabilities of Snapdragon® platforms for autonomous robotic systems. The MV SDK is engineered to supply the cutting edge computer vision algorithms to provide localization, feature recognition and obstacle detection for Snapdragon platforms. 
https://developer.qualcomm.com/software/machine-vision-sdk
https://github.com/ATLFlight/ATLFlightDocs

#### The MV SDK is designed to support the following algorithms:

##### Visual-Inertial Simultaneous Localization and Mapping (VISLAM)
Uses an extended Kalman filter to fuse IMU and camera tracking data to provide a 6 degree of freedom pose estimate in real-world coordinates.
Provides a 3D point cloud based upon tracked feature points
Optionally accepts and fuses in GPS data

##### Depth From Stereo (DFS)
Uses 2 time-synchronized cameras to generate a per-pixel dense depth map

##### Downward Facing Tracker (DFT)
Provides an "optic-flow"-like tracking algorithm to generate a displacement in pixels on a camera pointed 90° downwards

##### Sequence Reader/Writer (SRW)
Read and write sequences of camera and IMU sensor data

##### Voxel Map (VM)
Combines the camera's current 6DOF position with a depth map to generate a volumetric representation of its perceived world in 3D
Performs collision checking

##### Camera Auto Calibration (CAC)
Use image and IMU data to estimate calibration parameters for the camera

##### Camera Parameter Adjustment (CPA)
Use current image data to recommend camera parameter changes

##### Stereo Auto-Calibration (SAC)
Uncalibrated image pairs of scene yield extrinsic calibration parameters

