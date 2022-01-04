# qiskit-HHL
A jupyter notebook with the implementation of the quantum algorithm HHL based on https://arxiv.org/abs/1802.08227 in Qiskit.

This project requires Python 3 and the following Python libraries installed:

- [NumPy 1.21.5](http://www.numpy.org/)
- [Qiskit 0.34.0](https://qiskit.org)
- [Qiskit-Aqua 0.9.5](https://qiskit.org)

All the information about the developement of the construction of quantum circuits are available in the "Documentation" folder. There is a general description in English and a detailed report in French with all the details. Since this implementations used a $5n_l+n_b+1$ qubits with $n_l \geq 2$ and $n_b \geq 1$, it is not possible to test the results on a real quantum device, at least for the moment. However, some examples are provided in the file with the implementation: "HHL-Implementation-v3.5".
