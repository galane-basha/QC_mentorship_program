## Quantum Noise Analysis and Addition
Project Overview

This project explores the impact of noise on quantum circuits, specifically in a quantum addition operation using the Draper adder algorithm. Implemented in Qiskit, the project includes:

Noise Model: Adds noise to a quantum circuit using random Pauli operators based on specified probabilities:
        α: Probability of noise after a single-qubit gate.
        β: Probability of noise after a two-qubit gate.

Gate Basis Transformation: Converts any quantum circuit to use the gate basis {CX, ID, RZ, SX, X} to align with the capabilities of typical QPUs.

Quantum Addition (Draper Adder): Implements quantum addition using Quantum Fourier Transform (QFT) from scratch.

Noise Analysis on Quantum Addition: Combines the above to analyze how noise impacts the accuracy of quantum addition:
        Higher noise reduces accuracy.
        Strategies like error correction, circuit optimization, and noise-aware compilation can mitigate these effects.

Usage

    Open the provided .ipynb file for a step-by-step explanation and code implementation.


Requirements
 Basic understanding of Quantum Computing

Install dependencies with:

    %pip install qiskit[visualization]==1.0.2
    %pip install qiskit-aer
