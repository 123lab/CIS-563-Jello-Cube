CIS-563-Jello-Cube
==================
I implemented Jello Cube Simulation using C++  
Particle Based Jello Cube System is a particle based mass-spring system, in which the particles are connected by structur bend and shear spring (structural springs are between neighbor particles, shear springs are between digonal neighbor particles, and bend spring are between every second, third, and fourth spring.   
Integrated over time with RK4, the simulation uses a penalty based constraint system to handle collision and interpenetrations. When the particle comes close to the surface, a strong force is applied to the particle in order to get it out of surface. 

