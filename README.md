
## LQR controller for a magnetic levitation train
Control design for a transrapid (magnetic levitation train type) is here proposed using LQR.

<img src="https://github.com/FedericoRollo/LQR-controller-for-a-magnetic-levitation-train/raw/master/pictures/TransrapidScheme.png" width="800" height="300" />

Simulation of the controlled system are presented using Simulink. 
Main physical components considered are:
1. Transrapid as a rigid body with elastic components along two axis;
2. Electromagnets for levitation and for lateral guide;
3. Linear synchronous motor.

The cardinal equations for the dynamics of the system have been defined and decoupled on three main directions:
1. Headway motion, along x axes (**propulsion control**);
2. Sway motion, along y axes and equations for yaw angle (**guidance control**);
3. Pump motion, along z axes, and equations for pitch and roll angles (**levitation control**).

After a linearization on defined operative points, a LQR controller has been designed for each motion. 
Finally a simulation of the overall system is proposed. 

<img src="https://github.com/FedericoRollo/LQR-controller-for-a-magnetic-levitation-train/raw/master/pictures/overallSim.png" width="700" height="200" />

In the directory **Simulations** are contained all the simulations. Two main directories are present, one for the decoupled simulations and one for the finale complete simulations. For the latter there are two different simulations: for a **linear path** and for a linear path with a **curve**.  

**Control and Simulation support contributors: Federico Rollo, Adelina Selimi.**

**Mechanical support contributors: Luca Minotti, Francesco Ancona, Lorenzo Bianchini.**
