# ros-notes

## ROS2 Write A Publisher-Subscriber Node Using Python

![flow](./images/image.png)

1. Create  package
```
ros2 pkg create --build-type ament_python <package name>
``` 

<img src="./images/dir_tree.png" width="300" height="100" alt="dir-tree"> 


2. Write a publisher node

[publisher_member_function](./publisher_member_function.py)

<img src="./images/image-1.png" width="300" height="300" alt="publisher-tree"> 

3. Add Dependencies

<img src="./images/package_xml.png" width="300" height="300" alt="package_xml"> 


## ROS Command

```
rosbag info xxx.bag 

rosbag play <bag 1> <bag 2>

rostopic list

rostopic echo <topic name>
```