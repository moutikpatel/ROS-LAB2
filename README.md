This is Ros Lab 2: 

Follow these instructions:
1. Prepare the repo by executing “colcon build” in the root directory of the repo.
2. 2. Setup environment:
   3. a. source install/setup.bashb.
   4. export TURTLEBOT3_MODEL=waffle_pi
3. To create the world map:
   a. Run the simulator: roslaunch turtlebot3_gazebo maze.launchb.
      Run the robot controller: roslaunch turtlebot3_teleop turtlebot3_teleop_key.launchc.
      Run rviz for mapping: roslaunch turtlebot3_slam turtlebot3_slam.launchslam_method:=gmappingd.
      To save the created map: rosrun map_server map_saver -f map
