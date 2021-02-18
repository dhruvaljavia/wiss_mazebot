# wiss_mazebot

SETUP >>>
1. Create a workspace
2. Copy maze_world_files folder in src of workspace
3. Install turtlebot3 packages:
   - sudo apt-get install ros-melodic-turtlebot3-msgs
   - sudo apt-get install ros-melodic-turtlebot3
4. Set TurtleBot3 Model Name(type on terminal):
   - echo "export TURTLEBOT3_MODEL=burger" >> ~/.bashrc
5. Install turtlebot3 simulation package in src of workspace:
   - git clone -b melodic-devel https://github.com/ROBOTIS-GIT/turtlebot3_simulations.git
6. Modify the path written the following lines of maze.sdf and model.sdf files according to your respective directory structure:
   - lines 111 and 138 > maze_world_files/src/worlds/maze.sdf
   - lines 26 and 53 > maze_world_files/src/models/maze/model.sdf
7. Finally, build the workspace!
