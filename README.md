# ros-demo


Install VS Code + Extension "Dev Containers"

Go into src folder and open vscode and shift+Ctrl+P and select Reopen in container.

Inside VS Coce run 

Go to Run and Debug and start: "ROS Launch" on the top left with the green play button.

You will see two ROS nodes which are communicating in one direction. The code can be debugged.


Use this to start RVIZ
```
sudo apt install ros-humble-rviz2 -y
source /opt/ros/humble/setup.bash
rviz2
```
