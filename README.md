# swimmingTurtleROS
Install ROS


open a terminal and put roscore
then open another terminal
then input


          roslaunch  turtlemimic.launch
then open a new terminal and input

           rostopic pub /turtlesim1/turtle1/cmd_vel geometry_msgs/Twist -r 1 -- '[2.0, 0.0, 0.0]' '[0.0, 0.0, -1.8]'
