#Autonomous Maze Solving Robot – Micromouse (Edge AI Inspired)

#Overview: This project showcases a self-learning autonomous maze-solving robot that navigates a 16x16 dynamic maze without any external signals.
It uses embedded Edge AI principles to perform real-time learning and optimization onboard a microcontroller (Arduino platform).
Developed and optimized various algorithms like FloodFill, Left Wall Follower, and others to enable efficient exploration and pathfinding.

(Project sponsored by participation and competition in BGSW India Micromouse Challenge.)

Project Features:
    FloodFill Algorithm: Dynamic pathfinding and shortest path optimization over multiple runs.
    Left Wall Follower Algorithm: Traditional wall-following strategy for initial maze exploration.
    Real-Time Self-Learning: Robot learns and stores the shortest path autonomously after exploration.
    Embedded Systems Focus: Designed for microcontroller (Arduino) deployment under tight real-time constraints.
    Simulation Environment: Included dummy maze structures and simulators for algorithm validation before physical deployment.

Technologies Used:
    C/C++ (Arduino IDE)
    Embedded Systems Programming
    Basic Edge AI Concepts (Self-learning, Real-time Optimization)
    Simulation Tools for maze environments
    Custom-built Hardware Environment (for physical robot)

How It Works:
    Exploration Phase: Robot explores the maze using Left Wall Following to gather maze structure.
    Learning Phase: Robot applies FloodFill to compute shortest path dynamically based on learned maze.
    Optimization Phase: Robot stores optimized route and executes it at maximum speed for subsequent runs.
