# lab9-isam

## Installation

### Dependencies

```
sudo apt-get install cmake libsuitesparse-dev libeigen3-dev doxygen graphviz

```

Note that you may install libsdl1.2-dev but maybe unstable in Virtualbox

### ROS Package

```
$ git clone https://github.com/Sensing-Intelligent-System/lab9-isam
$ cd lab9-isam
$ source environment.sh
$ cd catkin_ws
$ catkin_make
```

## Run the Examples

For examples/example.cpp
```
$ rosrun isam isam_example
```

For examples/covariances.cpp
```
$ rosrun isam isam_covariances
```
