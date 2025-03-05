# COA_Quant
This project implements a quantum-based coin flip game using Qiskit, IBM’s quantum computing framework. Unlike classical random number generation, which relies on pseudo-random algorithms, this project uses quantum superposition to generate truly random results.

The program simulates flipping a quantum coin by applying a Hadamard gate to a qubit, putting it into an equal superposition of |0⟩ (Heads) and |1⟩ (Tails). The qubit is then measured, collapsing into one of the two states with equal probability (50/50). The game runs for a predefined number of rounds, counting how many times the coin lands on Heads.

Features:
Uses Qiskit's qasm_simulator to simulate quantum randomness
Applies a Hadamard gate to create a fair 50-50 probability distribution
Simulates multiple rounds of coin flips
Displays the results of each round along with the final count of Heads
Technologies Used:
Python
Qiskit (Quantum Computing Library)
Use Cases:
Demonstrating the principles of quantum superposition and measurement
Learning about quantum computing through a simple interactive game
Comparing classical vs. quantum randomness
This project serves as an educational tool to understand basic quantum mechanics and Qiskit programming while creating an engaging coin-flipping game.
