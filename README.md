# Quantum_Computing_relative_phase
Quantum Computing Relative Phase example with Bloch Sphere Visualiozation

# Qiskit Bloch Sphere Visualization

This Jupyter Notebook demonstrates how to construct and visualize a single-qubit quantum state using Qiskit’s `Statevector` class.

## What It Does

- Creates a qubit state using parameters θ (theta) and φ (phi)
- Uses the `Statevector` class from `qiskit.quantum_info` to define the quantum state
- Displays the state in LaTeX and visualizes it on the Bloch Sphere

## Qubit Formula

The qubit is defined as:

\[
|\psi\rangle = \cos(\theta/2)|0\rangle + e^{i\phi}\sin(\theta/2)|1\rangle
\]

with:
- θ = π × 1/3
- φ = π × 1/8

## Dependencies

- Python 3.9+
- Qiskit
- NumPy
- Jupyter Notebook

To install Qiskit:
```bash
pip install qiskit


## To Run

```bash
jupyter notebook Q_C.ipynb

