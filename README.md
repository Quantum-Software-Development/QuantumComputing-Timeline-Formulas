
 \[[🇧🇷 Português](README.pt_BR.md)\] \[**[🇺🇸 English](README.md)**\]

 <br>


# <p align="center"> 🇶 **Quantum Computing Timeline with Key Contributions and Formulas**

<!--

<br><br>

![1728778232985](https://github.com/user-attachments/assets/0f466bc0-fb40-4cad-ba3d-4e8494745a53)

<br><br>
-->

<!--### <p align="center">  <img src="https://github.githubassets.com/images/icons/emoji/octocat.png" width="46">  -->
### <p align="center"> [![Sponsor Quantum Software Development](https://img.shields.io/badge/Sponsor-Quantum%20Software%20Development-brightgreen?logo=GitHub)](https://github.com/sponsors/Quantum-Software-Development)


 <br><br>


## <p align="center"> [About This Repository]()

This repository is designed to serve as an educational resource, showcasing the progression of quantum computing, key contributions, and foundational formulas. Contributions and discussions are encouraged to expand on these materials and foster collaboration in the field of quantum computing.
Feel free to explore, contribute, and share your insights!


<br><br>

## <p align="center">  Early 20th Century – [Foundations of Quantum Mechanics]()

<br>


1. [Max Planck]() **(1900)** <br>
 ────────────── 
   * Founder of quantum theory by introducing the concept of energy quantization.

   Formula for quantized energy:
   
   $\huge \color{DeepSkyBlue} E = h \cdot f$

   Where:  
   - $\large \color{DeepSkyBlue} E$ is the energy of the photon.  
   - $\large \color{DeepSkyBlue} h$ is Planck's constant ($6.626 \times 10^{-34} \, \text{J·s}$).  
   - $\large \color{DeepSkyBlue} f$ is the radiation frequency.

#
  
2. **Albert Einstein (1905)**  
   * Explanation of the photoelectric effect, which introduced the concept of photons.

   Formula for the photoelectric effect:  
   $\huge \color{DeepSkyBlue} E_{photon} = h \cdot f = W + K$

   Where:  
   - $\large \color{DeepSkyBlue} W$ is the work function (minimum energy required to remove an electron).  
   - $\large \color{DeepSkyBlue} K$ is the kinetic energy of the ejected electron.

#

3. **Niels Bohr (1913)**  
   * Bohr's atomic model with quantized energy levels.

   Formula for the energy levels of the electron in the hydrogen atom:  
   $\huge \color{DeepSkyBlue} E_n = -\frac{13.6 \, \text{eV}}{n^2}$

   Where:  
   - $\large \color{DeepSkyBlue} E_n$ is the energy of level $n$.  
   - $\large \color{DeepSkyBlue} n$ is the principal quantum number.
  
#   

4. **Erwin Schrödinger (1926)**  
   * Schrödinger's equation, the foundation of wave mechanics.

   Time-dependent form of Schrödinger's equation:  
   $\huge \color{DeepSkyBlue} i\hbar \frac{\partial}{\partial t} \psi(r, t) = \hat{H} \psi(r, t)$  

   Where:  
   - $\large \color{DeepSkyBlue} \psi(r, t)$ is the wave function of the system.  
   - $\large \color{DeepSkyBlue} \hat{H}$ is the Hamiltonian operator.  
   - $\large \color{DeepSkyBlue} \hbar$ is the reduced Planck constant.
  
 #

5. **Werner Heisenberg (1927)**  
   * Uncertainty Principle, central to quantum physics.

   Formula for the Uncertainty Principle:  
   $\huge \color{DeepSkyBlue} \Delta x \cdot \Delta p \geq \frac{\hbar}{2}$

   Where:  
   - $\large \color{DeepSkyBlue} \Delta x$ is the uncertainty in position.  
   - $\large \color{DeepSkyBlue} \Delta p$ is the uncertainty in momentum.
  
 #

6. **Paul Dirac (1928)**  
   * Developed the relativistic theory of the electron and contributed to quantum mechanics.

   Dirac equation for relativistic particles:  
   $\huge \color{DeepSkyBlue} (i\hbar \gamma^\mu \partial_\mu - mc)\psi = 0$

   Where:  
   - $\large \color{DeepSkyBlue} \gamma^\mu$ are the Dirac matrices.  
   - $\large \color{DeepSkyBlue} m$ is the mass of the particle.  


<br><br>

## <p align="center">  Mid-20th Century – [Foundation for Quantum Information]()

<br>

7. **John von Neumann (1932)**  
   * Formalized the mathematics of quantum mechanics and introduced operator theory.

   Formula for the density matrix in Hilbert space:  
   $\huge \color{DeepSkyBlue} \rho = \sum_i p_i |\psi_i\rangle \langle\psi_i|$

   Where:  
   - $\large \color{DeepSkyBlue} \rho$ is the density matrix.  
   - $\large \color{DeepSkyBlue} p_i$ are the probabilities of the quantum states.  
   - $\large \color{DeepSkyBlue} |\psi_i\rangle$ are the individual quantum states.
  
#

8. **Claude Shannon (1948)**  
   * Although Shannon is primarily known for classical information theory, his definition of entropy plays a crucial role in both quantum computing and quantum information theory. Shannon's entropy measures the uncertainty of a random variable, and this concept extends to quantum systems, forming the foundation for quantum information theory.  

    Formula for Shannon Entropy (used in quantum information theory):**  
    $\huge \color{DeepSkyBlue} H = -\sum p_i \log p_i$
     
     Where:  
     - $\large \color{DeepSkyBlue} H$ is the entropy of the system (quantifies uncertainty or information).  
     - $\large \color{DeepSkyBlue} p_i$ represents the probability of the $\large \color{DeepSkyBlue} i^{th}$ event or outcome.
  
  #

   9. **Stephen Wiesner (1970)**  
   * Introduced the concepts of [quantum cryptography]() and [quantum money](), making significant contributions to the development of secure communication systems. Wiesner's work laid the groundwork for the field of quantum cryptography.

   * **Quantum Money [Quantum Currency]()**
     
     - Wiesner's idea of "quantum money" suggests using quantum states to encode currency, making it practically impossible to forge due to the properties of quantum states.  
     - [The exact mathematical formulation varies depending on the implementation](), but the general idea relies on [quantum superposition]() and [entanglement]() to ensure security and authenticity.  

   #
 
 10. **Richard Feynman (1981)**  
   * Introduced the idea of quantum computers as simulators for physical systems.

   Simplified formula for simulating quantum systems:  
   $\huge \color{DeepSkyBlue} U(t) = e^{-iHt/\hbar}$  

   Where:  
   - $\large \color{DeepSkyBlue} U(t)$ is the time evolution operator.  
   - $\large \color{DeepSkyBlue} H$ is the Hamiltonian of the system.
     
 # 

 11. **Gilles Brassard (1984)**  
   * Co-founder of the [BB84 protocol](), the first functional quantum cryptography system. The BB84 protocol is a [quantum key distribution] (QKD) protocol that allows two parties to [securely exchange cryptographic keys]() over a potentially insecure channel. The security of BB84 relies on the principles of quantum mechanics, particularly quantum superposition and the no-cloning theorem.  

   * **BB84 Protocol Formula:**  
     The Quantum Bit Error Rate (QBER) is used to measure the efficiency and security of the BB84 protocol by determining the [rate of errors]() that occur during the [transmission of quantum bits]() (qubits). It is calculated as follows:  

     $\huge \color{DeepSkyBlue} QBER = \frac{\text{observable error}}{\text{total bits sent}}$

      Where:  
     - [**Observable error**]() refers to the number of bits where the transmitted and received values differ due to noise or eavesdropping.  
     - [**Total bits sent**]() refers to the total number of qubits transmitted during the key distribution process.
    
      
     This formula is essential for determining the [level of interference and security in quantum communication systems]().
     The [lower the QBER](), the [higher the security]() of the quantum key distribution process.

#

  12. **David Deutsch (1985)**  
   * Proposed the concept of the quantum Turing machine and formulated the first quantum algorithm.
   
   Formulation of Deutsch's Algorithm:  
   $\huge \color{DeepSkyBlue} |q\rangle = \frac{1}{\sqrt{2}}(|0\rangle + |1\rangle)$  

   Where:  
   - $\large \color{DeepSkyBlue} |q\rangle$ is the superposed state of a qubit.  
   
     
    

  
   

 

  
















<!--

1. **Max Planck (1900)**  🌌  
   **Contribution**: Known as the "father of quantum theory," his discovery opened the door to quantum physics.
     
   * **Explanation**: Planck introduced the idea that energy is emitted in discrete quantities, called "quanta." His theory was the first step toward modern quantum physics.
     
   * **Formula**: Energy quantization: $\huge \color{DeepSkyBlue} {E = h \nu}$
  
<br>


2. **Albert Einstein (1905)** 💡
   **Contribution**: His ideas on wave-particle duality were crucial for modern physics, laying the foundation for quantum mechanics.
   
   -  Explained the photoelectric effect, introducing the idea of photons.
  
   - **Explanation**: Through the photoelectric effect, Einstein proposed that light behaves as particles (photons) with quantized energy, challenging the classical view of light as just a wave.

   * **Formula**: Energy of a photon: $\huge \color{DeepSkyBlue} {E = h \nu}$
  
 <br>

3. **Niels Bohr (1913)**
   * Developed the Bohr model of the atom with quantized energy levels.
     
   * **Formula**: Energy levels of hydrogen: $\huge \color{DeepSkyBlue} {E_n = - \frac{13.6}{n^2} \text{ eV}}$
  
<br>

4. **Erwin Schrödinger (1926)**
   * Developed Schrödinger's equation, forming the basis of wave mechanics.
     
   * **Formula**: Schrödinger's equation: $\huge \color{DeepSkyBlue} {i\hbar \frac{\partial}{\partial t} |\psi(t)\rangle = \hat{H} |\psi(t)\rangle}$

<br>

5. **Werner Heisenberg (1927)**
   * Introduced the Uncertainty Principle, a cornerstone of quantum mechanics.
     
   * **Formula**: Uncertainty relation: $\huge \color{DeepSkyBlue} {\Delta x \Delta p \geq \frac{\hbar}{2}}$

<br>

6. **Paul Dirac (1928)**
   * Developed the relativistic theory of the electron and contributed to quantum mechanics.
     
   * **Formula**: Dirac equation: $\huge \color{DeepSkyBlue} {\left( i \hbar \gamma^\mu \partial_\mu - mc \right) \psi = 0}$

<br>

### Mid-20th Century – [Foundations for Quantum Information]()

<br><

1. **John von Neumann (1932)**  📐
   * Formalized the mathematical framework of quantum mechanics and introduced operator theory.
  
   - **Explanation**: Von Neumann established the mathematical foundation of quantum mechanics, including measurement theory and the concept of operators.
     
   - **Contribution**: Formalized quantum theory, especially the description of quantum states and the mathematical interpretation of wave function collapse.

   - **Formula**: $\huge \color{DeepSkyBlue}\langle \psi | \hat{A} | \psi \rangle \$ 
  
<br>
  
2. **Richard Feynman (1981)** 💻  
   * Proposed the concept of quantum computers as simulators for physical systems.
 
   - **Explanation**: Feynman developed the path integral, an alternative approach to describe quantum mechanics through trajectories.
     
   - **Contribution**: Proposed the idea of a quantum computer to simulate quantum phenomena, marking the beginning of quantum computing.
  
   * **Formula**: $\huge \color{DeepSkyBlue}S = \int \mathcal{L} \, dt \$  

  
<br>

3. **David Deutsch (1985)**
   * Proposed the concept of a quantum Turing machine and formulated the first quantum algorithm.
     
   * **Formula**: General state of a qubit: $\huge \color{DeepSkyBlue} {|\psi\rangle = \alpha|0\rangle + \beta|1\rangle}$

<br>

### 1990s and 2000s – [Quantum Computing Development]()

<br>

1. **Peter Shor (1994)**
   * Developed Shor’s algorithm for quantum factorization.

   * **Formula**: Period-finding problem in modular arithmetic: $\huge \color{DeepSkyBlue} {a^x \mod N = 1}$
  
<br>

2. **Lov Grover (1996)**
   * Developed Grover’s quantum search algorithm.
     
   * **Formula**: Probability amplitude for successful search: $\huge \color{DeepSkyBlue} {\sin^2 \left((2k + 1)\theta\right)}$
  
 <br>

 3. **Charles Bennett (1993)**
    * Worked on reversible computing and discovered quantum teleportation.
   
    * The formula to describe **Charles Bennett's (1993)** work based on the provided information can be expressed as follows:

   3.1 **Reversible Computing**:  
   - Based on the concept of **reversible computation**, where operations can be undone without information loss, reducing energy dissipation (aligned with the second law of thermodynamics).  

   Simplified formula for energy and information conservation: $\huge \color{DeepSkyBlue} \Delta S = 0 \quad \text{(Entropy remains constant for reversible systems)}$
   

   3.2 **Quantum Teleportation**:  
   - Describes the transfer of quantum states between particles via quantum entanglement, without physically transferring the particle itself.  

   Generic formula for quantum teleportation: $\huge \color{DeepSkyBlue} \psi\rangle_C = |\phi\rangle_A \otimes |\beta_{00}\rangle_{BC}$
   
   Where:  
   
   - $\large \color{DeepSkyBlue} \(|\psi\rangle_C\)$ is the reconstructed state at the destination (C).
     
   - $\large \color{DeepSkyBlue} \(|\phi\rangle_A\)$ is the initial quantum state (A).
     
   - $\large \color{DeepSkyBlue} \(|\beta_{00}\rangle_{BC}\)$ represents the entangled particle pair (B and C).  


      
 



<!--

1. **Max Planck** (1900) 🌌  

    - **Formula**:
  
   $\color{Green} {\huge   E = h \nu   }$
  
   - **Explanation**: Planck introduced the idea that energy is emitted in discrete quantities, called "quanta." His theory was the first step toward modern quantum physics.
   - 
   - **Contribution**: Known as the "father of quantum theory," his discovery opened the door to quantum physics.

    <br> 

3. **Albert Einstein** (1905) 💡  
   - **Formula**: \( E_k = h \nu - \phi \)  
   - **Explanation**: Through the photoelectric effect, Einstein proposed that light behaves as particles (photons) with quantized energy, challenging the classical view of light as just a wave.
   - **Contribution**: His ideas on wave-particle duality were crucial for modern physics, laying the foundation for quantum mechanics.
  
     

4. **Niels Bohr** (1913) 🔬  
   - **Formula**: \( E_n = -\frac{Z^2 R_H}{n^2} \)  
   - **Explanation**: Bohr's model described the quantized energy levels of electrons within atoms, particularly hydrogen.
   - **Contribution**: His theory advanced atomic physics, leading to the concept of complementarity in quantum mechanics.

       <br> 

5. **Werner Heisenberg** (1927) 🎯  
   - **Formula**: \( \Delta x \Delta p \geq \frac{\hbar}{2} \)  
   - **Explanation**: The uncertainty principle states that it is impossible to simultaneously determine a particle’s position and momentum with absolute precision.
   - **Contribution**: This principle reshaped our understanding of quantum nature, showing that particle behavior remains indeterminate until observed.
  
    <br>

6. Erwin Schrödinger (1926) 🐈

![Erwin Schrödinger](path/to/image/schrodinger.jpg)

   <p align="center"> **Formula**:
     
   <p align="center"> $\color{Green} {\color{Green} {\huge  i \hbar \frac{\partial}{\partial t} \psi = \hat{H} \psi }}$
     
   - **Explanation**: Schrödinger’s equation is fundamental to quantum mechanics, describing how the quantum state of a system evolves over time. Schrödinger is also famous for his thought experiment known as **Schrödinger's cat**, where a hypothetical cat can be in both "alive" and "dead" states simultaneously until observed. This experiment illustrates the concept of quantum superposition and highlights the paradoxes in interpreting quantum mechanics.
     
   - **Contribution**: Schrödinger is known for his contribution to quantum mechanics theory, particularly through introducing the wave function, which provides a probabilistic description of particle behavior.
     
     
   <br>


7. **Paul Dirac** (1928) ➕➖  

    - **Formula**:

   $\color{Green} {\huge  (i \gamma^\mu \partial_\mu - m)\psi = 0 }$
      
   - **Explanation**: Dirac's equation unifies quantum mechanics with relativity, predicting the existence of antiparticles, such as the positron.
     
   - **Contribution**: A pioneer in quantum field theory, and among the first to propose a connection between quantum mechanics and relativity.

       <br> 

8. **John von Neumann** (1932) 📐  
   - **Formula**: \( \langle \psi | \hat{A} | \psi \rangle \)  
   - **Explanation**: Von Neumann established the mathematical foundation of quantum mechanics, including measurement theory and the concept of operators.
   - **Contribution**: Formalized quantum theory, especially the description of quantum states and the mathematical interpretation of wave function collapse.

       <br> 

9. **Claude Shannon** (1948) 📊  
   - **Formula**: \( H(X) = -\sum p(x) \log p(x) \)  
   - **Explanation**: Shannon is known as the father of information theory, introducing the concept of entropy as a measure of information in a message.
   - **Contribution**: His ideas laid the groundwork for digital communication and influenced quantum communication and data transmission research.

       <br> 

10. **Richard Feynman** (1948-1981) 💻  
   - **Formula**: \( S = \int \mathcal{L} \, dt \)  
   - **Explanation**: Feynman developed the path integral, an alternative approach to describe quantum mechanics through trajectories.
   - **Contribution**: Proposed the idea of a quantum computer to simulate quantum phenomena, marking the beginning of quantum computing.

       <br> 

11. **David Deutsch** (1985) 🌐  
   - **Formula**: N/A  
   - **Explanation**: Deutsch formalized the concept of a universal quantum computer, capable of simulating any physical system.
   - **Contribution**: His work laid the foundation for modern quantum computing, inspiring the development of quantum algorithms.

       <br> 

12. **John Bell** (1964) 🔗  
   - **Formula**: \( |E(a, b) + E(a, b') + E(a, b) - E(a', b')| \leq 2 \)  
   - **Explanation**: Bell's inequality tests if correlations between entangled particles can be explained by local theories.
   - **Contribution**: Fundamental for experiments that verified quantum entanglement and non-locality.

       <br> 

13. **Alexander Holevo** (1973) 🧩  
   - **Formula**: \( I(X:Y) \leq S(\rho) \)  
   - **Explanation**: The Holevo bound describes the maximum information extractable from a quantum system.
   - **Contribution**: Essential for quantum information theory, with implications in cryptography and quantum data transmission.

       <br> 

14. **Peter Shor** (1994) 🔓  
   - **Formula**: N/A  
   - **Explanation**: Shor's algorithm enables efficient factorization of large numbers, threatening the security of traditional cryptographic systems.
   - **Contribution**: The first quantum algorithm to solve complex problems more efficiently than classical algorithms.

       <br> 

15. **Lov Grover** (1996) 🔍  
   - **Formula**: N/A  
   - **Explanation**: Grover's algorithm improves search efficiency, reducing search time from \( O(N) \) to \( O(\sqrt{N}) \).
   - **Contribution**: Demonstrates how quantum computing can accelerate data search problems faster than classical computing.

-->

 <br><br><br><br><br><br>

## Contributions and References

This repository is a tribute to these great thinkers who have shaped physics and quantum computing. Their ideas and theories continue to inspire new generations of scientists and innovators.

## How to Contribute

Feel free to add information or corrections. This repository encourages contributions from everyone interested in Quantum Computing!
-->

#

###### <p align="center"> Copyright 2025 Quantum Software Development. Code released under the [MIT license.](https://github.com/Quantum-Software-Development/README/blob/161b677c5a791f0ca8219b8e934f1cf353d5b85d/LICENSE)
