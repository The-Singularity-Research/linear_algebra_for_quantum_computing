# Linear Algebra for Quantum Computing
---
Interested in contributing to this project? 
- Reach out via email to: thesingularity.research@gmail.com
- Be sure to include "Hacking the Universe" in the subject line, so that the email doesn't get overlooked. 
- Write a paragraph or two about how you would like to contribute.
- Ask to Join the Discord server. 
- Ask to Join the Slack Channel.

This is course material for a course on linear algebra and mathematical prerequisites for quantum computing. It contains Jupyter notebooks that can be downloaded as part of the course or opened in Binder as an online interactive notebook. 

[Become a Sponsor of The Singularity](https://github.com/sponsors/The-Singularity-Research)

---

## Why Linear Algebra?
Linear algebra, the language of matrices and vectors, is the fundamental language of quantum computing and quantum information. Approaching quantum computing through linear algebra is the approach taken in the most cited textbook on the subject: ["Quantum Computation and Quantum Information"](https://www.amazon.com/gp/product/1107002176/ref=as_li_tl?ie=UTF8&camp=1789&creative=9325&creativeASIN=1107002176&linkCode=as2&tag=singularity07-20&linkId=10080ebd13739525bdfd76be97682775) by Nielsen & Chuang. This approach is also mathematically the most approachable for the complete beginner. If you have very little background in mathematics, physics, and computer programming, this approach is for you!

## What Quantum Computing is, and is not
Quantum computing is a way of processing information in a fundamentally different way from the way your laptop or smartphone processes data. The "*classical*" way of processing information is in terms of bits, binary values of zeros and ones. Quantum computing takes advantage of three different properties of quantum physics to process information. 

### Superposition
**Superposition** is the fancy word used to describe how **qubits**, the quantum version of bits, can exist in a combination of both zero and one. Qubits can also be measured in different *bases*, allowing for things like *adaptive measurement* of states, and *measurement based quantum computation*. Since qubits can be in a state that is a mixture of both zero and one, this gives them computational properties that classical bits don't have. 

### Entanglement
**Entanglement** is the word used to describe how qubits can have states that are correlated with other qubit states. Qubits interact with each other and become *entangled*, meaning their states are now statistically correlated and information about one can sometimes reveal information about the other. Multiple qubits can be entangled at once and complicated behavior can emerge. One area of research that scientists have shown much interest in is **multipartite entanglement**. This is a complex form of entanglement that exhibits highly non-classical behavior. This can be used in quantum teleportation and quantum cryptography protocols. It is also the source of a famous experiment named after Einstein, Podolsky, and Rosen, as well as John Bell's famous experiments showing that local hidden variables theories are highly unlikely to be true. 

### Interference
**Interference**, like the interference we see in waves of light, sound, and water, is exhibited by quantum computers. Quantum computers can have *constructive* (additive) interference, or they can have *destructive* interference, where waves are out of sync and cancel. This interesteing and strange behavior is often the subject of debate when discussing *wave-particle duality* and the famous *measurement problem of quantum physics*. Interference can be used to enhance "good information" and to cancel "bad information" in computations. This allows us to set up computations in clever ways and use interference as an information processing technique to solve problems. 

### Quantum Computers as ASICs
ASICs or **Application Specific Integrated Circuits** are specialized computer chips that are built for very specific kinds of computational tasks. A good example of this the GPU or *Graphics Processing Unit*, or Google's TPU (Tensor Processing Unit) which have enhanced machine learning drastically in recent years. Other examples might be the *neuromorphic computing chips* that Intel has designed. These were all designed to solve specific kinds of problems, such as enhancing machine learning tasks. Quantum computers can be thought of in a very similar way. There is a classical computer interface that delegates certain computational tasks to the quantum hardware. The quantum hardware then processes that computational task and then the classical computer receives the output data. There are many kinds of problems that quantum computers can solve. In fact, any computational task a classical computer can solve, a quantum computer can also solve. However, classical computers are still more efficient at certain things, so they will not be going anywhere. There are many algorithms and problems that can be solved exponentially faster on a quantum computer compared to all known classical methods. 

Finding out where this computational advantage comes from is one of the central tasks of quantum computing research. There is a [Quantum Algorithm Zoo](https://quantumalgorithmzoo.org/), which lists many of the known algorithms that give speedup over classical methods. Much of the focus of The Singularity is to research these various applications and algorithms and implement them in various quantum computing languages. Some applications include using Shor's algorithm to break RSA public key cryptography and other algorithms that break elliptic curve cryptography. If you are interested in discovering the inner workings of quantum algorithms and trying to understand where this quantum supremacy or advantage comes from, check out these lectures. 

### Quantikz
If you are a Donald Knuth fan and love LaTeX too, check out the TikZ library [quantikz](https://ctan.org/pkg/quantikz?lang=en). It is a LaTeX library for constructing quantum circuit diagrams. It was used for rendering many of the quantum circuit diagrams in the following lectures. 

## Lectures
Below are lectures using Jupyter notebooks that fully develop all of the basic math and programming that is needed to start solving quantum computing problems. They start out with basic linear algebra, and explain the notion of quantum gates (similar to classical logical gates in classical computers). Click on the "launch binder" button to open the interactive version. 

- Lecture 1: [What is Quantum Computing?](https://github.com/The-Singularity-Research/linear_algebra_for_quantum_computing/blob/master/Intro.ipynb)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/The-Singularity-Research/linear_algebra_for_quantum_computing/master?filepath=Intro.ipynb)
- Lecture 2: [Complex Numbers in Python](https://github.com/The-Singularity-Research/linear_algebra_for_quantum_computing/blob/master/lecture_2_complex_numbers.ipynb)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/The-Singularity-Research/linear_algebra_for_quantum_computing/master?filepath=lecture_2_complex_numbers.ipynb)
- Lecture 3: [Vectors in Python](https://github.com/The-Singularity-Research/linear_algebra_for_quantum_computing/blob/master/lecture_3_vectors.ipynb)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/The-Singularity-Research/linear_algebra_for_quantum_computing/master?filepath=lecture_3_vectors.ipynb)
- Lecture 4: [Inner Products and Unit Vectors](https://github.com/The-Singularity-Research/linear_algebra_for_quantum_computing/blob/master/lecture_4_inner_products.ipynb)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/The-Singularity-Research/linear_algebra_for_quantum_computing/master?filepath=lecture_4_inner_products.ipynb)
- Lecture 5: [The Bloch Sphere and Representing Qubits](https://github.com/The-Singularity-Research/linear_algebra_for_quantum_computing/blob/master/lecture_5_bloch_sphere.ipynb)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/The-Singularity-Research/linear_algebra_for_quantum_computing/master?filepath=lecture_5_bloch_sphere.ipynb)
- Lecture 6: [Tensor Products of Vectors in Python](https://github.com/The-Singularity-Research/linear_algebra_for_quantum_computing/blob/master/lecture_6_tensor_products.ipynb)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/The-Singularity-Research/linear_algebra_for_quantum_computing/master?filepath=lecture_6_tensor_products.ipynb)
- Lecture 7: [Preparing Basis States in PennyLane](https://github.com/The-Singularity-Research/linear_algebra_for_quantum_computing/blob/master/lecture_7_preparing_basis_states.ipynb)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/The-Singularity-Research/linear_algebra_for_quantum_computing/master?filepath=lecture_7_preparing_basis_states.ipynb)
- Lecture 8: [Matrices in Python](https://github.com/The-Singularity-Research/linear_algebra_for_quantum_computing/blob/master/lecture_8_matrices.ipynb)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/The-Singularity-Research/linear_algebra_for_quantum_computing/master?filepath=lecture_8_matrices.ipynb)
- Lecture 9: [Tensor Products of Matrices in Python](https://github.com/The-Singularity-Research/linear_algebra_for_quantum_computing/blob/master/lecture_9_tensor_product_matrices.ipynb)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/The-Singularity-Research/linear_algebra_for_quantum_computing/master?filepath=lecture_9_tensor_product_matrices.ipynb)
- Lecture 10: [Quantum Logic Gates as Matrices](https://github.com/The-Singularity-Research/linear_algebra_for_quantum_computing/blob/master/lecture_10_quantum_gates.ipynb)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/The-Singularity-Research/linear_algebra_for_quantum_computing/master?filepath=lecture_10_quantum_gates.ipynb)


