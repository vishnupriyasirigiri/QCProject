# QCProject

## Overview

This repository contains a set of quantum computing implementations developed using Qiskit in a notebook-based environment. The project focuses on constructing and simulating fundamental quantum circuits, along with demonstrating how classical logical operations can be represented using quantum gates.

The notebook includes both theoretical constructs and practical simulations executed on a statevector and qasm-based backend.

---

## Objectives

* To implement and analyze standard single-qubit and multi-qubit quantum gates
* To visualize quantum states and their transformations
* To construct quantum circuits that replicate classical arithmetic logic
* To understand measurement outcomes and probabilistic behavior in quantum systems

---

## Implemented Components

### 1. Quantum Gate Simulations

The project includes implementations of commonly used quantum gates:

* Pauli-X, Pauli-Y
* Hadamard gate
* Controlled-NOT (CNOT)
* Toffoli (CCNOT)

For each circuit:

* The quantum circuit is constructed programmatically
* Statevector simulation is performed
* Measurement probabilities are derived
* Visualizations of quantum states are generated

---

### 2. State Analysis and Visualization

Quantum states are analyzed using:

* Statevector representations
* Probability distributions over computational basis states
* Bloch sphere visualization for single-qubit states

These tools are used to interpret how quantum operations transform qubit states.

---

### 3. Quantum Arithmetic Circuits

The notebook includes circuit-level implementations of:

* Half Adder
* Full Adder
* Half Subtractor
* Full Subtractor

These circuits are designed using reversible quantum logic and demonstrate how classical Boolean operations can be mapped to quantum systems.

---

## Technical Stack

* Python 3.x
* Qiskit
* Qiskit Aer (simulation backend)
* NumPy
* Matplotlib

---

## Execution Instructions

### Running in a Notebook Environment

1. Open the notebook file (`QCProject.ipynb`) in a compatible environment such as Jupyter Notebook or Google Colab
2. Execute cells sequentially
3. Provide inputs where required for arithmetic circuit evaluation

### Local Installation

Install required dependencies:

```bash
pip install qiskit qiskit-aer matplotlib numpy pylatexenc
```

---

## Output Description

Execution of the notebook produces:

* Quantum circuit diagrams
* Statevector outputs for each circuit
* Measurement histograms
* Bloch sphere representations for single-qubit states
* Simulation results for arithmetic circuits

---

## File Structure

```
QCProject.ipynb   Main notebook containing all circuit implementations and simulations
```

---

## Notes

* All circuits are simulated; no real quantum hardware is used
* The implementations emphasize clarity and conceptual understanding over optimization
* Arithmetic circuits are constructed using reversible logic, consistent with quantum computation constraints

---

## Author

Vishnu Priya Sirigiri

---

## License

This repository is intended for academic and educational use.
