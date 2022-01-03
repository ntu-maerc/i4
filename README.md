# Brief Description
A robotic arm model, two wheels and a chassis, is built from scratch with the help of URDF. PID controllers, specifically TRAJECTORY controllers (robotic arm) and a differential drive controller (wheels), are implemented so that the robot can move freely during simulation. A fixed Hokuyo laser is attached to the front of the robot to allow for the creation of a map, or SLAM. The SLAM algorithm that was used is known as Gmapping. Upon completing SLAM, the localization of the robot is then carried out, and the algorithm used, as seen in the code, is the AMCL. Subsequently, we successfully incorporated the “move_base” package, which is already provided in ROS, to allow our robot to perform autonomous navigation whilst avoiding obstacles in its path.

## What’s next?
In the coming weeks, we will simulate our robot in Moveit, in which we will implement inverse kinematics to our robot’s end effector. By doing so, our robot, specifically its arm, will be capable of moving freely to carry out mundane tasks, for instance, picking up objects on the ground.
Main Aim: to be able to accomplish the robotic arm aspect of our robot. 

# Projects at NTU MAE Robotics Club

* Part of an NTU MAERC initiative

## Intermediate Group 4

* Repository for Intermediate Group 4 to build code!

### Steps to clone the repository
* Launch a terminal and run the command  
```
$ git clone https://github.com/ntu-maerc/i4.git 
```
