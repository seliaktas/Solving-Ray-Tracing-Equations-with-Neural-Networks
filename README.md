# Solving Ray-TracingEquations with Neural Networks

This thesis presents an innovative approach for solving ray-tracing equations using neural networks, offering faster and more accurate solutions. 
The primary objective is to solve ray-tracing equations with neural networks, 
however, we decided to initially examine the capabilities of the network in addressing a one-dimensional problem, such as the harmonic oscillator. 
Firstly, we compare various neural network models for solving the harmonic oscillator equation. 
These include conventional neural networks, physics-informed neural networks (PINNs), and a combined model the Hamiltonian approach with the PINN. 
Conventional neural networks require balanced data to solve the problem and struggle when data is not provided. 
Conversely, PINNs are able to learn successfully with a small dataset by satisfying physical equations, for both provided and unprovided data regions. 
However, the aim is to solve these equations with only initial conditions, without providing any additional data. 
To achieve this, a neural network model integrating the Hamiltonian approach with PINN is introduced.
This integrated model mainly focuses on energy conservation, enabling the model to find solutions using initial conditions. 
The application of this thesis is solving ray-tracing equations in linearly heterogeneous media, both isotropic and anisotropic using the integrated model. 
We solve ray-tracing equations for an isotropic continuum in the forward problem by providing parameters like velocity, take-off angle, and time.
The model efficiently determines seismic wave ray paths. 
In the inverse problem, we aim to determine the angle and velocity model for an isotropic continuum by providing receiver and source locations, and travel time. 
We then progressively increase the complexity of the problem, starting with isotropic velocity model and advancing to constant elliptically and to generalized elliptically anisotropic models.

Please refer to the conclusion of the thesis for a detailed overview of the results.
