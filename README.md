# Variational-Quantum
variational algorithm design workflow, tradeoffs associated with each step, and how to use Qiskit Runtime primitives to optimize for speed and accuracy


At the heart of all variational algorithms lies the key idea of analyzing the differences between states, which are conveniently related through some well-behaved mapping (e.g., continuous, differentiable) from a set of parameters or variables — hence the name.

First, we'll explore how to construct parameterized circuits by hand. We'll use these circuits to define a variational form that represents a collection of parameterized states for our variational algorithm to explore. Then, we'll construct our ansatz by applying this variational form to our reference state.
