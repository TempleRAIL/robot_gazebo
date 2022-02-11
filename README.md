# robot-gazebo
---
A package to launch gazebo with turtlebot and hokuyo 2d laser.
## Preparation
install the ros-gazebo, turtlebot-description, turtlebot-bringup packages


## Usage
```
cd your_ws/src
git clone https://github.com/naiij/robot-gazebo.git
cd ..
catkin_make
roslaunch robot_gazebo turtlebot_world.launch
```

## Note
You can change the world file by type:  
```
export TURTLEBOT_GAZEBO_WORLD_FILE="your world file"
```
the laser & camera merged version will be published later.  
