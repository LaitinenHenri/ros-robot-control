# ros-robot-control

This is a school project I worked on with Veeti Pekonen and John Bäckström.

**Project Overview**
The goal of this project was to create a dual-arm robot using two Motoman robots provided to us. We also attached grippers to the ends of the robot arms. The task involved simulating the robot's functionality using ROS (Robot Operating System) services and actions.

**Objectives**
Box Manipulation:

Use a provided service to spawn small and large boxes in the RViz environment.
Implement a motion control system to pick up the small box and place it on the large box.
Ensure the closest robot picks up the small box and transfers it to the other robot if it cannot reach the large box.

Code Components:

Motion Control Code: Handles picking and placing operations based on coordinates from a custom service.
Random Pose Code: Generates random positions for testing and simulation purposes.

**Code Contribution**

I wrote the motion control and random pose codes entirely by myself, with some guidance from my teammates when I encountered difficulties. Partial credit goes to them for their assistance.

**Challenges and Learning**

Before this project, I had never worked with ROS, so understanding its communication system (e.g., services, actions, and topics) was initially overwhelming.
Over time, I gained a solid understanding of ROS and learned to code at an intermediate level.
This project, along with the course it was part of, sparked my enthusiasm for robotics and coding in general.


**Acknowledgments**

Special thanks to my teammates, Veeti and John, for their support and collaboration throughout this project.

