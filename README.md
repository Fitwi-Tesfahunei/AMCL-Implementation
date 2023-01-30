# AMCL-Implementation
AMCL Implementation

This shows the implementation of the Adaptive Monte Carlo Localization (AMCL) algorithm. To do this, I had to generate a map of my simulation world with the help of the PGM Map Creator package. Then, I set up the AMCL launch file that includes the AMCL, Map Server, and Move Base nodes. Finally, I set up the ROS Teleop package to move direct the robot.
In the beginning, it can be seen that the particles are scattered. However, as the robot moves, it can be seen that the particles converge and localize the robot with minimal error.
