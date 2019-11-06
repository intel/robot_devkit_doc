Overview
==========

Intel® Robot DevKit (RDK) Project contains robotics related open source software
components under ROS2 framework for RealSense based perceptual
computation, neuron network based object and people face detection,
object tracking and 3D localization, SLAM, navigation, visual manipulation for industry
robot, and a bunch of tools for development and debugging.

Key Packages
----------------

`ros2_intel_realsense <https://github.com/intel/ros2_intel_realsense>`_
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>

ros2_intel_realsense for using Intel® RealSense™ cameras (D400 series and T265)
with ROS2.

`ros2_object_analytics <https://github.com/intel/ros2_object_analytics>`_
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>

ros2_object_analytics is a group of ROS2 packages for real-time object
detection, localization and tracking. These packages aim to provide
real-time object analyses over RGB-D camera inputs, enabling ROS
developer to easily create amazing robotics advanced features, like
intelligent collision avoidance and semantic SLAM.

`ros2_openvino_toolkit <https://github.com/intel/ros2_openvino_toolkit>`_
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>

The OpenVINO™ toolkit quickly deploys applications and solutions that
emulate human vision. Based on Convolutional Neural Networks (CNN), the
toolkit extends computer vision (CV) workloads across Intel® hardware,
maximizing performance.

This project is a ROS2 wrapper for CV API of OpenVINO™, providing the
following features:

- Support CPU and GPU platforms

- Support standard USB camera and Intel® RealSense™ camera

- Support Video or Image file as detection source

- Face detection:

  - Emotion recognition

  - Age and gender recognition

  - Head pose recognition

- Object detection

- Object segmentation

- Demo application to show above detection and recognitions

`navigation2 <https://github.com/ros-planning/navigation2>`_
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>

The ROS 2 Navigation System is the control system that enables a robot
to autonomously reach a goal state, such as a specific position and
orientation relative to a specific map. Given a current pose, a map, and
a goal, such as a destination pose, the navigation system generates a
plan to reach the goal, and outputs commands to autonomously drive the
robot, respecting any safety constraints and avoiding obstacles
encountered along the way.

`ros2_grasp_library <https://github.com/intel/ros2_grasp_library>`_
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>

ROS2 Grasp Library enables state-of-the-art CNN based deep learning grasp 
detection algorithms on ROS2 for visual based industrial robot manipulation.

`tools <https://github.com/intel/robot_devkit_src>`_
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>

To facilitate the development work, several tools are provided, including 
`rtmonitor`_ to monitor and capture real time performance metrics of ROS2 C++ Application, 
and `rdk_perf`_ to measure ROS2 topics and show result in rqt at run time.

Reference
---------

Intel® ROS Projects: http://wiki.ros.org/IntelROSProject

Intel® ROS2 Projects: https://index.ros.org/doc/ros2/Related-Projects/Intel-ROS2-Projects/

.. _rtmonitor: https://github.com/intel/robot_devkit_src/tree/master/tools/rtmonitor
.. _rdk_perf: https://github.com/intel/robot_devkit_src/tree/master/tools/rdk_perf
