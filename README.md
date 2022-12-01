# spawn_multiple_robot
How to spawn multiple USVs on VRX sim
enter command "roslaunch vrx_multirobot.launch" after initializing roscore
These scripts will open the sim environment with two USVs.
vrx.launch file is the default launch file of the simulation environment.
You can edit these folders by comparing your default launch file to these files.


robots.launch file has the parameters for spawning USV's
one_robot.launch spawns one robot. vrx_multirobot.launch file calls this script for creating each robot.
