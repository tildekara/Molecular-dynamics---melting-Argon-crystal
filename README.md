This script is an implementation of Molecular Dynamics simulation for a set of atoms of one kind with van der Waals interactions - noble gas model. Simulating this in Jmol will show phase transition from solid crystal to gas.
Initial conditions are N atoms described with $r_i = (x_i, y_i, z_i)$ position coordinates and momentum $p_i$. Position coordinates are calculated from elementary cell vectors of the crystal. Initial momenta have Maxwell's distribution.
Each couple of atoms interacts with van der Waals forces $V^P$ and with limited area of a sphere $V^S$.

Jmol animation:
![First frame](https://github.com/tildekara/Quantum_Methods_of_Solid_State_Physics---melting-Argon-crystal/blob/master/Jmol_first_frame.png?raw=true)
![Next frame](https://github.com/tildekara/Quantum_Methods_of_Solid_State_Physics---melting-Argon-crystal/blob/master/Jmol_animation_step2.png?raw=true)
![Molten Argon](https://github.com/tildekara/Quantum_Methods_of_Solid_State_Physics---melting-Argon-crystal/blob/master/Jmol_molten_Argon.png?raw=true)
