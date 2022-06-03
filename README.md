## about 

- kitti dataset publisher based on `ROS2`

## how to run 

- the package is built with ubuntu 20.04, ROS2 galactic 

- instruction is in `run.md` 
   - cannot build this in conda, will have errors like `libgdal.so: undefined reference to `TIFFReadRGBAStrip@LIBTIFF_4.0'`, need to build without any conda environment 

- to visualize output, run 
```
~/workspace/kitti_ws/src/ros2_kitti_publishers$ rviz2 -d default.rviz
```

## acknowledgement 

- the repo is mainly adapted from 
   - https://github.com/umtclskn/ros2_kitti_publishers
   - https://github.com/umtclskn/ros2_kitti_publishers/pull/1