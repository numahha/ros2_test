

gazebo /opt/ros/dashing/share/gazebo_plugins/worlds/gazebo_ros_joint_state_publisher_demo.world

Ref https://qiita.com/l1sum/items/78f1a904fff3d389d8be
Ref Error in REST request https://www.qoosky.io/techs/82838933fc

double_pendulum_with_baseとかは、~/.gazebo/modelsの中にある。

* sdf for gazeboとurdf for ros2を作って、同時に動作させる。
* gazebo_ros_diff_drive_demoが、ros2 topicから制御入力をgazeboに送るやつになっているので、これを勉強する。
* https://github.com/ros-simulation/gazebo_ros_pkgs/wiki/ROS-2-Migration:-Body-Wrench-and-Joint-Effort も勉強する．
