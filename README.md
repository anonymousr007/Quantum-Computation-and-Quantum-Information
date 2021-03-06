# Quantum Computation and Quantum Information

## Table of Contents

### Part I Fundamental concepts

- 1 Introduction and overview
  - 1.1 Global perspectives
    - 1.1.1 History of quantum computation and quantum information
    - 1.1.2 Future directions
  - 1.2 Quantum bits
    - 1.2.1 Multiple qubits
  - 1.3 Quantum computation
    - 1.3.1 Single qubit gates
    - 1.3.2 Multiple qubit gates
    - 1.3.3 Measurements in bases other than the computational basis
    - 1.3.4 Quantum circuits
    - 1.3.5 Qubit copying circuit?
    - 1.3.6 Example: Bell states
    - 1.3.7 Example: quantum teleportation
  - 1.4 Quantum algorithms
    - 1.4.1 Classical computations on a quantum computer
    - 1.4.2 Quantum parallelism
    - 1.4.3 Deutsch’s algorithm
    - 1.4.4 The Deutsch–Jozsa algorithm
    - 1.4.5 Quantum algorithms summarized
  - 1.5 Experimental quantum information processing
    - 1.5.1 The Stern–Gerlach experiment
    - 1.5.2 Prospects for practical quantum information processing
  - 1.6 Quantum information
    - 1.6.1 Quantum information theory: example problems
    - 1.6.2 Quantum information in a wider context
- 2 Introduction to quantum mechanics
  - 2.1 Linear algebra
    - 2.1.1 Bases and linear independence
    - 2.1.2 Linear operators and matrices
    - 2.1.3 The Pauli matrices
    - 2.1.4 Inner products
    - 2.1.5 Eigenvectors and eigenvalues
    - 2.1.6 Adjoints and Hermitian operators
    - 2.1.7 Tensor products
    - 2.1.8 Operator functions
    - 2.1.9 The commutator and anti-commutator
    - 2.1.10 The polar and singular value decompositions
  - 2.2 The postulates of quantum mechanics
    - 2.2.1 State space
    - 2.2.2 Evolution
    - 2.2.3 Quantum measurement
    - 2.2.4 Distinguishing quantum states
    - 2.2.5 Projective measurements
    - 2.2.6 POVM measurements
    - 2.2.7 Phase
    - 2.2.8 Composite systems
    - 2.2.9 Quantum mechanics: a global view
  - 2.3 Application: superdense coding
  - 2.4 The density operator
    - 2.4.1 Ensembles of quantum states
    - 2.4.2 General properties of the density operator
    - 2.4.3 The reduced density operator
  - 2.5 The Schmidt decomposition and purifications
  - 2.6 EPR and the Bell inequality
- 3 Introduction to computer science
  - 3.1 Models for computation
    - 3.1.1 Turing machines
    - 3.1.2 Circuits
  - 3.2 The analysis of computational problems
    - 3.2.1 How to quantify computational resources
    - 3.2.2 Computational complexity
    - 3.2.3 Decision problems and the complexity classes P and NP
    - 3.2.4 A plethora of complexity classes
    - 3.2.5 Energy and computation
  - 3.3 Perspectives on computer science

### Part II Quantum computation

- 4 Quantum circuits
  - 4.1 Quantum algorithms
  - 4.2 Single qubit operations
  - 4.3 Controlled operations
  - 4.4 Measurement
  - 4.5 Universal quantum gates
    - 4.5.1 Two-level unitary gates are universal
    - 4.5.2 Single qubit and CNOT gates are universal
    - 4.5.3 A discrete set of universal operations
    - 4.5.4 Approximating arbitrary unitary gates is generically hard
    - 4.5.5 Quantum computational complexity
  - 4.6 Summary of the quantum circuit model of computation
  - 4.7 Simulation of quantum systems
    - 4.7.1 Simulation in action
    - 4.7.2 The quantum simulation algorithm
    - 4.7.3 An illustrative example
    - 4.7.4 Perspectives on quantum simulation 
