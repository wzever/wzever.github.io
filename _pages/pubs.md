## 📝 Selected Publications 
---
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2026</div><img src='https://wzever.github.io/_pages/images/M2GenCO_pipeline.png' alt="m2genco" height="300"></div></div>
<div class='paper-box-text' markdown="1">

(**CCF-A**) [**Problem Distributions as Tasks: Repurposing Meta Learning for Generative Combinatorial Optimization towards Multi-task Pretrain and Adaptation**](https://openreview.net/forum?id=OfxgzjqzeA) [[PDF](https://openreview.net/pdf?id=OfxgzjqzeA)][[Code ![github-stars](https://img.shields.io/github/stars/Thinklab-SJTU/M2GenCO?style=social)](https://github.com/Thinklab-SJTU/M2GenCO)]

**Wenzheng Pan**, Jiale Ma, Nuoyan Chen, Yang Li, Junchi Yan


- A new meta-learning view for CO: M²GenCO conceptualizes a task as a COP type and its data distribution, enabling cross-problem pretraining beyond instance-wise optimization.
- Meta-diffusion for transferable generation: it couples diffusion-based generative modeling, which fits task-specific solution distributions, with multi-task meta-learning, which improves few-shot OOD adaptation.
- Systematic distribution-level benchmarks: it introduces support/query splits over 5 graph-based COPs and diverse distributions/scales, moving NCO evaluation beyond uniform-instance testing.
- Strong accuracy-efficiency trade-off: experiments show state-of-the-art performance across tasks while reducing inference time and training cost compared with mainstream generative CO methods.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='https://wzever.github.io/_pages/images/ml4co_bench_101.png' alt="ml4co_bench_101" height="300"></div></div>
<div class='paper-box-text' markdown="1">

(**CCF-A**) [**ML4CO-Bench-101: Benchmark Machine Learning
for Classic Combinatorial Problems on Graphs**](https://openreview.net/forum?id=ye4ntB1Kzi) [[PDF](https://openreview.net/pdf?id=ye4ntB1Kzi)][[Code ![github-stars](https://img.shields.io/github/stars/Thinklab-SJTU/ML4CO-Bench-101?style=social)](https://github.com/Thinklab-SJTU/ML4CO-Bench-101)]

Jiale Ma, **Wenzheng Pan**, Yang Li, Junchi Yan


In this paper, we establish a modular and streamlined framework benchmarking prevalent neural CO methods, dissecting their design choices via a tri-leveled “paradigm-model-learning” taxonomy to better characterize different approaches. Further, we integrate their shared features and respective strengths to form 3 unified solvers representing global prediction (GP), local construction (LC), and adaptive expansion (AE) mannered neural solvers. We also collate a total of 34 datasets for 7 mainstream CO problems (including both edge-oriented tasks: TSP, ATSP, CVRP, as well as node-oriented: MIS, MCl, MVC, MCut) across scales to facilitate more comparable results among literature.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2025</div><img src='https://wzever.github.io/_pages/images/coexpander.png' alt="coexpander" height="300"></div></div>
<div class='paper-box-text' markdown="1">

(**CCF-A**) [**COExpander: Adaptive Solution Expansion for Combinatorial Optimization**](https://openreview.net/forum?id=KMaBXMWsBM) [[PDF](https://openreview.net/pdf?id=KMaBXMWsBM)][[Code ![github-stars](https://img.shields.io/github/stars/Thinklab-SJTU/COExpander?style=social)](https://github.com/Thinklab-SJTU/COExpander)]

Jiale Ma\*, **Wenzheng Pan***, Yang Li, Junchi Yan


- We propose a novel paradigm Adaptive Expansion (AE) and the COExpander solver for NCO solving. It bridges the global prediction (GP) and local construction (LC) paradigms via a partial state prompted heatmap generator with adaptive step sizes for decision-making.
- We re-wrap 5 non-learning baseline solvers and re-cononicalize 29 standard datasets to provide a standard benchmark for 6 commonly studied COPs.
- Compared with previous neural SOTA, COExpander has reduced the average optimality drop on 6 COPs from 3.81% to 0.66%, with a speedup of 4.0x.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='https://wzever.github.io/_pages/images/unico.png' alt="unico" height="300"></div></div>
<div class='paper-box-text' markdown="1">

(**CCF-A**) [**UniCO: On Unified Combinatorial Optimization via Problem Reduction to Matrix-Encoded General TSP**](https://openreview.net/forum?id=yEwakMNIex) [[PDF](https://openreview.net/pdf?id=yEwakMNIex)] [[Code ![github-stars](https://img.shields.io/github/stars/Thinklab-SJTU/UniCO?style=social)](https://github.com/Thinklab-SJTU/UniCO)]

**Wenzheng Pan**\*, Hao Xiong\*, Jiale Ma, Wentao Zhao, Yang Li, Junchi Yan

- We propose the UniCO framework to unify a set of CO problems by reducing them into the general TSP form for effective and simultaneous training.
- This work focuses on the challenging TSPs that are non-metric, asymmetric or discrete distances without explicit node coordinates.
- Two neural TSP solvers are devised w/ and w/o supervision to conquer such matrix input, respectively: 1) MatPOENet, an RL-based sequential model with pseudo one-hot embedding (POE) scheme and 2) MatDIFFNet, a Diffusion-based generative model with the mix-noised reference mapping scheme.
- Pioneering experiments have been conducted on ATSP, 2DTSP, HCP- and SAT-distributed general matrix-encoded TSPs.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='https://wzever.github.io/_pages/images/UnifyML4TSP.png' alt="ml4tsp-bench" height="300"></div></div>
<div class='paper-box-text' markdown="1">

(**CCF-A**) [**Unify ML4TSP: Drawing Methodological Principles for TSP and Beyond from Streamlined Design Space of Learning and Search**](https://openreview.net/forum?id=grU1VKEOLi) [[PDF](https://openreview.net/pdf?id=grU1VKEOLi)][[Code ![github-stars](https://img.shields.io/github/stars/Thinklab-SJTU/ML4TSPBench?style=social)](https://github.com/Thinklab-SJTU/ML4TSPBench)]

Yang Li, Jiale Ma, **Wenzheng Pan**, Runzhong Wang, Haoyu Geng, Nianzu Yang, Junchi Yan

- ML4TSPBench advances a unified modular streamline incorporating existing technologies in both learning and search for transparent ablation.
- The desired principles are joint probability estimation, symmetry solution representation, and online optimization, for ML4TSP solver design.
- The strategic decoupling and organic recompositions yield a factory of new and stronger TSP solvers.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JMLR </div><img src='https://wzever.github.io/_pages/images/pygmtools.png' alt="pygmtools" height="300"></div></div>
<div class='paper-box-text' markdown="1">

(**CCF-A**) [**Pygmtools: A Python Graph Matching Toolkit**](https://jmlr.org/papers/v25/23-0572.html) [[PDF](https://jmlr.org/papers/volume25/23-0572/23-0572.pdf)][[Code ![github-stars](https://img.shields.io/github/stars/Thinklab-SJTU/pygmtools?style=social)](https://github.com/Thinklab-SJTU/pygmtools)]

Runzhong Wang, Ziao Guo, **Wenzheng Pan**, Jiale Ma, Yikai Zhang, Nan Yang, Qi Liu, Longxuan Wei, Hanxue Zhang, Chang Liu, Zetian Jiang, Xiaokang Yang, Junchi Yan


- Pygmtools is released as a Python graph matching toolkit that implements a comprehensive collection of two-graph and multi-graph matching solvers.
- Our implementation supports numerical backends including Numpy, PyTorch, Jittor, Paddle, runs on Windows, MacOS and Linux, with friendly guidance.
</div>
</div>
