## Ohio University Reading Group Schedule

<table>
  <tr>
    <th> Date </th>
    <th> Paper </th>
    <th> Presenter </th>
  </tr>
  <tr>
    <td> TBD </td>
    <td> TBD </td>
    <td> TBD </td>
  </tr>
  <tr>
    <td> TBD </td>
    <td> TBD </td>
    <td> TBD </td>
  </tr>
  <tr>
    <td> TBD </td>
    <td> TBD </td>
    <td> TBD </td>
  </tr>
</table>

> <b>TODO</b>: select papers from POPL19, AAAI19, etc.


#### Possible POPL19 papers (in no particular order):

* [An Abstract Domain for Certifying Neural Networks](https://dl.acm.org/ft_gateway.cfm?id=3290354)
    * Abstract interpretation of neural networks.

* [Definitional Proof-Irrelevance without K](https://dl.acm.org/ft_gateway.cfm?id=3290316)
    * Proof irrelevance compatible with univalence (not particularly relevant to us but could be useful for understanding the type theory underlying Coq).

* [Formal Verification of Higher-Order Probabilistic Programs](https://dl.acm.org/ft_gateway.cfm?id=3290351)
    * Program logics for verifying higher-order probabilistic programs with built-in sampling, conditioning, and probability theory axioms. Quasi-Borel space semantics.

* [Pretend Synchrony](https://dl.acm.org/ft_gateway.cfm?id=3290372)
    * Verifying asynchronous distributed programs by treating them as regular synchronous programs and verifying with Floyd-Hoare logic and SMT.

* [A Separation Logic for Concurrent Randomized Programs](https://dl.acm.org/ft_gateway.cfm?id=3290377)
    * Based on / extends the idea of coupling.


#### Possible AAAI-19 papers:

* [Capacity Control of ReLU Neural Networks by Basis-path Norm](https://www.aaai.org/Papers/AAAI/2019/AAAI-ZhengS.1575.pdf)
    * "Basis-path Norm" as a capacity measure for ReLU networks. Generalization error bound based on the norm. It "explains the generalization behaviors of ReLU networks more accurately than previous capacity measures".

* [Inverse Abstraction of Neural Networks Using Symbolic Interpolation](https://www.aaai.org/Papers/AAAI/2019/AAAI-DathathriS.3732.pdf)
    * Computing symbolic abstractions of pre-images of unsafe outputs under a network (regions in input space mapped to the unsafe output by the network).

* [Robustness Guarantees for Bayesian Inference with Gaussian Processes](https://www.aaai.org/Papers/AAAI/2019/AAAI-CardelliL.5988.pdf)
    * Robustness (against adversarial examples) measure for Bayesian inference. 

* [Distributionally Adversarial Attack](https://www.aaai.org/Papers/AAAI/2019/AAAI-ZhengTianhang.602.pdf)
    * Solving for optimal "adversarial-data distribution", a square-norm constrained deviation from the original distribution that maximally increases generalization risk. 

* [On Testing of Uniform Samplers](https://www.aaai.org/Papers/AAAI/2019/AAAI-ChakrabortySourav.652.pdf)
    * Testing uniformity of samplers with a small number of samples.


##### Less relevant but maybe interesting (also AAAI-19):

* [Consensus in Opinion Formation Processes in Fully Evolving Environments](https://www.aaai.org/Papers/AAAI/2019/AAAI-AulettaV.6390.pdf)
    * Convergence of opinion formation in social networks in which the structure of the social graph, agents' stubbornness levels, and their innate beliefs can change over time (influenced by one another).

* [Compiling Bayesian Network Classifiers into Decision Graphs](https://www.aaai.org/Papers/AAAI/2019/AAAI-ShihA.4035.pdf)
    * Decision graphs are small thus amenable to tractable formal verification.

* [Sparse Adversarial Perturbations for Videos](https://www.aaai.org/Papers/AAAI/2019/AAAI-WeiX.2649.pdf)
    * Computing adversarial perturbations for key frames in a video and interpolating across the frames in between. Sparse means "temporally sparse".
