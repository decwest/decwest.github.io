---
layout: page
permalink: /codes/
title: codes
description: Coding (especially robot programming) and sharing my work publicly is a hobby I really love.💻 <br/> This page introduces some of my popular repositories.
nav: true
nav_order: 3
---

## [nav2_dynamic_window_pure_pursuit_controller](https://github.com/Decwest/nav2_dynamic_window_pure_pursuit_controller)

Nav2 plugin for Dynamic Window Pure Pursuit (DWPP) controller.

DWPP is a novel extension of the Pure Pursuit method that computes command velocities while considering the robot’s velocity and acceleration constraints. I first proposed this method at IAS-19 ([news](https://decwest.github.io/news/italy2025/)).

I also presented this work at ROSCon JP 2025 (in Japanese).

本取り組みをROSConJP 2025にて発表しました．[スライド (docswell)](https://www.docswell.com/s/Decwest/ZDWVW4-2025-09-16-200946)，[動画 (Vimeo)](https://vimeo.com/1122708915?share=copy)

<img src='../assets/img/codes/dwpp.gif' width="400" >

## [navgoal_webgui](https://github.com/Decwest/navgoal_webgui)

A WebGUI for publishing 2D Nav Goal (geometry_msgs::PoseStamped).

It also supports touch screens.

<img src='../assets/img/codes/navgoal_webgui.gif' width="400" >

<br/>

## [robot_simulator_template](https://github.com/Decwest/robot_simulator_template)

This repository contains some urdfs of robot components for robot simulation in gazebo, such as 2D/3D LiDAR, RGBD camera and mobile base.

<img src='../assets/img/codes/simulator_template.png' width="400">

<br/>

## [nhk2021_ilias](https://github.com/KeioRoboticsAssociation/nhk2021_ilias)

Codes and simulator for NHK Robocon 2021.

I created a urdf model of a 4 wheel steering robot, using the method to rotate joints on Gazebo by ROS Topic. I also created a precise and rotatable field model by converting a 3D CAD field to sdf.

This repository may provide expertise in simulator construction.

<img src='../assets/img/codes/simulator.gif' width="400">
