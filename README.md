# Quantum Computing with Qiskit and IBM Quantum

Practical quantum circuits built with Qiskit and IBM Quantum Platform. No physics degree required — just curiosity!

## What's inside

- **Superposition** — a qubit in two states at the same time
- **Entanglement** — two qubits connected instantaneously
- **Grover's Algorithm** — quantum search that always finds the right answer
- **Shor's Algorithm** — the algorithm that could break modern encryption

## Results

- Superposition: `{'0': 483, '1': 517}` — ~50/50, like flipping a coin
- Entanglement: `{'00': 513, '11': 487}` — always matching, never '01' or '10'
- Grover: `{'11': 1000}` — 1000 out of 1000 correct answers

## How to run

```bash
pip install qiskit-ibm-runtime qiskit matplotlib pylatexenc
```

Create a free account at [IBM Quantum Platform](https://quantum.ibm.com), get your API key and run:

```python
from qiskit_ibm_runtime import QiskitRuntimeService
QiskitRuntimeService.save_account(channel="ibm_quantum_platform", token="YOUR_API_KEY", overwrite=True)
```

Then open any `.ipynb` notebook in Jupyter and run it!
