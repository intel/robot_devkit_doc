Grasp Library
=================


ROS2 Grasp Library consists of:

- A ROS2 Grasp Planner providing grasp planning service, as an extensible capability of `MoveIt Grasp Planning`_

- A ROS2 Grasp Detector interface, enabled with the specific back-end algorithm `GPD`_ with Intel® `OpenVINO`_ technology

- Hand-eye calibration generating transformation from camera frame to a specified target frame; Grasp translation to the MoveIt `Grasp Message`_

- Robot interfaces controlling the physical robot to move, pick, place, as well as to feedback robot states

- Grasp applications demonstrating the grasp planning capabilities, and telling how to put all the above software components together for intelligent visual manipulation tasks

For details, please refer to `ROS2 Grasp Library Tutorial`_.

.. _MoveIt Grasp Planning: https://github.com/intel/ros2_grasp_library
.. _GPD: https://github.com/atenpas/gpd
.. _OpenVINO: https://software.intel.com/en-us/openvino-toolkit
.. _Grasp Message: http://docs.ros.org/api/moveit_msgs/html/msg/Grasp.html
.. _ROS2 Grasp Library Tutorial: https://intel.github.io/ros2_grasp_library

