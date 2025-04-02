# Nauti-controls
Controller scripts for PID and bounding box navigation

## Dependencies
- [ROS Noetic](https://wiki.ros.org/noetic/Installation/Ubuntu)
- [OpenCV](https://learnopencv.com/install-opencv-4-on-ubuntu-18-04/)

## Setup Instructions
- Place this package inside a catkin workspace and then build it using the following command:
```bash
catkin build
```

## How to run
- To run the bounding box navigation script, use the following command:
```bash
roslaunch nauti_control bbox_controller.launch
```
This would launch the bounding box node which would wait for