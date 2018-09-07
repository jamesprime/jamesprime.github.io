---
layout: page
title: The Schrödinger Equation
---
The Schrödinger equation exists as the sort of quantum-world equivalent to $$F = ma$$ in the Newtonian world.

$$
\mathbf{E \Psi} = \mathbf{\hat{H} \Psi}
$$

$$\mathbf{\hat{H}}$$ denotes the Hamiltonian operator, which is effectively a term that accounts for the state of a given system.  It encompasses the kinetic energies of the nuclei and electrons, and the "potential" energies of --- i.e. interactions between --- the nuclei and other nuclei, the electrons and other electrons, and the nuclei and electrons.

The goal would be to figure out a wavefunction, $$\mathbf{\Psi}$$, that minimises the energy $$\mathbf{E}$$ when combined with the Hamiltonian operator.  **Solve for $$\mathbf{\Psi}$$!**

## The Born-Oppenheimer approximation

Assuming the nuclei are effectively stationary --- as their motion is negligible compared to that of the much faster electrons --- and fixing their psoitions in space allows us to ignore contributions from:

* The kinetic energy of the nuclei, because they're not moving
* The Coulomb interactions between the nuclei, because they don't change, and so it can just be calculated once and added back in at the end

and
