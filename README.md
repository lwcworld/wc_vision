# installed development environment
- cv_camera (http://wiki.ros.org/cv_camera)
- ORB_SLAM2 from ETHZ (https://github.com/ethz-asl/orb_slam_2_ros)
- darknet_ros (YOLO V3 - ROS ver) (https://github.com/leggedrobotics/darknet_ros)

## how to execute?
<pre><code> roslaunch wc_vision wc_vision.launch </code></pre>

## dealing errors
#### 1. /ORB_SLAM2/src/System.cc:134:28: error: ‘usleep’ was not declared in this scope usleep(1000);
- https://github.com/raulmur/ORB_SLAM2/issues/317
- https://github.com/raulmur/ORB_SLAM2/pull/144
#### 2. 
