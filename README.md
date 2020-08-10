# ROS

## 1. Load와 cable이 없는 version

roslaunch uasl_crane_gazebo testbot_house.launch

rqt

## 2. Load와 cable이 있는 version

roslaunch uasl_crane_gazebo cablebot_world.launch

roslaunch uasl_crane_control cablebot_control.launch

rqt

rqt 실행 후 plugin -> topic -> easy message publisher 설정 필요
