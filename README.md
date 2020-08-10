# ROS

## 1. without load, cable
  '''
  $ roslaunch uasl_crane_gazebo testbot_house.launch
  $ rqt
  '''
## 2. with load, cable
  '''
  $ roslaunch uasl_crane_gazebo cablebot_world.launch
  $ roslaunch uasl_crane_control cablebot_control.launch
  $ rqt
  '''
rqt plugin -> topic -> easy message publisher
