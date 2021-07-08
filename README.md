# Robot-and-AI-Task4B-Robot-navigation
<h2>Task4 -B:</h2>

<p1>1- 1- create a package: 
  <br>
 $ cd ~/catkin_ws/src
 $ catkin_create_pkg ai_task geometry_msgs roscpp rospy std_msgs
  <br>
2- write python script.
  <br>  
3- make launch file:
  <br>
  &lt;launch&gt;
   <br>
  &lt;node name="task4b" pkg="ai_task" type="task4b.py" &gt;
   <br>
  &lt;launch/&gt;
    <br>
4- run the node:
  <br>
    a- run gazebo: roslaunch turtlebot3_gazebo turtlebot3_house.launch
    <br>
    b- run rivs: roslaunch turtlebot3_navigation turtlebot3_navigation.launch map_file:=$HOME/map.yaml
      <br>
    c- run the new node using this commands:
    <br>
    $ cd catkin_ws
      <br>
    $ source devel/setup.bash
      <br>
    $ roslaunch ai_task pub.launch
    
   
  </p>
