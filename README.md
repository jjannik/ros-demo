# ros-demo

## Prerequisite

Install VS Code + Extension "Dev Containers"

## Getting Started

1. Go inside the `src` folder of the repo.
2. Open vscode and press Shift+Ctrl+P to select `Reopen in container` or `Build Container`.
3. Wait until VScode is attached to the running docker container (bottom left of vscode turns blue with the name of the running container)
4. Go to Run and Debug and start: `ROS Launch` on the top left with the green play button.

Inside the vscode, you will see two new terminals where one says

```
[INFO] [1698509372.456450883] [sim]: Publishing: 'Hello, world! 0'
[INFO] [1698509372.956450135] [sim]: Publishing: 'Hello, world! 1'
[INFO] [1698509373.456444624] [sim]: Publishing: 'Hello, world! 2'
[INFO] [1698509373.956439461] [sim]: Publishing: 'Hello, world! 3'
```
and the other one says

```
[INFO] [1698509372.456772982] [sim]: I heard: 'Hello, world! 0'
[INFO] [1698509372.956672114] [sim]: I heard: 'Hello, world! 1'
[INFO] [1698509373.456631312] [sim]: I heard: 'Hello, world! 2'
[INFO] [1698509373.956616831] [sim]: I heard: 'Hello, world! 3'
```

This result indicates that the two ROS nodes are communicating. The code in that repo can be debugged. 
Just set a breakpoint in one of the .cpp files.

Use this to start RVIZ
```
sudo apt install ros-humble-rviz2 -y
source /opt/ros/humble/setup.bash
rviz2
```
