# Quantum Computing with Qiskit

A beginner-friendly collection of Qiskit notebooks for learning the fundamentals of quantum computing.
This repository introduces quantum circuits, single-qubit gates, multi-qubit gates, and circuit drawing through short, hands-on Jupyter notebooks.
No prior quantum computing experience is required, only a basic familiarity with Python.

## 📚 Contents

| Notebook | Description |
|----------|-------------|
| Quantum_circuit.ipynb | Introduction to quantum circuits and their basic components |
| Single_qubit_gates.ipynb | Introduction to single-qubit gates and their effect on quantum states |
| Multiple_qubit_gate.ipynb | Introduction to multi-qubit gates and how they act on more than one qubit |
| Drawing_circuits.ipynb | Introduction to drawing and visualizing quantum circuits in Qiskit |

### What you'll learn

**Quantum_circuit.ipynb**
- Creating a `QuantumCircuit`
- Working with qubits and classical bits
- Adding basic operations to a circuit
- Visualizing circuits

**Single_qubit_gates.ipynb**
- What single-qubit gates are
- How gates change a qubit's state
- Inspecting quantum states using statevectors in Qiskit

**Multiple_qubit_gate.ipynb**
- What multi-qubit gates are
- How gates act on more than one qubit in a circuit

**Drawing_circuits.ipynb**
- Drawing quantum circuits in Qiskit
- Reading and understanding circuit diagrams

## 🚀 Getting Started

The notebooks use **Python**, **Qiskit**, and **Jupyter Notebook**.

### Installation

```bash
pip install qiskit
pip install jupyter
```

> **Tip:** Circuit drawings and state plots may also need extra visualization packages. If you see an error when drawing a circuit, install them with:
>
> ```bash
> pip install matplotlib pylatexenc
> ```

### Running the notebooks

1. Clone this repository:

   ```bash
   git clone https://github.com/dav605/Qiskit.git
   cd Qiskit
   ```

2. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

3. Open a notebook from the file browser and run the cells in order.

We recommend following the notebooks in this order: `Quantum_circuit.ipynb`, then `Single_qubit_gates.ipynb`, `Multiple_qubit_gate.ipynb`, and `Drawing_circuits.ipynb`.
