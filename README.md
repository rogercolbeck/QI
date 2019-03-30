# QI
Quantum information Mathematica package.

This is a Mathematica package containing commands for implementing functionalities commonly needed in quantum information processing.  These are useful for doing theoretical computations on quantum information protocols.  For instance, one could easily use it to work through the teleportation protocol with a perfect Bell state, and then to see what happens to the fidelity of the output state when a noisy Bell state is shared instead.  The ability to choose random states etc. can be useful for finding counterexamples to particular statements, or for gaining confidence in a statement prior to proving it.  The package may form a useful starting point for constructing others, e.g., it has been used for a quantum compiler (see www-users.york.ac.uk/~rc973/UniversalQCompiler.html ).

As examples, it includes functionality for
- taking tensor products
- computing partial traces
- reordering systems within a tensor product
- Schmidt decomposition
- computing von Neumann entropies or mutual informations
- generating random states, unitaries, measurements or channels.

There is also a command for Fourier Motzkin elimination.

To use the package, open the file QI.m in Mathematica and press "Run All Code".

A short manual, examples notebook and useful palette for entering symbols can be found at www-users.york.ac.uk/~rc973/QI_package.html.
