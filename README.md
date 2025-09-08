Understanding molecular interactions at the quantum level is one of the central challenges in physics, chemistry, and quantum computing. The hydrogen molecule, as the simplest diatomic system, serves as a benchmark for testing quantum simulation methods. This project combines quantum algorithms, numerical simulations, and visualization to demonstrate how qubits can capture fundamental aspects of molecular bonding.

Key Aspects of the Project:
1. Hamiltonian Construction: Derived the electronic Hamiltonian of H₂ and mapped it onto qubits.
2. Potential Energy Surface (PES): Computed the PES and identified the equilibrium bond length.
3. Hartree–Fock & VQE: Compared classical Hartree–Fock with Variational Quantum Eigensolver (VQE) results, validating the accuracy of the quantum approach.
4. 3D Visualization: Modeled H₂ bond formation dynamically, showing how electrons transition from isolated atoms into a shared molecular orbital.
5. All key physical quantities — bond length, energy, orbital radii — were derived using quantum simulation methods rather than pre-assumed constants.

Results:
1. Equilibrium Bond Length: ~0.763 Å (consistent with theory).
2. Ground State Energy: Obtained from VQE, in close agreement with exact diagonalization.
3. Visualization: Developed an animation of H₂ bond formation, transitioning from separated atoms to a stable molecular bond.


![Demo Animation]("C:\Users\avane\output.gif")



Future Work:

The current work focuses on the ground state of H₂. Extension is the simulation of excited states using quantum algorithms (e.g., subspace expansion methods or quantum equation-of-motion approaches). This will allow a deeper exploration of spectroscopy and molecular dynamics, which I plan to pursue as a next step.


