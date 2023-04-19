# Classical-Computation-in-Quantum-Environments

Here can be found the original document in Catalan for my final thesis. It serves as an extremely comprehensive entry point to the world of Quantum
Computation for readers of any background, giving introductions in both the required Linear Algebra and Computer Architecture. It shows a plethora of algorithms and
architectures to perform some basic arithmetic operations, and provides generalizable schemas to build more complex operations from simpler blocks, always analyzing the tradeoff between spatial and temporal costs.

The goal of this document is to serve as a guide to anyone that desires to implement a quantum algorithm that requires an execution of a numerical function on each state in superposition.

## Abstract

Modern cryptography is based on the difficulty of the factoring problem to ensure secure
communication, so the discovery of a polynomial-time algorithm to find prime factors in a quantum computer placed quantum computation in the spotlight of the scientific community.

Ever since the end of the last century, research in this field has been incessant, achieving
tremendous feats such as the creation of a quantum computer with hundreds of qubits or the
teleportation of a quantum state over more than a thousand kilometers, and it does not show
signs of stopping anytime soon. The importance of the research in this field for cryptography
practically guarantees that this model of computation will become accessible enough to be used
for purposes beyond research.

Be it research, the implementation of current quantum algorithms, or the design of hypothetical future quantum processors, it is imperative to have the ability to encode classical information in these computers and transform it into the desired result. It is common in the
literature to assume the ability of the system to apply any of these functions that transform
classical information, but it is quite rare to find a discussion about how to perform these operations in this new model of computation or a study of the effects of such functions in the temporal and spatial complexity of the overall quantum algorithm.

Many research papers have been published in the last years studying a great diversity of
methods to perform said calculations, but these are usually designed specifically for some algorithm or to fit a certain architecture.

The goal of this project is to study the state of the art in the implementation of these classical calculations in quantum systems, the compilation and comparison of the dozens of published
designs, and the modification of these to be used generally in any desired algorithm, giving all
necessary information needed to obtain a physical implementation for any of these from scratch.
Any reader will be able to obtain a quantum circuit able to perform any classical computation
in a quantum computer and will be given many options to implement every operation in order
to adapt it to the particular necessities of its system or architecture.

In this document we show many designs able to perform different arithmetic calculations on
quantum states in superposition, we give extensive guides detailing the building process of each
of them and we analyze the impact they have on the spatial and temporal complexities of the
algorithms that use them.
