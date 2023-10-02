# ecse373_f22_hxz936_navvis_description

To run the project, run the display.launch file by:
roslaunch navvis_description display.launch

# Default options are to run using the outdated robot.urdf file and to use the joint_state_pulisher.gui.

To run using the updated robot.xacro file by:
roslaunch navvis_description display.launch use_xacro:=true

To use the joint_state_publisher instead of the joint_state_publisher_gui by:
roslaunch navvis_description display.launch use_gui:=false

To run using the updated robot.xacro file and the joint_state_publisher by:
roslaunch navvis_description display.launch use_xacro:=true use_gui:=false
