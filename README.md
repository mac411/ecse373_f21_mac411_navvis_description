# How to use navvis_description ros package to view Navvis robot in rviz

## Setup:

Ensure a compatible version of ROS is installed on an appropriate Ubuntu distribution.

Source the ROS setup script in terminal.

Create a ROS workspace directory with catkin, and extract this package into the workspace's src directory.

Now it is possible to view the robot using rviz

## Terminal commands to launch rviz:

### Launch rviz with joint_state_publisher_gui:

roslaunch navvis_description navvis_launch &

### Launch rviz with joint_state_publisher (no GUI):

 '''roslaunch navvis_description navvis_launch use_jsp_gui:=false & '''

#### URDF or XACRO

There is another argument that can be passed in the roslaunch command to switch between running the URDF or XACRO definition of the robot

use_xacro:=true/false
