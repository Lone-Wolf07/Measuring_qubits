# Measuring_qubits
A simple Qiskit program to initialize a state vector and measure it

I was reading the book *Quantum Computing for Everyone* by *Bernhardt* and as I was reading it I wanted to know if I could verify the whole concept of state vectors, how qubits are measured and how the probability of collapsing of a qubit into a |0> or |1> depends on the state vector of the qubit

Let's say for example let the qubit have the state vector 
| 0.6   |
|-------|
| 0.8   |

We can represent it in the form a0|0> + a1|1>
ie:    0.6 [ 1 ]   +   0.4 [ 0 ]
           [ 0 ]           [ 1 ]
