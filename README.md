# LiDAR Scout Rover Website

A web-based control and monitoring interface for the LiDAR Scout Rover autonomous system. This dashboard provides real-time telemetry, navigation visualization, and manual control capabilities for rover operations.

## Table of Contents
- [Overview](#overview-tab)
- [Stacks](#stacks-page)
- [Navigation](#navigation-page)
- [Controller](#controller-page)
- [Topics](#topics-page)

## Overview Tab

<img width="765" height="439" alt="Overview" src="https://github.com/user-attachments/assets/781c8096-76ae-4e7f-ba8e-b8a3967ba3d9" />

The Overview page is the main dashboard for monitoring the rover in real time. It displays the camera feed, connection status, control mode, goal distance, gas sensor data, obstacle activity, teleoperation controls, and a local navigation view—all in one place for quick situational awareness during operation.

## Stacks Page

<img width="1037" height="315" alt="Stacks Page" src="https://github.com/user-attachments/assets/f68c5eaa-7092-4b60-b39f-2b07b688a38e" />

The Stacks page displays the rover's system architecture and active ROS 2 components. It shows the main topics and subsystems for sensing, navigation, safety, and motor control, helping explain how the rover software is organized.

## Navigation Page

<img width="1032" height="310" alt="Navigation page" src="https://github.com/user-attachments/assets/722ab777-1256-4807-9d8d-28269269220e" />

The Navigation page displays the rover's pose, path status, and active navigation data. It shows pose values, plan status, goal distance, and the current control source, providing a quick view of Nav2 operation without needing RViz.

## Controller Page

<img width="1385" height="425" alt="Controller page" src="https://github.com/user-attachments/assets/e54df2c1-9cb4-4305-9d36-024ba5366ce5" />

The Controller page focuses on manual control and drive mode status. It displays whether the rover is being controlled by navigation, avoidance, manual input, or is idle, while also showing how velocity commands flow through the different `/cmd_vel` topics.

## Topics Page

<img width="1903" height="599" alt="Topics tab" src="https://github.com/user-attachments/assets/327c71d3-bf23-4bb3-b2cc-4bc6fd7bfd62" />

The Topics page lists the main ROS 2 topics used by the rover system. Topics are grouped by perception, navigation, and control, providing a quick reference for monitoring the rover's active Point-LIO, Nav2, obstacle, and command topics.


