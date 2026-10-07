# Quantum Random Number Generator

## Project Overview
A Quantum Random Number Generator (QRNG) that uses quantum superposition and measurement to generate random 0 and 1 bits.

## How It Works
1. A qubit is created.
2. A Hadamard (H) gate puts the qubit into superposition.
3. The qubit is measured.
4. The measurement produces either 0 or 1.
5. Multiple measurements are used to generate random bits.

## Technologies Used
- Python
- Qiskit
- Qiskit Aer Simulator

## Testing
The quantum-generated results are compared with random bits generated using Python's `random` module.

## Project Status
Working prototype completed.
