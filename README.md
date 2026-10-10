# Quantum Computing with Qiskit ⚛️

A hands-on collection of Jupyter notebooks exploring the fundamentals of quantum computing using **Python, Qiskit, and IBM Quantum**.

This repository contains my practical work from the **IBM Quantum Qiskit Fall Fest 2026 workshop**, conducted at Vishnu Institute of Technology, Bhimavaram, from October 8–10, 2026.

The notebooks cover quantum circuits, superposition, interference, entanglement, Grover's search algorithm, and quantum teleportation through explanations, experiments, and circuit implementations.

## 📚 Notebooks

### 1. Introduction to Qiskit
**File:** `First_notebook.ipynb`

- Create a quantum circuit using Qiskit.
- Apply the Hadamard (H) gate to a qubit.
- Measure the qubit and explore measurement outcomes.
- Understand the basic workflow of a quantum circuit.

### 2. Superposition and Interference
**File:** `superposition-with-qiskit_fallfest (1).ipynb`

- Understand quantum superposition using the quantum coin analogy.
- Explore Hadamard, NOT, and phase gates.
- Study quantum phase and constructive and destructive interference.
- Examine measurement probabilities and expectation values.
- Visualize qubit states using the Bloch sphere.

### 3. Bell's Inequality and Quantum Entanglement
**File:** `bells-inequality-with-qiskit_fallfest (1).ipynb`

- Explore quantum entanglement and correlations between qubits.
- Study Bell's inequality and hidden-variable theories.
- Build and analyze quantum circuits.
- Investigate how quantum correlations differ from classical expectations.

### 4. Grover's Search Algorithm
**File:** `grovers_fallfest.ipynb`

- Understand quantum search and amplitude amplification.
- Explore quantum oracles and the Grover operator.
- Study the quadratic query speedup of Grover's algorithm.
- Formulate search problems using Boolean constraints.
- Implement a Minesweeper example using Grover's algorithm.
- Explore circuit optimization, measurement results, and execution on quantum hardware or simulators.

### 5. Quantum Teleportation
**File:** `quantum-teleportation_fallfest.ipynb`

- Understand quantum teleportation using entangled qubits.
- Study Bell pairs, CNOT, Hadamard, X, and Z gates.
- Implement Alice's measurement and Bob's correction steps.
- Explore classical communication in quantum teleportation.
- Investigate teleportation between qubits on a quantum processor.
- Analyze circuit execution and measurement results.

## 🛠️ Tech Stack

- **Language:** Python
- **Quantum framework:** Qiskit
- **Quantum hardware and cloud services:** IBM Quantum
- **Simulation:** Qiskit Aer
- **Development environment:** Jupyter Notebook / JupyterLab
- **Numerical computing:** NumPy
- **Version control:** Git and GitHub

## ⚙️ Getting Started

### Prerequisites

- Python 3.11 recommended
- Conda or another Python environment manager
- Jupyter Notebook or JupyterLab
- Basic knowledge of Python

### 1. Clone the repository

```bash
git clone <YOUR_GITHUB_REPOSITORY_URL>
cd <YOUR_REPOSITORY_NAME>
```

Replace the placeholders with your actual GitHub repository URL and directory name.

### 2. Create a Conda environment

```bash
conda create -n qiskit-fallfest python=3.11 -y
conda activate qiskit-fallfest
```

### 3. Install the dependencies

```bash
python -m pip install "qiskit[visualization]>=2.1.0" "qiskit-ibm-runtime>=0.40.1" "qiskit-aer>=0.17.0" numpy pylatexenc jupyterlab ipykernel
```

### 4. Register the Jupyter kernel

```bash
python -m ipykernel install --user --name qiskit-fallfest --display-name "Python (Qiskit Fall Fest)"
```

### 5. Launch JupyterLab

```bash
jupyter lab
```

Open any notebook and select the **Python (Qiskit Fall Fest)** kernel.

Run the cells from top to bottom.

## ☁️ Running on IBM Quantum

Some notebooks include examples that can run on real IBM Quantum hardware using Qiskit Runtime.

1. Create an account on [IBM Quantum](https://quantum.ibm.com/).
2. Follow the [IBM Quantum setup guide](https://quantum.cloud.ibm.com/docs/guides/cloud-setup).
3. Configure your IBM Quantum credentials locally.
4. Select an available backend and execute the relevant notebook cells.

**Note:** Real quantum hardware requires valid credentials and available quantum processing time. Where supported, simulator alternatives can be used for local experimentation.

Never commit API keys, tokens, passwords, or other credentials to GitHub.

## 🧠 Key Concepts Explored

| Concept | What I explored |
|---|---|
| Qubits | The basic units of quantum information |
| Quantum gates | Hadamard, X, Z, CNOT, and phase operations |
| Superposition | Representing combinations of quantum states |
| Interference | How quantum amplitudes reinforce or cancel |
| Entanglement | Correlations between quantum systems |
| Bell's inequality | Testing quantum predictions against classical hidden-variable models |
| Grover's algorithm | Quantum search and amplitude amplification |
| Quantum teleportation | Transferring a quantum state using entanglement and classical communication |
| Measurement | Obtaining classical outcomes from quantum circuits |

## 🎯 Learning Outcomes

Through these notebooks, I explored how to:

- Build and execute quantum circuits using Qiskit.
- Understand fundamental principles of quantum mechanics through practical experiments.
- Analyze quantum measurement results and probability distributions.
- Implement introductory quantum algorithms.
- Explore the difference between classical computing and quantum computing.
- Understand the basic workflow for executing circuits on simulators and quantum hardware.

## 📂 Repository Structure

```text
quantum-computing-qiskit/
│
├── First_notebook.ipynb
├── superposition-with-qiskit_fallfest (1).ipynb
├── bells-inequality-with-qiskit_fallfest (1).ipynb
├── grovers_fallfest.ipynb
├── quantum-teleportation_fallfest.ipynb
└── README.md
```

*The structure above reflects the uploaded notebook filenames. Update the filenames in this section if you rename them in your repository.*

## 📖 References

- [IBM Quantum Learning](https://quantum.cloud.ibm.com/learning)
- [Qiskit Documentation](https://quantum.cloud.ibm.com/docs)
- [Qiskit Installation Guide](https://quantum.cloud.ibm.com/docs/guides/install-qiskit)
- [IBM Quantum Platform](https://quantum.ibm.com/)

## 🙌 Acknowledgements

Thanks to **IBM Quantum** and the organizers of **Qiskit Fall Fest 2026 at Vishnu Institute of Technology, Bhimavaram**, for the opportunity to learn and experiment with quantum computing.

---

**Learning quantum computing, one circuit at a time. ⚛️**

