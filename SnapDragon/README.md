## AIMET

AIMET is an open-source library for optimizing trained neural network models. It does this by providing advanced model compression and quantization techniques to shrink models while maintaining task accuracy. Smaller models translate into improved run-time performance and lower latency as well lower compute, memory, and power consumption.

Developers can incorporate AIMET’s advanced model compression and quantization algorithms into their PyTorch and TensorFlow model-building pipelines for automated post-training optimization, as well as for model fine-tuning. Automating these algorithms helps eliminate the need for hand-optimizing neural networks that can be time-consuming, error-prone, and difficult to repeat. And as part of our Qualcomm AI Stack, you can combine multiple software capabilities in your development.

Qualcomm Innovation Center (QuIC) open sourced AIMET on GitHub to collaborate with other leading AI researchers and to provide a simple library plugin for AI developers to utilize for state-of-the-art model efficiency performance. The cutting-edge compression and quantization techniques are based on innovative research from Qualcomm AI Research.
https://developer.qualcomm.com/software/ai-model-efficiency-toolkit
<br>
https://github.com/quic/aimet
<br>
https://github.com/quic/aimet-model-zoo

## Machine Vision SDK

The machine vision (MV) SDK is a C programming API comprised of a binary library and some header files. It is targeted towards robotics developers looking to utilize the full capabilities of Snapdragon® platforms for autonomous robotic systems. The MV SDK is engineered to supply the cutting edge computer vision algorithms to provide localization, feature recognition and obstacle detection for Snapdragon platforms. 
https://developer.qualcomm.com/software/machine-vision-sdk
<br>
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

## Snapdragon Ride SDK

The era of the intelligently connected, autonomous driving car is upon us. The Snapdragon Ride Software Developer Kit (SDK) assists automotive suppliers and automakers to deploy virtually all the autonomous driving features they want now — with the ability to scale in the future. Our full suite of automotive products was developed with more than 30 years of mobile leadership and 20 years of automotive experience. The Snapdragon Ride Platform and SDK are supporting automakers to build cars that are connected to networks, the cloud, other cars, pedestrians, traffic, and infrastructure systems.
The Snapdragon Ride Platform is at the forefront of this intelligent and connected automotive transformation, gaining momentum with global automakers and Tier 1 suppliers worldwide. Collaborations include OEMs like BMW and Cadillac — luxury automotive companies poised to lead the intelligently connected automotive revolution.

The expanded product roadmap for Snapdragon Ride makes it a truly advanced solution — a scalable, fully customizable ADAS platform — ready to transform the automotive industry. And now, the Snapdragon Ride SDK helps automotive OEMs and developers build safety-certified applications for perception and drive policy on top of the Snapdragon Ride Platform.

Snapdragon Ride allows for rapid creation of customizable and ASIL-compliant ADAS solutions across the entire product line from entry level (L1) to premium (L3) with direct support from Qualcomm Technologies.
https://developer.qualcomm.com/software/digital-chassis/snapdragon-ride
