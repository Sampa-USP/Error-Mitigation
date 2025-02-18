Error Mitigation in Quantum Computing

This repository aims to explore and analyze error mitigation techniques in quantum computing systems, comparing two distinct methods. Error mitigation is a crucial field for improving the accuracy of results obtained from noisy quantum hardware.

Project Description

Current quantum computing systems suffer from noise and errors in circuits, which hinder the accuracy of their results. This repository investigates and implements two popular error mitigation methods, seeking to understand their differences, advantages, and limitations.

The methods analyzed are:

Zero-Noise Extrapolation (ZNE)

Clifford Regression (CR)

Objectives

Implement and understand each error mitigation method.

Apply both methods to representative quantum circuits.

Compare the results obtained with and without error mitigation.

Evaluate the efficiency and accuracy of each technique.

Methods

1. Zero-Noise Extrapolation (ZNE)

This method involves executing the quantum circuit with artificially amplified noise levels and then extrapolating the results to the zero-noise region.

2. Clifford Regression (CR)

This technique estimates the expectation values of quantum circuits by executing a set of Clifford circuits and using regression techniques to infer results with reduced bias from noise.
