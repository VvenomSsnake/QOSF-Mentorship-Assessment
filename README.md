# QOSF-Mentorship-Assessment

## Question

The goal here is to implement simple quantum circuit simulator. It is expected that simulator can perform following:

- initialize state

- read program, and for each gate:

  - calculate matrix operator
  - apply operator (modify state)
- perform multi-shot measurement of all qubits using weighted random technique

## Solution

My solution uses numpy and sympy in order to create a generalized program for creating Quantum Circuits and custom Quantum Gates (both unitaries and controlled unitaries). The solution also allows the creation of parametric gates, using sympy for allowing string inputs and handling them symbolically. The string inputs can later be bound to a numeric value using a function, in order to perform measurements on the parametric circuit.
