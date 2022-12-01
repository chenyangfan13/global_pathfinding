# 建图
打开gazebo roslaunch turtlebot3_gazebo turtlebot3_stage_2.launch
建图命令  roslaunch turtlebot3_slam turtlebot3_slam.launch slam_methods:=gmapping
栅格图保存 roslaunch mapserver.launch 


## 规划
打开gazebo roslaunch turtlebot3_gazebo turtlebot3_stage_2.launch
roslaunch turtlebot3_navigation turtlebot3_navigation.launch map_file:=/home/cyf/WorkSpace/ros_code/test/src/turtlebot3/turtlebot3_navigation/maps/maps.yaml
然后勾选marker，选择起点终点
