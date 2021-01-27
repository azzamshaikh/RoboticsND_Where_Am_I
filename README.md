# RoboticsND_Where_Am_I
Build and implement the Adaptive Monte Carlo Localization package on my robot (based on RoboticsND_Build_My_World)

## Instructions

1. Create and initialize a catkin workspace `catkin_ws`
> $ mkdir -p /***preferred directory***/catkin_ws/src  
> $ cd /***preferred directory***/catkin_ws/src  
> $ catkin_init_workspace  

2. Clone this repo in a different directory and move the 'ball_chaser' and 'my_robot' package to `src`

3. Go back to the `catkin_ws` directory and and launch the world
> $ cd /catkin_ws  
> $ catkin_make  
> $ source devel/setup.bash  
> $ roslaunch main main.launch  

The robot is now controllable via the terminal according to the instructions posted. In the RVIZ window, you will see the particle clouds adjusting with time for more accurate localization.

The parameters for the AMCL are located in `catkin_ws/src/my_robot/launch/amcl.launch`.
