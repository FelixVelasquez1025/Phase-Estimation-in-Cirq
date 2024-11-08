# Phase-Estimation-in-Cirq

This repository contains a Python script that implements a Phase Estimation circuit using Google's Cirq library. Phase Estimation is a fundamental algorithm in quantum computing used to estimate the eigenphase of an eigenvalue of a unitary operator. This project aims to demonstrate the application of phase estimation in Cirq with a simple example.



**Overview**

The Phase Estimation algorithm uses quantum gates to estimate the phase of an eigenvalue of a given unitary operator 
𝑈
U. 

The project initializes a quantum circuit in Cirq that:

Creates a superposition of states.

Applies controlled unitary operations.

Performs the Quantum Fourier Transform (QFT) to encode the phase information in a measurable way.

Measures the qubits to retrieve the estimated phase value.

This implementation provides an educational introduction to the Phase Estimation algorithm and demonstrates how to use Cirq for building and simulating quantum circuits.



**Project Structure**

phase_estimation_circuit.py: The main script to build and simulate the Phase Estimation circuit.

README.md: Overview, setup instructions, usage, and reference information.



**Prerequisites**

Python 3.8+

Cirq: Google's open-source framework for creating and simulating quantum circuits.




**Script Details**

Define the Unitary Operator: The script allows you to define a unitary operator for which you want to estimate the phase.

Apply Controlled Unitaries: Controlled unitary gates are applied to each qubit based on their position.

Quantum Fourier Transform (QFT): The QFT is applied to transform the encoded phase into a measurable form.

Measurement and Output: The script outputs the measurement results, giving an estimation of the phase.


**References**

Cirq Documentation: https://quantumai.google/cirq

Qiskit Textbook on Phase Estimation: https://docs.quantum.ibm.com/api/qiskit/qiskit.circuit.library.PhaseEstimation
