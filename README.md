# 3D modelling and visualization of Robots using ROS and Rviz

To develop any new robotic system may be mobile robot, robotic arm, aerial robot, etc., it is impotant to simulate it in the virtual environment with maximum possible real time capabilities. This includes development of ROBOT models, their kinematic and dynamic behaviours, sensors and controllers of the robot and the surrounding environment.

This project is the kick-off in this direction. ROS kinetic is used for the developement along with Linux (Ubuntu 16.04). Three different models are tried and tested using Rviz (ROS visualization) environment. This is one of the visualization and simulation tool available as libraries with ROS.

The 3 Robot models are:
1. Four Wheel Robot (it is not ackermann drive)
2. Differential robot
3. seven DOF arm

The model is developed using URDF and XACRO and then LAUNCH files are used to run them in Rviz evnironment.

## Project Folder structure

1. docs 
    * Project details.pdf - detailed project report covering hardware and software description
    * differential_wheeled_robot.pdf - graphical view of hierarchy of links of differential wheel robot
    * four_wheel_robot.pdf - graphical view of hierarchy of links of 4 wheel mobile robot
    * seven_dof_arm - graphical view of hierarchy of links of seven DOF robotic arm
2. src
    * robots_3D_modelling_and_visualization - ROS package containing all the urdf, xacro and launch files of the project
    
3. test
    * 4 wheel robot in rviz.png - robot in Rviz
    * differential_drive_robot in rviz.png - robot in Rviz
    * seven_dof_arm in rviz.png - robot in Rviz
