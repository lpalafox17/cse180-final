CSE180 Final Project
=======
# Tasks
CSE180 Final Project created through the use of ROS2 Gazeboo and C++
- [x]  Move the turtlebot
- [x]  Safely move the turtlebot and avoid any obstacle
- [x]  Explore the environment
- [x]  Returns a coordinate of the extra cylinder with a reasonable margin of error.


# Compile and Run
In order to succesfully run this project there are a couple of things needed before starting. 
- Ubuntu 20.04 succesfully installed with packages.
- Install ROS2 foxy
- Install Gazebo
- Install nav2 packages
- Install colcon 
- Stefano Carpin's [MRTP](https://github.com/stefanocarpin/MRTP)<br/>
A more detailed installation instruction can be found in Stefano Carpin [Installation Instructions](https://github.com/stefanocarpin/MRTP/wiki/Installation-Intructions)

# Compiling 
`git clone https://github.com/lpalafox17/CSE180FINAL.git`  
In terminal write:
```bash
cd /CSE180FINAL/src
source /opt/ros/foxy/setup.bash
. install/local_setup.bash
colcon build
```


