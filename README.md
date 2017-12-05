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

## Discussions

### 1. Factor graph

Please draw the diagram of the example.cpp graph. How many nodes and factors are in the factor graph?

### 2. Covarience Matrix and Jacobian Matrix

Could you explain the relationship between Covarience Matrix and Jacobian Matrix (see covariances.cpp, line 71-81.)

### 3. Covarience Matrix in the Factor Graph in 1.

What are the dimensions of the covarience matrix of the factor graph in example.cpp? Please show the covarience matrix in terminal.





