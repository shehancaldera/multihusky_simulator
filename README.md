[![License BSD 3 Clause](https://img.shields.io/badge/License-BSD--3--Clause-brightgreen.svg)](https://opensource.org/licenses/BSD-3-Clause)
# Multi Husky Simulator Package
Simulating multiple Clearpath Robotics Husky robots in a Gazebo world uisng different namespaces. Namespacing allows us to multiply the instances of publishing ROS messages over the same topics at the same time.

Major work is based on original husky tutorials found at http://wiki.ros.org/Robots/Husky.

## Notice: 
1. Updated robot_localization package does not work very well. Therefore, robot_localization_243 package was used from its archived source as it is.

2. This work eavily depends on the original husky-simulator, husky-desktop, and their related packages being properly installed.

## Steps to Run:
1. First `git clone <repo_url>` to your `catkin_ws/src`
2. Run catkin make in your `catkin_ws` dir by executing `catkin_pake --pkg multihusky_simulator`
3. Source it to your .bashrc
4. Run it by `roslaunch multihusky_simulator multihusky_random_world.launch`

### Reference:
1. Bogdon, C., 2016, Simulating Multiple Husky UGVs in Gazebo, Clearpath Robotics Blog, Available at: https://www.clearpathrobotics.com/blog/2016/03/simulating-multiple-husky-ugvs-in-gazebo/

2. Bingham, B., <bsb808>, 2017, nre_simmultihusky Git Repository, Available at: https://github.com/bsb808/nre_simmultihusky

3. The Construct, 2018, [ROS Q&A] 130 - How to launch multiple robots in Gazebo simulator?, Available at: https://www.youtube.com/watch?v=mFTkN5v4Jzc

