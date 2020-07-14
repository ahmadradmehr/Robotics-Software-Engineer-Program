## Grid-based FastSLAM

In this project, a `gmapping` ROS package, which is based on the Grid-based FastSLAM algorithm, is implemented to map an environment.
`gmapping` provides laser based SLAM. Meaning that its node can be fed with the robot laser measurements and odometry values and expect it to provide a 2D occupancy grid map of the environment. The map will be updated as the robot moves and collect sensory information using its laser range finder sensor.
