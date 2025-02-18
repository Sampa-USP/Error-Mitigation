# Error Mitigation in Quantum Computing

This repository is associated with the article available on arXiv at [arXiv:0000.00000](https://arxiv.org/abs/0000.00000) and aims to explore and analyze error mitigation techniques in quantum computing systems, comparing two distinct methods. Error mitigation is a crucial field for improving the accuracy of results obtained from noisy quantum hardware.

## Project Description

Current quantum computing systems suffer from noise and errors in circuits, which hinder the accuracy of their results. This repository investigates and implements two popular error mitigation methods, seeking to understand their differences, advantages, and limitations.

The methods analyzed are:

1. **Zero-Noise Extrapolation (ZNE)**
2. **Clifford Regression (CR)**

## Objectives

- Implement and understand each error mitigation method.
- Apply both methods to representative quantum circuits.
- Compare the results obtained with and without error mitigation.
- Evaluate the efficiency and accuracy of each technique.

## Methods

### 1. Zero-Noise Extrapolation (ZNE)
This method involves executing the quantum circuit with artificially amplified noise levels and then extrapolating the results to the zero-noise region.

### 2. Clifford Regression (CR)
This technique estimates the expectation values of quantum circuits by executing a set of Clifford circuits and using regression techniques to infer results with reduced bias from noise.

## Tools and Libraries Used

- AWS Braket
- Qiskit
- IBM Quantum
- NumPy
- Matplotlib

## Repository Structure

```
📦 error-mitigation-quantum
├── README.md
├── zne_zero_noise_extrapolation/
│   └── zne_implementation.ipynb
├── cr_clifford_regression/
│   └── cr_implementation.ipynb
└── results_comparison/
    └── comparative_analysis.ipynb
```

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/error-mitigation-quantum.git
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Navigate to the directory of the desired method and run the notebook:

```bash
jupyter notebook zne_implementation.ipynb
```

Or:

```bash
jupyter notebook cr_implementation.ipynb
```

4. To see the comparison between both methods:

```bash
jupyter notebook comparative_analysis.ipynb
```

## Citation

If you use this repository in your research or publication, please cite it as:

```
@misc{your-username2025error-mitigation,
  author       = {Your Name},
  title        = {Error Mitigation in Quantum Computing},
  year         = {2025},
  publisher    = {GitHub},
  journal      = {GitHub repository},
  howpublished = {\url{https://github.com/Sampa-UDP/quantum-error-mitigation}}
}
```

## License

This project is licensed under the [MIT License](LICENSE). The license applies to the code and materials provided in this repository.

---

Developed by:
- Nara Ávila Moraes
- Alexsandro Kirch
- Alberto Torres Riera Junior
- Angelina Mascarini
- Gabriel Fabian Tortoretto
- Lucas Alves Leite

