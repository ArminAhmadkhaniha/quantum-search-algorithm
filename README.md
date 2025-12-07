# Performance Analysis of Hardware-Efficient Quantum Search Algorithm


[![DOI](https://img.shields.io/badge/DOI-10.1007%2Fs10773--023--05424--7-blue)](https://link.springer.com/article/10.1007/s10773-023-05424-7)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![MATLAB](https://img.shields.io/badge/MATLAB-2023a-orange)](https://www.mathworks.com/)

## Overview

This repository contains the code and analysis for the paper **"Performance Analysis of the Hardware-Efficient Quantum Search Algorithm"**, published in the *International Journal of Theoretical Physics*.

We explore a hardware-efficient quantum search algorithm optimized for the Noisy Intermediate-Scale Quantum (NISQ) era. Unlike standard Grover's algorithm, which suffers from depth limitations on current hardware, our approach optimizes circuit depth to mitigate errors.

### Key Contributions
* **Hardware Efficiency:** Optimized circuit depth to reduce susceptibility to gate errors.
* **Noise Analysis:** Comprehensive simulation of **Phase-Damping (PD)** and **Amplitude-Damping (AD)** noise effects.
* **Comparative Study:** Benchmarking against standard Grover's algorithm and other counterparts.
* **Validation:** Cross-validation of Qiskit (Python) results using MATLAB simulations.

## Repository Structure

* `python_src/`: Contains the Qiskit implementation of the hardware-efficient search algorithm.
* `matlab_src/`: Contains MATLAB scripts used for mathematical validation and detailed noise analysis (PD/AD channels).

## Getting Started

### Python (Algorithm Implementation)
To install dependecies:
```bash
pip install -r requirements.txt

```

## Citation
url  = {[https://link.springer.com/article/10.1007/s10773-023-05424-7](https://link.springer.com/article/10.1007/s10773-023-05424-7)}
