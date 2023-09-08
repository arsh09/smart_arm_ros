## Smart Arm Simulation 

### Instructions: 


This is how you setup the simulation

```bash
$ cd $HOME
$ mkdir -p smart_ws/src
$ cd $HOME/smart_ws/src
$ git clone -b noetic-devel --recursive  https://github.com/arsh09/smart_arm_ros.git
$ git submodule update
$ cd $HOME/smart_ws/
$ catkin_make
```

This is how you bringup everything 

```bash
$ source $HOME/smart_ws/devel/setup.bash
$ roslaunch smart_arm_bringup smart_arm_bringup.launch
```