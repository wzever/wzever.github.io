## 📝 Publications 
---
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2025</div><img src='https://wzever.github.io/_pages/images/coexpander.png' alt="coexpander" height="300"></div></div>
<div class='paper-box-text' markdown="1">

(CCF-A) [**COExpander: Adaptive Solution Expansion for Combinatorial Optimization**](https://www.researchgate.net/publication/391363643_COExpander_Adaptive_Solution_Expansion_for_Combinatorial_Optimization) [[PDF](https://www.researchgate.net/profile/Jiale-Ma-9/publication/391363643_COExpander_Adaptive_Solution_Expansion_for_Combinatorial_Optimization/links/6813b80e60241d5140214026/COExpander-Adaptive-Solution-Expansion-for-Combinatorial-Optimization.pdf)][[Code (coming soon) ![github-stars](https://img.shields.io/github/stars/Thinklab-SJTU/COExpander?style=social)](https://github.com/Thinklab-SJTU/COExpander)]

Jiale Ma\*, **Wenzheng Pan***, Yang Li, Junchi Yan


- We propose a novel paradigm Adaptive Expansion (AE) and the COExpander solver for NCO solving. It bridges the global prediction (GP) and local construction (LC) paradigms via a partial state prompted heatmap generator with adaptive step sizes for decision-making.
- We re-wrap 5 non-learning baseline solvers and re-cononicalize 29 standard datasets to provide a standard benchmark for 6 commonly studied COPs.
- Compared with previous neural SOTA, COExpander has reduced the average optimality drop on 6 COPs from 3.81% to 0.66%, with a speedup of 4.0x.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='https://wzever.github.io/_pages/images/unico.png' alt="unico" height="300"></div></div>
<div class='paper-box-text' markdown="1">

(CAAI/Tsinghua-A) [**UniCO: On Unified Combinatorial Optimization via Problem Reduction to Matrix-Encoded General TSP**](https://openreview.net/forum?id=yEwakMNIex) [[PDF](https://openreview.net/pdf?id=yEwakMNIex)] [[Code ![github-stars](https://img.shields.io/github/stars/Thinklab-SJTU/UniCO?style=social)](https://github.com/Thinklab-SJTU/UniCO)]

**Wenzheng Pan**\*, Hao Xiong\*, Jiale Ma, Wentao Zhao, Yang Li, Junchi Yan

- We propose the UniCO framework to unify a set of CO problems by reducing them into the general TSP form for effective and simultaneous training.
- This work focuses on the challenging TSPs that are non-metric, asymmetric or discrete distances without explicit node coordinates.
- Two neural TSP solvers are devised w/ and w/o supervision to conquer such matrix input, respectively: 1) MatPOENet, an RL-based sequential model with pseudo one-hot embedding (POE) scheme and 2) MatDIFFNet, a Diffusion-based generative model with the mix-noised reference mapping scheme.
- Pioneering experiments have been conducted on ATSP, 2DTSP, HCP- and SAT-distributed general matrix-encoded TSPs.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='https://wzever.github.io/_pages/images/UnifyML4TSP.png' alt="ml4tsp-bench" height="300"></div></div>
<div class='paper-box-text' markdown="1">

(CAAI/Tsinghua-A) [**Unify ML4TSP: Drawing Methodological Principles for TSP and Beyond from Streamlined Design Space of Learning and Search**](https://openreview.net/forum?id=grU1VKEOLi) [[PDF](https://openreview.net/pdf?id=grU1VKEOLi)][[Code ![github-stars](https://img.shields.io/github/stars/Thinklab-SJTU/ML4TSPBench?style=social)](https://github.com/Thinklab-SJTU/ML4TSPBench)]

Yang Li, Jiale Ma, **Wenzheng Pan**, Runzhong Wang, Haoyu Geng, Nianzu Yang, Junchi Yan

- ML4TSPBench advances a unified modular streamline incorporating existing technologies in both learning and search for transparent ablation.
- The desired principles are joint probability estimation, symmetry solution representation, and online optimization, for ML4TSP solver design.
- The strategic decoupling and organic recompositions yield a factory of new and stronger TSP solvers.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JMLR </div><img src='https://wzever.github.io/_pages/images/pygmtools.png' alt="pygmtools" height="300"></div></div>
<div class='paper-box-text' markdown="1">

(CCF-A) [**Pygmtools: A Python Graph Matching Toolkit**](https://jmlr.org/papers/v25/23-0572.html) [[PDF](https://jmlr.org/papers/volume25/23-0572/23-0572.pdf)][[Code ![github-stars](https://img.shields.io/github/stars/Thinklab-SJTU/pygmtools?style=social)](https://github.com/Thinklab-SJTU/pygmtools)]

Runzhong Wang, Ziao Guo, **Wenzheng Pan**, Jiale Ma, Yikai Zhang, Nan Yang, Qi Liu, Longxuan Wei, Hanxue Zhang, Chang Liu, Zetian Jiang, Xiaokang Yang, Junchi Yan


- Pygmtools is released as a Python graph matching toolkit that implements a comprehensive collection of two-graph and multi-graph matching solvers.
- Our implementation supports numerical backends including Numpy, PyTorch, Jittor, Paddle, runs on Windows, MacOS and Linux, with friendly guidance.
</div>
</div>
