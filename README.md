# Turtlesim Catcher
Simple project with turtle simulator, using ros2 nodes, topics, services, parameters and launch files. The master-turtle tries to catches all the other turtle that spawns within every 2 seconds. The nodes run in a endless loop and the entire simulation is run using launch file.
<br> There are mainly three nodes - 
> ● The turtlesim_node from the turtlesim package <br>
> ● A custom node to control the turtle (named “turtle1”) which is already existing in the 
turtlesim_node. This node can be called turtle_controller. <br>
> ● A custom node to spawn turtles on the window, and to manage which turtle is still “alive”
(on the screen). This node can be called turtle_spawner. <br>

### Pre-requisite ###
> **Ubuntu 22.04 LTS** <br>
> **ROS2-Humble installed** <br>
