# Quantum Simulation of an Ising Ring 

Jupyter notebook implementing and analysing trotterized time evolution for a transverse‑field Ising ring (periodic boundary conditions) and its ground-state behaviour (e.g. frustration).

This was adapted from the final project of the course "Quantum Information" (2024/2025)- MSc. Theoretical Physics @ University of Porto.

## Contents

### 1. Hamiltonian Simulation via Trotterization
* Derivation of the First-Order Trotter-Suzuki decomposition for the Ising Hamiltonian & mapping physical parameters to quantum gates.
* Implementation of time evolution circuits under periodic boundary conditions and study of Trotter error.

### 2. Ground-state Behaviour
* Implementation of variational solvers (QAOA) to approximate the ground state energy.
* Using Path-Integral Quantum Monte Carlo to validate quantum simulation results.

This is accompanied by extensive plotting of system dynamics and properties and comparison of different algorithmic approaches.

## Requirements
- Python 3.8+
- numpy, scipy, matplotlib, jupyter
- qiskit, qiskit-ibm-runtime, qiskit_aer, qiskit[visualization], qiskit_algorithms, qiskit_addon_utils (see notebook for versions).
- dwave-ocean-sdk
