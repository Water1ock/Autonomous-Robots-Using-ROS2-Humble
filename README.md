# Autonomous-Robots-Using-ROS2-Humble

An implementation of 3 different autonomous navigation robots fulfilling 3 different purposes:-
1. World Navigation using Nav2
2. Maze-Solving
3. Waiting Tables in a restaurant.

# World Navigation using Nav2
This autonomous robot makes use of the Nav2 stack which includes global and local planners, and integrates localization algorithms such as AMCL (Adaptive Monte Carlo Localization) to help the robot know its position within a known map. It also uses algorithms for real-time obstacle avoidance, and makes use of behaviour trees to structure high-level tasks and decision making.

![Nav2_Multi_goals](https://github.com/user-attachments/assets/4a2095b1-27b0-4e07-a600-aca36c23fa6e)


# Autonomous Maze-Solving Robot
This robot makes use of the SLAM Toolbox (tried with cartographer first, but the mapping was not accurate and the robot kept getting lost) to find its way around a maze and get out.

![maze_solving](https://github.com/user-attachments/assets/63803e17-62d7-4c51-b417-3804c037c5c7)


# Autonomous Waiter with GUI
This robot makes use of the Commander API to differentiate between the different tables and customers. It efficiently performs the task of picking up orders from a source, and delivering it to different targets autonomously in a controlled environment.

![Nav2_Waiter_bot](https://github.com/user-attachments/assets/e9d9aac9-7e7f-424f-a6d8-f358628826e2)

# Software Requirements
1. Ubuntu 22.04 (LTS)
2. ROS2 - Humble
