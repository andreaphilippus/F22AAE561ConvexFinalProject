# Optimal 6 Degrees-of-Freedom Station-Keeping of a Satellite in a Cislunar Halo Orbit via Lie Algebra based Convex Model Predictive Control

https://github.com/andreaphilippus/F22AAE561ConvexFinalProject/

This is a final project in a course, Introduction to Convex Optimization (AAE 56100), instructed by Professor Dengfeng Sun in Fall 2022.

The main script is ```code/main_CVX.m```.

## Problem Description

An active spacecraft is to track reference orbit and attitude on a Earth-Moon $L_2$ halo orbit with optimal amount of fuel using Model Predictive Control algorithm with convexified problem.

## Authors

Parts of the code are written/contributed by:

* [Minyoung Andrea-Philippus (Philip) Ra](https://github.com/andreaphilippus/) - [LinkedIn](https://www.linkedin.com/in/philipra/)
* [Joseph Le](https://github.com/josephtule) 		- [LinkedIn](https://www.linkedin.com/in/joseph-le-844823170/)

## Dependencies

The code uses [CVX](http://cvxr.com/) library for optimal control calculation.

The code requires MATLAB version of 2021b or later to run ```draw_video_CasADi.m``` as it uses ```exportgraphics``` feature which is added on version 2021b. 
* Negligible if ```draw_video_XXX``` lines in ```casadi_CR3BP_RK4.m``` are commented out.

## Excerpt from Introduction

This project will study the optimal control for station keeping of a spacecraft
near the $L_2$ point in order to find insight that may be generalized to controlling around other Lagrange points. In a
typical space mission, the spacecraft state to be controlled is both position and attitude, and it is referred to as relative 6
degrees-of-freedom (6DOF). In non-linear dynamical environments such as the Cislunar space, both translational and
rotational motions are often volatile, leading the uncontrolled object deviate from a reference behavior over time. For
a typical multi-spacecraft mission, proximity operation and formation flight of two or more spacecrafts are included.
Control of such operations requires coupling between relative attitude and position taken into consideration.

## Special Notes

Thanks to Mark and Andy who were our great teammates from [AAE 56800 Final Project](https://github.com/andreaphilippus/Sp22AAE568T3FinalProject) in Spring 2022,
which became the foundation of this project.

* [Mark Batistich](https://github.com/MarkBatistich) 	- [LinkedIn](https://www.linkedin.com/in/mark-batistich/)
* [Andrew Kim](https://github.com/akimb) 		- [LinkedIn](https://www.linkedin.com/in/andrewkim101/)
