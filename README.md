# ros_navigation_vrep_simulation
**For mooc**  
ros navigation simulation using vrep.  
## steps:  
1. Run roscore and vrep; 
2. Go to workspace and build move_base package;
~~~
catkin build move_base
~~~  
2. Open vrep scene and run simulation;  
3. Go to /move_base and run:  
~~~
roslaunch move_base move_base.launch
~~~
4. Open rviz;  
5. Set goal point.
