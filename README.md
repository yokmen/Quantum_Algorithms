# Quantum Algorithms — Learning Journey

A personal study notebook tracking my path from the fundamentals of quantum
mechanics through the major quantum algorithms and into more advanced topics
like error correction and complexity theory.

Each folder below is a personal learning module.

---

## Roadmap

### [01_basics/](01_basics/) — Foundations
The math and physics you need before touching a single gate: linear algebra,
Hilbert spaces, Dirac notation, qubits, measurement, entanglement, and the
no-cloning theorem.

### [02_gates/](02_gates/) — Quantum Gates
Single-qubit gates (Pauli, Hadamard, S, T), rotation gates, multi-qubit gates
(CNOT, CZ, SWAP, Toffoli), universal gate sets, and visualization on the Bloch
sphere.

### [03_circuits/](03_circuits/) — The Circuit Model
Building circuits from gates, classic two-qubit protocols (Bell states,
teleportation, superdense coding), circuit identities, and a hands-on
introduction to Qiskit.

### [04_early_algorithms/](04_early_algorithms/) — Early Quantum Algorithms
The warm-up algorithms that first showed quantum speedups: Deutsch,
Deutsch-Jozsa, Bernstein-Vazirani, and Simon.

### [05_grover/](05_grover/) — Grover's Search
Quantum oracles, Grover's algorithm, amplitude amplification, and a tour of
applications and variants.

### [06_shor/](06_shor/) — Shor's Factoring Algorithm
The full pipeline: Quantum Fourier Transform, quantum phase estimation,
modular exponentiation, order finding, and Shor's algorithm itself.

### [07_advanced_algorithms/](07_advanced_algorithms/) — Advanced Algorithms
HHL for linear systems, VQE, QAOA, quantum walks, quantum machine learning,
and Hamiltonian simulation.

### [08_error_correction/](08_error_correction/) — Quantum Error Correction
Noise and decoherence, the 3-qubit bit-flip code, the Shor 9-qubit code, the
stabilizer formalism, surface codes, and fault-tolerant computation.

### [09_complexity_and_theory/](09_complexity_and_theory/) — Complexity & Theory
Quantum complexity classes (BQP, QMA, ...), query and communication
complexity, and lower bounds / no-go theorems.

---

## Setup

The notebooks are designed to be run with Python 3 and a few standard
scientific / quantum libraries:

```bash
pip install numpy scipy matplotlib jupyter
pip install qiskit qiskit-aer
```