- 5 The quantum Fourier transform and its applications
  - 5.1 The quantum Fourier transform
  - 5.2 Phase estimation
    - 5.2.1 Performance and requirements
  - 5.3 Applications: order-finding and factoring
    - 5.3.1 Application: order-finding
    - 5.3.2 Application: factoring
  - 5.4 General applications of the quantum Fourier transform
    - 5.4.1 Period-finding
    - 5.4.2 Discrete logarithms
    - 5.4.3 The hidden subgroup problem
    - 5.4.4 Other quantum algorithms?
- 6 Quantum search algorithms
  - 6.1 The quantum search algorithm
    - 6.1.1 The oracle
    - 6.1.2 The procedure
    - 6.1.3 Geometric visualization
    - 6.1.4 Performance
  - 6.2 Quantum search as a quantum simulation
  - 6.3 Quantum counting
  - 6.4 Speeding up the solution of NP-complete problems
  - 6.5 Quantum search of an unstructured database
  - 6.6 Optimality of the search algorithm
  - 6.7 Black box algorithm limits
- 7 Quantum computers: physical realization
  - 7.1 Guiding principles
  - 7.2 Conditions for quantum computation
    - 7.2.1 Representation of quantum information
    - 7.2.2 Performance of unitary transformations
    - 7.2.3 Preparation of fiducial initial states
    - 7.2.4 Measurement of output result 282
  - 7.3 Harmonic oscillator quantum computer
    - 7.3.1 Physical apparatus
    - 7.3.2 The Hamiltonian
    - 7.3.3 Quantum computation
    - 7.3.4 Drawbacks
  - 7.4 Optical photon quantum computer
    - 7.4.1 Physical apparatus
    - 7.4.2 Quantum computation
    - 7.4.3 Drawbacks
  - 7.5 Optical cavity quantum electrodynamics
    - 7.5.1 Physical apparatus
    - 7.5.2 The Hamiltonian
    - 7.5.3 Single-photon single-atom absorption and refraction
    - 7.5.4 Quantum computation
  - 7.6 Ion traps
    - 7.6.1 Physical apparatus
    - 7.6.2 The Hamiltonian
    - 7.6.3 Quantum computation
    - 7.6.4 Experiment
  - 7.7 Nuclear magnetic resonance
    - 7.7.1 Physical apparatus
    - 7.7.2 The Hamiltonian
    - 7.7.3 Quantum computation
    - 7.7.4 Experiment
  - 7.8 Other implementation schemes

### Part III Quantum information

- 8 Quantum noise and quantum operations
  - 8.1 Classical noise and Markov processes
  - 8.2 Quantum operations
    - 8.2.1 Overview
    - 8.2.2 Environments and quantum operations
    - 8.2.3 Operator-sum representation
    - 8.2.4 Axiomatic approach to quantum operations
  - 8.3 Examples of quantum noise and quantum operations
    - 8.3.1 Trace and partial trace
    - 8.3.2 Geometric picture of single qubit quantum operations
    - 8.3.3 Bit flip and phase flip channels
    - 8.3.4 Depolarizing channel
    - 8.3.5 Amplitude damping
    - 8.3.6 Phase damping
  - 8.4 Applications of quantum operations
    - 8.4.1 Master equations
    - 8.4.2 Quantum process tomography
  - 8.5 Limitations of the quantum operations formalism
- 9 Distance measures for quantum information
  - 9.1 Distance measures for classical information
  - 9.2 How close are two quantum states?
    - 9.2.1 Trace distance
    - 9.2.2 Fidelity
    - 9.2.3 Relationships between distance measures
  - 9.3 How well does a quantum channel preserve information?
