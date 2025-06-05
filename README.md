# 3D Face Reconstruction From Stereo Images

This project focuses on 3D face reconstruction from stereo images under three calibration scenarios: fully calibrated, partially calibrated, and uncalibrated.

A calibrated 3D scene was set up in Blender with three cameras capturing the face from left, front, and right angles. The front camera remained fixed as a reference, while the side cameras varied in pose across four configurations to evaluate the effects of rotation and translation on reconstruction.

## Calibration Setups

The datasets were captured under four calibration setups, which are as follows:

- **Dataset 0**: Translation of ±0.1 m without rotation  
- **Dataset 5**: Rotation of ±5° combined with ±0.1 m translation  
- **Dataset 10**: Rotation of ±10° combined with ±0.2 m translation  
- **Dataset 20**: Rotation of ±20° combined with ±0.4 m translation  

Each dataset contains three images, three ground truth depth maps, and a JSON file with all camera parameters.

Four separate programs are provided for calibrated, uncalibrated, and partially calibrated (pose estimation) reconstruction, as well as depth map visualization.

Each program allows you to change the dataset and observe how camera pose affects the accuracy of 3D reconstruction.
