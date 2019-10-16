joint_state_publisher_test
**************************

Need to install joint_state_publisher (here, use https://github.com/rjshim/joint_state_publisher/commit/a71e8d56880d22f05a90cb24f8681a5818ee5876)

Terminal 1

.. code:: shell

    ros2 launch dummy_robot_bringup.launch.py

Terminal 2

.. code:: shell

    ros2 run joint_state_publisher joint_state_publisher single_rrbot.urdf 

Terminal 3

.. code:: shell

    rviz2

In RViz

* Fixed Frame: "map" -> "world"
* Add "TF"
