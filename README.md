# MolFlowSurfaceRoughness
Computational Project on Effect of Surface Roughness on Particle Trajectory Distribution

It is important to note that while using the program MolFlow, importing from CAD may result in leaks and breakages of the model due to discretisation issues. Moreover, to run simulations properly, one must specify whether surfaces are "one sided" or "two sided", which is handeled poorly if directly import from CAD. These issues can result in trajectories bouncing in a small space (and because molflow treats all trajectories equally regarless of how short they are) and take unreasonable computation power.
