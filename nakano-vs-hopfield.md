
# **The True Origin of the Hopfield Network: Nakano (1972) vs Hopfield (1982)** #

In 1972, Kaoru Nakano of the Tokyo Institute of Technology published a complete recurrent neural network model for associative memory in [*IEEE Transactions on Systems, Man, and Cybernetics* (SMC-2, pp. 380–388)](https://doi.org/10.1109/TSMC.1972.4309131)

The paper, **“Associatron — A Model of Associative Memory,**” already contained all of the core elements that later became known as the Hopfield network:

● A fully interconnected recurrent network with binary (±1) neurons
● A Hebbian outer-product learning rule

<i>T<sub>ij</sub> = Σ<sub>m</sub> x<sub>im</sub> x<sub>jm</sub> (i ≠ j), T<sub>ii</sub> = 0</i>

● An explicit energy (Lyapunov) function

<i>V = −1/2 Σ<sub>i</sub> Σ<sub>j</sub> T<sub>ij</sub> x<sub>i</sub> x<sub>j</sub></i>

●　A mathematical proof that the energy monotonically decreases and is bounded below, guaranteeing convergence to stable stored patterns

●　Computer simulations showing a storage capacity of approximately 0.14𝑁, remarkably close to the theoretical limit 0.138𝑁 derived more than a decade later

---

Ten years later, in 1982, John J. Hopfield published an essentially identical model in Proceedings of the National Academy of Sciences (PNAS), reframing the same mathematics using the language of spin-glass physics from statistical mechanics.

At the level of equations and dynamical behavior, the two models are the same.
The only genuinely new theoretical results appeared later (1985–1987), when Amit, Gutfreund, and Sompolinsky rigorously derived the storage capacity limit using replica methods — a limit Nakano had already reached empirically in 1972.

The difference in historical impact was not mathematical, but contextual.

Nakano’s work appeared during the first AI winter, in a systems-theory journal, and outside the physics community.
Hopfield’s paper arrived at precisely the moment when physicists were actively searching for biological applications of spin-glass theory, and it rapidly gained wide attention.

As a result, the model became universally known as the “Hopfield network.”

Hopfield later received the Nobel Prize in Physics in 2024 for foundational contributions enabling machine learning with artificial neural networks.
Nakano’s earlier work remains largely unrecognized outside Japan.


Nakano, K. (1972). *Associatron — A Model of Associative Memory.*  
[*IEEE Transactions on Systems, Man, and Cybernetics*](https://doi.org/10.1109/TSMC.1972.4309131)

Hopfield, J. J. (1982). *Neural networks and physical systems with emergent collective computational abilities.*  
[*Proceedings of the National Academy of Sciences*](https://doi.org/10.1073/pnas.79.8.2554)

---
