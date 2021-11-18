# Catkin workspace for rover 21

Clone this repository using the following command: 
```
git clone --recurse-submodules https://github.com/burkap/rover21_ros_ws`
```
```
cd rover21_ros_ws
catkin_make
source ./devel/setup.sh
```

To test:
```
roslaunch arm_21_gazebo arm_moveit_gazebo.launch
```
