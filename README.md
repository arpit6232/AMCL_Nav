# Navigation using AMCL

##Launch## 

    1) Open three terminal windows
    2) Run roslaunch my_robot world.launch in the first terminal window to open the Gazebo world with robot and RViz
    3) Open the amcl_rviz.rviz file in Rviz. It is saved in the my_robot/rviz/ directory
    4) Run roslaunch my_robot amcl.launch in the second terminal window
    5) Rviz will directly open pre-configured setting so have a look at the displayed topics
    6) See the position of the robot in Gazebo and accordingly select the 2D Pose Estimate in Rviz(Click on the button then click on the position in map in Rviz and hold to select the direction
    7) Then, select the 2D Navigation Goal button and select any place in the map and wait for the robot to reach its goal!
    8) Added a video file and a screenshot in my_robot/video_pics/ showing the localisation of the robot in the world with various goals
    9) In the third terminal, you can then use teleop by ruuning rosrun teleop_twist_keyboard teleop_twist_keyboard.py
    
