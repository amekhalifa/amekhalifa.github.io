---
title: "Ardrone visual servoing"
collection: research
---
State estimation and control of a quadrotor of type ardrone v2 are successfully implemented. The ardrone is equipped with downward and front cameras, IMU, downward sonar, and a flight controller that is connected wirelessly with a ground station, PC, in which the estimation and control algorithms are implemented. The information obtained from the onboard sensors is fused by an Extended Kalman filter to get 3D quadrotor states. A high-level PID control algorithm is used to control the 3D linear position of the quadrotor. The ground station interface, estimation, and control algorithms are developed under ROS.
 
<iframe width="560" height="315" src="https://www.youtube.com/embed/1LL_Z5CmQo8" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