- 10 Quantum error-correction
  - 10.1 Introduction
    - 10.1.1 The three qubit bit flip code
    - 10.1.2 Three qubit phase flip code
  - 10.2 The Shor code
  - 10.3 Theory of quantum error-correction
    - 10.3.1 Discretization of the errors
    - 10.3.2 Independent error models
    - 10.3.3 Degenerate codes
    - 10.3.4 The quantum Hamming bound
  - 10.4 Constructing quantum codes
    - 10.4.1 Classical linear codes
    - 10.4.2 Calderbank–Shor–Steane codes
  - 10.5 Stabilizer codes
    - 10.5.1 The stabilizer formalism
    - 10.5.2 Unitary gates and the stabilizer formalism
    - 10.5.3 Measurement in the stabilizer formalism
    - 10.5.4 The Gottesman–Knill theorem
    - 10.5.5 Stabilizer code constructions
    - 10.5.6 Examples
    - 10.5.7 Standard form for a stabilizer code
    - 10.5.8 Quantum circuits for encoding, decoding, and correction
  - 10.6 Fault-tolerant quantum computation
    - 10.6.1 Fault-tolerance: the big picture
    - 10.6.2 Fault-tolerant quantum logic
    - 10.6.3 Fault-tolerant measurement
    - 10.6.4 Elements of resilient quantum computation
- 11 Entropy and information
  - 11.1 Shannon entropy
  - 11.2 Basic properties of entropy
    - 11.2.1 The binary entropy
    - 11.2.2 The relative entropy
    - 11.2.3 Conditional entropy and mutual information
    - 11.2.4 The data processing inequality
  - 11.3 Von Neumann entropy
    - 11.3.1 Quantum relative entrop
    - 11.3.2 Basic properties of entropy
    - 11.3.3 Measurements and entropy
    - 11.3.4 Subadditivity
    - 11.3.5 Concavity of the entropy
    - 11.3.6 The entropy of a mixture of quantum states
  - 11.4 Strong subadditivity
    - 11.4.1 Proof of strong subadditivity
    - 11.4.2 Strong subadditivity: elementary applications
- 12 Quantum information theory
  - 12.1 Distinguishing quantum states and the accessible information
    - 12.1.1 The Holevo bound
    - 12.1.2 Example applications of the Holevo bound
  - 12.2 Data compression
    - 12.2.1 Shannon’s noiseless channel coding theorem
    - 12.2.2 Schumacher’s quantum noiseless channel coding theorem
  - 12.3 Classical information over noisy quantum channels
    - 12.3.1 Communication over noisy classical channels
    - 12.3.2 Communication over noisy quantum channels
  - 12.4 Quantum information over noisy quantum channels
    - 12.4.1 Entropy exchange and the quantum Fano inequality
    - 12.4.2 The quantum data processing inequality
    - 12.4.3 Quantum Singleton bound
    - 12.4.4 Quantum error-correction, refrigeration and Maxwell’s demon
  - 12.5 Entanglement as a physical resource
    - 12.5.1 Transforming bi-partite pure state entanglement
    - 12.5.2 Entanglement distillation and dilution
    - 12.5.3 Entanglement distillation and quantum error-correction
  - 12.6 Quantum cryptography
    - 12.6.1 Private key cryptography
    - 12.6.2 Privacy amplification and information reconciliation
    - 12.6.3 Quantum key distribution
    - 12.6.4 Privacy and coherent information
    - 12.6.5 The security of quantum key distribution

### Appendices

- Appendix 1: Notes on basic probability theory
- Appendix 2: Group theory
  - A2.1 Basic definitions
    - A2.1.1 Generators
    - A2.1.2 Cyclic groups
    - A2.1.3 Cosets
  - A2.2 Representations
    - A2.2.1 Equivalence and reducibility
    - A2.2.2 Orthogonality
    - A2.2.3 The regular representation
  - A2.3 Fourier transforms
- Appendix 3: The Solovay--Kitaev theorem
- Appendix 4: Number theory
  - A4.1 Fundamentals
  - A4.2 Modular arithmetic and Euclid’s algorithm
  - A4.3 Reduction of factoring to order-finding
  - A4.4 Continued fractions
- Appendix 5: Public key cryptography and the RSA cryptosystem 640
- Appendix 6: Proof of Lieb’s theorem















































































