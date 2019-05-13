# calibration_camera_lidar
从autoware分离出来的相机雷达联合标定ros包

metapackage

下到自己的工作空间中，catkin_make

然后source devel/setup.bash

新开一个终端执行roscore

当前终端执行rosrun calibration_camera_lidar calibration_toolkit

要装nlopt，上github上搜索nlopt，按照下面说的步骤装上就能用了。
