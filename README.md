# Dense 3D reconstruction using Stereo cameras
This project involves dense 3D recontruction of scene using stereo pair along with point cloud segmentation and clustering to classify potential obstacles for GPS denied navigation. 
Tested on Jetson Nano with two CSI lanes for stereo cameras.

1. A Disparity map is created using Stereo SGBM algorithm [ Rectification followed by Stereo matching ] . 
2. 3D reconstruction using camera intrinsics and extrinsics. 
3. Point cloud representation using KD Tree [PCL library].
4. Point Cloud segmentation and clustering.


# Building

 'sh generate.sh'

# Run

 'sh run.sh'
 
 # Disparity Map
 ![Screenshot from 2021-11-26 22-59-26](https://user-images.githubusercontent.com/21309793/143617177-e5a7da21-9ebf-4915-adeb-9dcfb64e7a83.png)

# Point Cloud
 

![Screenshot from 2021-11-26 23-25-18](https://user-images.githubusercontent.com/21309793/143617687-93891331-ddfe-4518-b993-c3187f923e7b.png)
![Screenshot from 2021-11-26 23-29-03](https://user-images.githubusercontent.com/21309793/143617690-940f22a6-9e5c-462b-bbbe-54267cdc80cc.png)
