# Custom Gazebo Robot Park 

This repository contain all relevant files for custom Gazebo world built to house future robots. 



### Getting started

First, you need to build the project. Navigate to build directory and execute the following commands:

```shell
cmake /..
make 
export GAZEBO_PLUGIN_PATH=${GAZEBO_PLUGIN_PATH}:/<PATH TO DIRECTORY>/build
```

Afterwards, move to `world` directory and fire up the Gazebo world

```shell
cd ../world
gazebo RoboPark
```