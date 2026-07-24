# QAOA Implementation

## Project Overview

This project explores the **Quantum Approximate Optimization Algorithm (QAOA)** for solving the Max-Cut optimization problem. QAOA is a hybrid quantum-classical algorithm that combines parameterized quantum circuits with classical optimization to approximate solutions for combinatorial optimization problems.

The project investigates how circuit depth and quantum noise affect QAOA performance through a series of experiments, implementations, and analyses.

---

## Objectives and Goals

The objectives of this project were to:

- Implement the Quantum Approximate Optimization Algorithm (QAOA).
- Solve the Max-Cut optimization problem using QAOA.
- Compare noisy and noiseless quantum simulations.
- Analyze the effect of circuit depth on optimization performance.
- Compare QAOA with the classical Goemans-Williamson approximation algorithm.

---

## Methodology

The project was completed using a collection of Jupyter notebooks that explore different aspects of QAOA.

The workflow includes:

- Constructing QAOA quantum circuits
- Implementing the Max-Cut optimization problem
- Running noiseless quantum simulations
- Evaluating noisy quantum simulations
- Comparing multiple circuit depths
- Benchmarking against the Goemans-Williamson classical algorithm

---

## Results and Key Findings

The experiments demonstrate how circuit depth and quantum noise influence QAOA performance.

Key findings include:

- Higher circuit depths can improve solution quality but require greater computational resources.
- Quantum noise reduces optimization performance compared to noiseless simulations.
- The comparison with the Goemans-Williamson algorithm provides a useful classical benchmark for evaluating QAOA.

Detailed analysis is available in the final report included in this repository.

---

## Repository Contents

| File | Description |
|------|-------------|
| `qoao-implementation-final.ipynb` | Main QAOA implementation |
| `Depth-comparision-no-noise.ipynb` | Circuit depth comparison without noise |
| `FINAL-version-5-and-10-nodes-Depth-comparision-with-noise-with-noiseless-results.ipynb` | 5 and 10 node experiments |
| `FINAL-version-20-nodes-working-Depth-comparision-with-noise-with-noiseless-results.ipynb` | 20 node experiments |
| `Noiseless-vs-noise-for-a-depth.ipynb` | Noise comparison analysis |
| `Goemans-Williamson-algorithm-final.ipynb` | Classical benchmark implementation |
| `Final_QAOA_to_Max_Cut_Report.pdf` | Final project report |
| `QAOA-presentation_compressed.pdf` | Project presentation |
| `qaoa-circuit-tracing-final.pdf` | Circuit tracing documentation |

---

## Technologies Used

- Python
- Jupyter Notebook
- Qiskit
- NumPy
- Matplotlib

---

## Installation

Clone the repository:

```bash
git clone https://github.com/annasehgal/qaoa-implementation.git
cd qaoa-implementation
```

Install the required Python packages:

```bash
pip install qiskit numpy matplotlib jupyter
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open any notebook to reproduce the experiments.

---

## Future Improvements

Possible future work includes:

- Testing larger graph sizes
- Running experiments on real quantum hardware
- Comparing additional variational quantum algorithms
- Exploring alternative classical optimizers
- Investigating improved noise mitigation techniques

---

## Individual Contributions

This project was completed independently.

My contributions included:

- Implementing the QAOA algorithm
- Designing and conducting the experiments
- Comparing noisy and noiseless simulations
- Evaluating circuit depth performance
- Comparing QAOA with the Goemans-Williamson algorithm
- Preparing the report, presentation, and circuit analysis

---

## License

This project is licensed under the MIT License.
