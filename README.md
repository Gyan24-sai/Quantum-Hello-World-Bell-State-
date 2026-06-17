# Quantum-Hello-World-Bell-State-
Quantum (Bell State) with qiskit
This project demonstrates one of the most important concepts in quantum computing: quantum entanglement. Using the Qiskit framework, a quantum circuit is created with two qubits. A Hadamard gate is first applied to the first qubit to place it into a state of superposition. Then, a Controlled-NOT (CNOT) gate is applied to entangle the two qubits.

After entanglement is created, both qubits are measured and the circuit is simulated using Qiskit's Aer Simulator. The measurement results show that the two qubits always produce correlated outcomes, typically resulting in approximately 50% of the measurements being 00 and 50% being 11.
Working Principle
Step 1: Create Two Qubits

Initially, both qubits are in the state:

∣00⟩
Step 2: Apply Hadamard Gate

The Hadamard gate transforms qubit 0 into:

2
	​

∣0⟩+∣1⟩
	​


The system becomes:

2
	​

∣00⟩+∣10⟩
	​

Step 3: Apply CNOT Gate

The CNOT gate flips qubit 1 whenever qubit 0 is 1:

2
	​

∣00⟩+∣11⟩
	​


This state is called a Bell State, one of the simplest examples of quantum entanglement.

Step 4: Measure the Qubits

When measured:

About 50% of the time → 00
About 50% of the time → 11

The outcomes 01 and 10 ideally never occur.
