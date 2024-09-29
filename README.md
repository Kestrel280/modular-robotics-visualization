# Modular Robotics Simulation

This repository hosts a set of tools which can be used to simulate modular robot reconfiguration.
Example use cases include:

- Finding the shortest path from an initial configuration to a desired configuration
- Analyzing and comparing the effectiveness of different models (ex: sliding vs pivoting)
- Determining if a configuration is "super-rigid"

## Usage

This section briefly describes how to find a shortest path between two configurations.
For more specific information about each step of the process, see the relevant tools [wiki page](https://github.com/gShahr/modular-robotics/wiki).

1. Set up initial and desired configurations using the [3D Tiler](https://Modular-Robotics-Group.github.io/modular-robotics/3DTiler/Index.html).
2. Run [Pathfinder](https://github.com/Modular-Robotics-Group/modular-robotics/wiki/Pathfinder) with the configurations.
3. Visualize the generated path in [WebVis](https://Modular-Robotics-Group.github.io/modular-robotics/WebVis/index.html).

## Install

Both the 3D Tiler and WebVis are web applications, and as such do not need to be installed unless
you need a local modified version. The process for building and running Pathfinder is described
[here](https://github.com/Modular-Robotics-Group/modular-robotics/wiki/Pathfinder#compiling).

## 3DTiler

3DTiler can be used to set up configurations for modular robots, plan out possible configurations,
or just make stuff out of cubes (or rhombic dodecahedra).

<p align="center">
  <img src="https://github.com/user-attachments/assets/d0e8ca45-8fe5-437e-8750-eacd78040120" width="640">

  <p align="center">
    <em>3DTiler UI</em>
  </p>
</p>

[Documentation](https://github.com/gShahr/modular-robotics/wiki/3D-Tiler)

[Open 3DTiler](https://Modular-Robotics-Group.github.io/modular-robotics/3DTiler/Index.html)

## Pathfinder

Pathfinder will find the shortest path between two configurations, if such a path exists.

[Documentation](https://github.com/Modular-Robotics-Group/modular-robotics/wiki/Pathfinder)

[How to compile](https://github.com/Modular-Robotics-Group/modular-robotics/wiki/Pathfinder#compiling)

## Visualization

WebVis helps validate paths found using Pathfinder by animating the sequence of moves found.

<p align="center">
  <img src="https://github.com/user-attachments/assets/a5a6754b-7876-4b19-a570-a5dc63a21dd3" width="640">

  <p align="center">
    <em>WebVis UI</em>
  </p>
</p>

[Documentation](https://github.com/gShahr/modular-robotics/wiki/Visualization-Tool)

[Open WebVis](https://Modular-Robotics-Group.github.io/modular-robotics/WebVis/index.html)
