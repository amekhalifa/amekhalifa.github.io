---
title: "Asctec Pelican Quadrotor Rotor-assembly Identification"
collection: research
---
To estimate the rotor-assembly (ESC, Motor, and Propeller) parameters (Thrust and Drag Coefficients), an experimental setup is carried out. In this experiment,
the rotor is mounted on a 6-DOF torque/force sensor (see Appendix I for more technical
details) that is connected to a NI Data Acquisition Card (NI DAC). Then, the DAC is
connected to a PC, running SIMULINK program as an interface, to read data from DAC.
The velocity of rotor is changed gradually, and in each time, the generated thrust and drag
moment is measured and recorded using SIMULINK program. By using MATLAB Curve
Fitting toolbox the acquired data of thrust and moment is fitted to be in the form of (2.88
and 2.89). Thus, the thrust and moment coefficients can be obtained. You can check this [paper](https://arxiv.org/abs/1903.12001) and this [thesis](https://arxiv.org/abs/1904.08498) for details.
<iframe width="560" height="315" src="https://www.youtube.com/embed/D3acCZN-eBw" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


