Arm Drone URDF

Link to CAD model on Onshape:
https://cad.onshape.com/documents/58d398ac98a5cfbd812c2b5b/v/c5caf0953f401d5a26158f93/e/49327196d398bbf9e76e13bd

Link to URDF exporter:
https://onshape-to-robot.readthedocs.io/en/latest/

This is a ros2 package. The URDF can be launched and visualized with:
ros2 launch arm-drone arm-drone_launch.py

In another terminal, launch rviz2, add robot_model and tf, set world frame to drone, and you're all set