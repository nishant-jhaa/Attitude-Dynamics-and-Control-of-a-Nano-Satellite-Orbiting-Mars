# Attitude-Dynamics-and-Control-of-a-Nano-Satellite-Orbiting-Mars
This project illustrates how to evaluate and implement a range of attitude control modes. Besides the simple PD control uses here, other attitude tracking control solutions could readily be substituted



This project considers a small satellite orbiting Mars at a low altitude gathering science data. However, this small satellite needs to transfer this data to a larger mother satellite at a higher altitude. Further, to keep the batteries from draining all the way, periodically the satellite must point its solar panels at the sun to recharge. Thus, three mission goals must be considered by the satellite: 
1) point sensor platform straight down at Mars, 
2) point communication platform at the mother satellite, and 
3) point the solar arrays at the sun. 
In all scenarios the small spacecraft and mother craft are on simple circular orbits whose motion is completely known.
The high-level goal of this project is to design a thruster-based attitude control to achieve these attitude control scenarios. In order to satisfy the mission requirements, the spacecraft’s body-frame B must be driven towards various reference body-frames R that corresponds to the desired attitude. The reference attitude is computed from the knowledge of the spacecraft position and velocity about Mars, as well as the knowledge of the mother satellite motion for the communication scenario and the knowledge of the sun heading for the power generation scenario. Once this reference is derived, we will implement the torque control law u that drives the current attitude MRP σB/N and the angular velocity ωB/N towards their reference values (σR/N, ωR/N). The scope of this project encompasses reference frame generation, attitude characterization and feedback control.


** This project is developed by acquiring necessary skills from the MOOC Offered by University of Colorado Boulder on Coursera (https://in.coursera.org/learn/capstone-mars-mission/). The detailed description of the tasks to be done is given in the document uploaded as "Spacecraft MOOC". 
For further reading and reference, Kindly Refer: Schaub, H. and Junkins, J. L., Analytical Mechanics of Space Systems, AIAA Education Series, Reston, VA, 4th ed., 2018, doi:10.2514/4.105210
