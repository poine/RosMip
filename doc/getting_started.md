# getting started

## Installing
* Install 'Robotics Cape Library for BeagleBone'

* Clone and build the repository in a catkin workspace (maybe look at [this](http://wiki.ros.org/catkin/Tutorials/workspace_overlaying) if you are not familiar with ROS)

## Running

### Simplest simulation

try: `roslaunch rosmip_gazebo_demos odom_navigation_demo.launch`

This will start a rosmip physics simulation in gazebo, the robot control code (balancing controller and odometry), move base (the navigation stack) and rviz (the visualization interface). You should see rosmip start to balance itself. Click on '2D Nav Goal' in rviz, then somewhere on the ground to set a navigation goal to the robot. The robot should set itself in motion and move to where you clicked.


[![Video](https://img.youtube.com/vi/Yv71yOK3KO0/0.jpg)](https://youtu.be/Yv71yOK3KO0 "Show screen capture")

