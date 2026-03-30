# Hamiltonian

A quantum computing framework for generating and constructing qubit Hamiltonians using hybrid classical-quantum workflows. This project leverages **OpenFermion** for symbolic Hamiltonian generation and **Intel Quantum SDK** for quantum-classical compilation and execution.

## Overview

Hamiltonian is designed to bridge the gap between high-level quantum chemistry problem formulation and low-level quantum hardware execution. The framework:

- **Generates symbolic Hamiltonians** from quantum chemistry problems using OpenFermion
- **Constructs optimized qubit representations** using Intel Quantum SDK's Hybrid-Quantum-Classical Library
- **Provides a seamless two-stage pipeline**: Python-based generation → C++ compilation and execution

Perfect for researchers and quantum computing practitioners working on quantum simulation, quantum chemistry, and variational quantum algorithms.

## Prerequisites

Before running this project, ensure you have:

- **Docker** installed on your system,
- **Intel Quantum SDK Docker Image**:
  ```bash
  docker pull intellabs/intel_quantum_sdk:latest
