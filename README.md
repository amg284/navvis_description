## ROS package for Lab 2 - Navvis_description.
### Alan Goodloe (amg284)

#### To set up project, run these :
- `source /opt/ros/noetic/setup.bash`
- `source devel/setup.bash`
- `roscore &`

Then set the robot_description, this is where it is trying to subscribe to
- `rosparam set /robot_description urdf_from_xacro.urdf`

#### Remember to install these, they are necessary later on in the lab:
- gazebo_plugins
- velodyne_description packages


#### Usage
To run the project, run the display.launch file by: 
    `roslaunch navvis_description display.launch use_xacro:=true`
