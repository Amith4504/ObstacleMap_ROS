# Dense 3D reconstruction using Stereo cameras
This project involves dense 3D recontruction of scene using stereo pair along with point cloud segmentation and clustering to classify potential obstacles for GPS denied navigation. 
Tested on Jetson Nano with two CSI lanes for stereo cameras.

1. A Disparity map is created using Stereo SGBM algorithm . 
2. 3D reconstruction using camera intrinsics and extrinsics. 
3. Point cloud representation using KD Tree [PCL library].
4. Point Cloud segmentation and clustering.


# Building

 'sh generate.sh'

# Run

 'sh run.sh'

