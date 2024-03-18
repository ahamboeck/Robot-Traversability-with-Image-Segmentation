# Robot-Traversability-with-Image-Segmentation
This project was developed as part of a course at UAS Technikum Wien.

## Getting Started

### Dependencies
- ROS noetic
- Ubuntu 20.04
- Gazebo 11.11.0
- Boost 1.71
- C++14
- Protobuff 3.6.1

### Installing
In construction...


## Timeline
This seciton is only for myself to keep track of what I've done during the time working on it.

### 18.02.2024
Accomplished:
- Setup of the ROS enviornment with an explorer.

### 20.02.2024
Accomplished:
- Setup with gazebo and explorer lite.

### 21.02.2024
Accomplished:
- Clean up github
- Add gazebo world to pgm package

To-do:
- Add virtual camera for gazebo
- Extract video stream
- Create a custom world with textured ground (grass, gravel, water, asphalt)
- Extract ground truth maps with the pgm package

### 22.02.2024
Accomplished:
- Clean up github
- Create map from gazebo world
- Improve explorer package

To-do:
- Add virtual camera for gazebo
- Extract video stream
- Create a custom world with textured ground (grass, gravel, water, asphalt)
- Check if the gazebo to pgm converter creates correct maps (resolution etc.)

### 25.02.2024
Accomplished:
- Link submodules to forked repository
- Add virtual camera for gazebo
- Get video stream via ros topic
- Add new maps for exploration

To-do:
- Create a custom world with textured ground (grass, gravel, water, asphalt)
- Check if the gazebo to pgm converter creates correct maps (resolution etc.)

### 03.03.2024
Accomplished:
- Add model with low friction to gazebo map
- Rotate camera
- Remap local_costmap

To-do:
- Manipulate local_costmap and check for results
- Check if odometry can mess up the mapping process due to slipping
- Create node that publishes a % of the ground truth map explored by the explorer
- Train model on custom dataset
- Add model for grass in gazebo
- Create a custom world with textured ground (grass, gravel, water, asphalt)
- Check if the gazebo to pgm converter creates correct maps (resolution etc.)