ros2_test
*********

気持ち
-----
* シミュレーション周りがしっかりしているなら、ros/ros2を使いたい。
* 他のモチベーションとしては、可視化ツールrvitzの使い勝手が良さそうなところ、マルチスレッド（プロセス?）の設計をスムーズにできそうなところ。
* ros_controlは素晴らしいけど、その内に動かなくなるのは分かっているから、ros2でやる。
* ros2_controlは期待できない。ただ、力をそのまま伝達できさえすればいいので、代替品はそんなに難しくないと思う。
* プロセス間で通信される量が何なのかを、いまいち分かっていない。

メモ
----
.. code:: shell

    git clone https://github.com/numahha/ros2_test.git

リンクメモ
---------

* `ROS 2の基本 <https://gbiggs.github.io/rosjp_ros2_intro/ros2_basics.html>`_



Tutorials memo (RViz)
---------------------
Terminal 1
.. code:: shell

    ros2 launch dummy_robot_bringup dummy_robot_bringup.launch.py

Terminal 2
.. code:: shell

    rviz2

In RViz

* Fixed Frame: "map" -> "world"
* Add "TF"

`Ref <https://index.ros.org//doc/ros2/Tutorials/dummy-robot-demo//>`_


インストール
-----------
* `公式インストール <https://index.ros.org/doc/ros2/Installation/Linux-Development-Setup/>`_
* colcon sudo apt install python3-colcon-common-extensions
* `Gazebo-ros_pkgs (ROS2) <http://gazebosim.org/tutorials?tut=ros2_installing&cat=connect_ros>`_
* rqt install sudo apt install ros-$ROS_DISTRO-rqt*
