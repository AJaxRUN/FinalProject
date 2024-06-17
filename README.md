## Project Package Overview

### add_markers
- **Description**: This package handles the addition of markers in the simulation.
- **Dependencies**: 
  - `roscpp`: ROS C++ client library.
  - `visualization_msgs`: Messages for visualizing data in RViz.
  - `geometry_msgs`: Messages for common geometric primitives such as points, vectors, and poses.

### turtlebot_interactive_markers
- **Description**: This package allows for interactive marker control in RViz.
- **Dependencies**: 
  - `interactive_markers`: Tools for creating interactive markers.
  - `visualization_msgs`: Messages for visualizing data in RViz.
  - `geometry_msgs`: Messages for common geometric primitives such as points, vectors, and poses.
  - `roscpp`: ROS C++ client library.

### turtlebot_rviz_launchers
- **Description**: This package contains RViz launchers for the TurtleBot.
- **Dependencies**: 
  - `rviz`: 3D visualization tool for ROS.
  - `roscpp`: ROS C++ client library.
  - `visualization_msgs`: Messages for visualizing data in RViz.

### turtlebot_description
- **Description**: This package provides the URDF model of the TurtleBot.
- **Dependencies**: 
  - `urdf`: Universal Robot Description Format for representing a robot model.
  - `xacro`: XML macro language for creating URDF files.
