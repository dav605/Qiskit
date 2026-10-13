# Quantum Computing with Qiskit

A beginner-friendly collection of Qiskit notebooks for learning the fundamentals of quantum computing.
This repository introduces quantum circuits, single-qubit gates, multi-qubit gates, circuit drawing, Qiskit's little-endian qubit ordering, and running a first simulation through short, hands-on Jupyter notebooks, along with a practice set to test your understanding.
No prior quantum computing experience is required, only a basic familiarity with Python.

## 📚 Contents

| Notebook | Description |
|----------|-------------|
| Quantum_circuit.ipynb | Introduction to quantum circuits and their basic components |
| Single_qubit_gates.ipynb | Introduction to single-qubit gates and their effect on quantum states |
| Multiple_qubit_gate.ipynb | Introduction to multi-qubit gates and how they act on more than one qubit |
| Drawing_circuits.ipynb | Introduction to drawing and visualizing quantum circuits in Qiskit |
| Little_Endian.ipynb | Introduction to little-endian qubit ordering in Qiskit |
| Practice_set1.ipynb | Practice problems to review the concepts covered in the earlier notebooks |
| First_simulation.ipynb | Introduction to running a quantum circuit simulation in Qiskit |

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

**Little_Endian.ipynb**
- What little-endian ordering means in Qiskit
- How it affects the order of qubits and measurement results

**Practice_set1.ipynb**
- Practice problems to reinforce the concepts from the notebooks above

**First_simulation.ipynb**
- Running a quantum circuit on a simulator in Qiskit

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

We recommend following the notebooks in this order: `Quantum_circuit.ipynb`, then `Single_qubit_gates.ipynb`, `Multiple_qubit_gate.ipynb`, `Drawing_circuits.ipynb`, `Little_Endian.ipynb`, `Practice_set1.ipynb`, and `First_simulation.ipynb`.
