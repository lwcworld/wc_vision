# installed development environment
- cv_camera (http://wiki.ros.org/cv_camera)
- ORB_SLAM2 from ETHZ (https://github.com/ethz-asl/orb_slam_2_ros)

## how to execute?
<pre><code> roslaunch wc_vision wc_vision.launch </code></pre>


The stable PX4 version is v.1.8.0 : 
<pre><code>git clone --branch DQRC12B https://github.com/PX4/Firmware.git </code></pre>
for multiple quadrotor simulation, 
<pre><code>roslaunch px4 multi_uav_mavros_sitl.launch </code></pre>
if there is error using multiple quadrotors,
- open the single_vehcile_spawn.launch launch file
- Replace this line
