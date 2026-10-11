# ⚛️ Qiskit Fall Fest 2026 — Quantum Computing Challenges

A collection of hands-on quantum computing challenges completed using **Qiskit and Python** as part of Qiskit Fall Fest 2026 at Vishnu Institute of Technology.

## 📌 About the Project

This repository contains practical experiments exploring quantum circuits, measurement probabilities, quantum correlations, and the effects of quantum gates on qubit states.

Each challenge is implemented in Jupyter Notebook, executed using Qiskit, and documented with measurement results, histograms, and explanations.

## 🧪 Challenges Completed

### Challenge 1: Single-Qubit Quantum Circuits
- Create and simulate single-qubit quantum circuits.
- Apply quantum gates and observe their effects.
- Measure qubit states and analyze measurement outcomes.

### Challenge 2: Make the Quantum Coin Biased
- Create a single-qubit circuit with unequal measurement probabilities.
- Use the `RY` rotation gate to control the probability of measuring `0` or `1`.
- Execute each circuit for 100 shots.
- Visualize and compare the results using histograms.

**Key learning:** Quantum gates can change measurement probabilities by changing the qubit's quantum state.

### Challenge 3: Can You Change the Correlation?
- Construct a two-qubit Bell-state circuit.
- Measure the correlated outcomes of the original circuit.
- Add an `X` gate to one qubit to modify the measurement relationship.
- Execute both circuits for 100 shots.
- Compare the measurement distributions using histograms.

**Key learning:** Applying an `X` gate to one qubit changes the dominant outcomes from `00` and `11` to `01` and `10`.

### Challenge 4: Quantum Correlation Switch
- Build a circuit that produces correlated measurement outcomes.
- Modify the circuit to produce opposite measurement outcomes.
- Run both experiments for 100 shots.
- Compare the histograms and explain the change in correlation.

**Key learning:** A single-qubit gate can change the relationship between the measurement outcomes of an entangled pair.

## 🛠️ Tech Stack

- **Language:** Python
- **Framework:** Qiskit
- **Simulation:** Qiskit Aer
- **Environment:** Jupyter Notebook
- **Visualization:** Matplotlib and Qiskit Histogram Visualization

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd YOUR_REPOSITORY_NAME
```

Replace the placeholders with your actual GitHub repository URL and folder name.

### 2. Install the required libraries

Run this command in your terminal:

```bash
pip install qiskit qiskit-aer matplotlib jupyter
```

### 3. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the challenge notebook and execute the cells in order.

## 📊 Experiments and Results

The experiments use simulated quantum circuits with 100 shots per circuit.

| Experiment | Expected Measurement Outcomes |
|---|---|
| Challenge 2 — Circuit A | More `0` outcomes |
| Challenge 2 — Circuit B | More `1` outcomes |
| Challenge 3 — Original Bell circuit | `00` and `11` |
| Challenge 3 — Modified circuit | `01` and `10` |
| Challenge 4 — Correlated circuit | `00` and `11` |
| Challenge 4 — Opposite circuit | `01` and `10` |

The observed counts may vary because quantum measurements are probabilistic. These experiments use a simulator, not real IBM Quantum hardware.

## 🎯 Key Learnings

- Understanding qubits and quantum measurement.
- Building quantum circuits using Qiskit.
- Applying Hadamard, CNOT, X, and RY gates.
- Controlling single-qubit measurement probabilities.
- Creating and modifying Bell states.
- Understanding correlated and opposite measurement outcomes.
- Executing quantum circuits with multiple shots.
- Visualizing and interpreting measurement results.

## 🚀 Future Improvements

- Run selected circuits on real IBM Quantum hardware.
- Compare simulated and hardware measurement results.
- Explore additional quantum gates and entangled states.
- Investigate how noise affects measurement distributions.

## 🙌 Acknowledgment

Completed as part of **Qiskit Fall Fest 2026** at Vishnu Institute of Technology.

Thanks to the organizers and speakers for introducing practical quantum computing concepts through hands-on challenges.

---

**Author:** Syam Vadarevula

**Topics:** `Quantum Computing` · `Qiskit` · `Python` · `Quantum Circuits` · `Quantum Entanglement` · `Jupyter Notebook`
