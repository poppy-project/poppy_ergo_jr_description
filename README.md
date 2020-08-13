# Poppy Ergo Jr description

This ROS package contains URDF and collada files to use [Poppy Ergo Jr](https://www.poppy-project.org/en/robots/poppy-ergo-jr/) robot with ROS1 Melodic.
The URDF contains also contains the collision model and is suitable for Gazebo simulations.
So far, only the gripper effector is supported. Using the lamp effector would require to update the URDF.

![Poppy Ergo Jr in RViz ROS Melodic](./doc/img/rviz.png)

## Quickstart

Launch the following command in order to run RViz, visualize the robot and move the joints. If you want the lamp effector:
```
roslaunch poppy_ergo_jr_description display.launch gui:=True lamp:=true
```
Or, if you want the gripper effector:
```
roslaunch poppy_ergo_jr_description display.launch gui:=True gripper:=true
```

## Roadmap

Feel free to open pull requests!

* [ ] Integrate the pen holder effector to xacro 
