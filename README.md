# swarm_formation_sim
A collection of swarm robot formation simulations using Python and Pygame. I have done [swarm robot simulations in ROS](https://github.com/yangliu28/swarm_robot_ros_sim.git) before, but decided to give Python and Pygame a try, for the simpilicity in programming the alogrithms and implementing the graphics.

Line formation simulation features climbing method and competing mechanism. The requirements for the robots: basic wireless communication, limited communication range, direction and distance sensing of a robot in range, robot modeled as dot so no collision avoidance necessary, omnidirection movement, homogeneous robots. When running on real robots, the algorithm will rely heavily on communication to update robots' knowledge. More details can be found in the comments in "line_formation.py".

Run the line formation simulation:

`python line_formation.py`

