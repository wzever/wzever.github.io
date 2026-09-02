## 📝 Selected Publications 
---
<div class="publication-overview" aria-label="Publication statistics">

<style>
.publication-overview { margin: 1.15rem 0 1.75rem; }
.publication-stats, .publication-tags { display: flex; flex-wrap: wrap; gap: .7rem; align-items: stretch; }
.publication-stat { display: inline-flex; align-items: baseline; gap: .35rem; min-width: 6.1rem; padding: .5rem .65rem; background: #fff; border: 1px solid #dbe3ec; border-radius: 6px; box-shadow: 0 3px 10px rgba(23,43,77,.04); }
.publication-stat-value { color: #172b4d; font-size: 1.05rem; font-weight: 700; line-height: 1; }
.publication-stat-label { color: #64748b; font-size: .68rem; font-weight: 600; letter-spacing: .035em; text-transform: uppercase; }
.publication-stat:before { background: #1f4f7a !important; }
.publication-stat-value { color: #1f4f7a !important; }
.publication-stat-separator { align-self: stretch; width: 1px; min-height: 1.6rem; margin: .2rem .2rem; background: #d4dde7; }
.publication-tag { position: relative; overflow: hidden; display: inline-flex; align-items: center; justify-content: space-between; gap: .45rem; min-width: 6.1rem; padding: .5rem .65rem; color: #64748b; background: #fff; border: 1px solid #dbe3ec; border-radius: 6px; box-shadow: 0 3px 10px rgba(23,43,77,.04); font-size: .68rem; font-weight: 650; letter-spacing: .035em; line-height: 1; text-transform: uppercase; }
.publication-tag:before { content: ""; position: absolute; top: 0; right: 0; left: 0; height: 2px; background: var(--tag-color); }
.publication-tag strong { color: var(--tag-color); font-size: 1.05rem; font-weight: 750; }
.publication-tag--icml { --tag-color: #198f83; }
.publication-tag--iclr { --tag-color: #6657e8; }
.publication-tag--jmlr { --tag-color: #7863b0; }
.publication-tag--neurips { --tag-color: #ef634d; }
@media (max-width: 767px) { .publication-stat, .publication-tag { flex: 1 1 6.5rem; } .publication-stat-separator { display: none; } }
@media (min-width: 768px) {
  .paper-box { align-items: center; }
  .paper-box .paper-box-image { align-self: center; display: flex; align-items: center; margin-top: auto; margin-bottom: auto; }
  .paper-box .paper-box-image > div { position: relative; display: flex; align-items: center; justify-content: center; width: fit-content; max-width: 100%; }
  .paper-box .paper-box-image img { align-self: center; }
}
</style>

<div class="publication-stats" aria-label="Publication statistics and venues">

<div class="publication-stat">
<span class="publication-stat-value">7</span>
<span class="publication-stat-label">Total</span>
</div>

<div class="publication-stat">
<span class="publication-stat-value">7</span>
<span class="publication-stat-label">CCF-A</span>
</div>

<div class="publication-stat">
<span class="publication-stat-value">3</span>
<span class="publication-stat-label">(Co-)First</span>
</div>

<span class="publication-stat-separator" aria-hidden="true"></span>

<span class="publication-tag publication-tag--icml"><strong>3</strong><span>ICML</span></span>
<span class="publication-tag publication-tag--iclr"><strong>2</strong><span>ICLR</span></span>
<span class="publication-tag publication-tag--neurips"><strong>1</strong><span>NeurIPS</span></span>
<span class="publication-tag publication-tag--jmlr"><strong>1</strong><span>JMLR</span></span>

</div>

</div>

<div class='paper-box'><div class='paper-box-image'><div><span class="badge">ICML 2026</span><img src='https://wzever.github.io/_pages/images/M2GenCO_pipeline.png' alt="m2genco" height="300"></div></div>
<div class='paper-box-text' markdown="1">

<span style="color:red;">(**CCF-A**)</span> [**Problem Distributions as Tasks: Repurposing Meta Learning for Generative Combinatorial Optimization towards Multi-task Pretraining and Adaptation**](https://openreview.net/forum?id=OfxgzjqzeA) [[PDF](https://openreview.net/pdf?id=OfxgzjqzeA)][[Code ![github-stars](https://img.shields.io/github/stars/Thinklab-SJTU/M2GenCO?style=social)](https://github.com/Thinklab-SJTU/M2GenCO)]

**Wenzheng Pan**, [Jiale Ma](https://heatingma.github.io/), [Nuoyan Chen](https://cny123222.github.io/about/), [Yang Li](https://yangco-le.github.io), [Junchi Yan](https://thinklab.sjtu.edu.cn)


We introduce **M²GenCO**, a meta-generative framework that treats problem distributions as tasks to enable efficient multi-task pretraining, few-shot adaptation, and robust generalization across graph-based combinatorial optimization problems. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><span class="badge">ICML 2026</span><img src='https://wzever.github.io/_pages/images/ml4lp.png' alt="ml4lp" height="300"></div></div>
<div class='paper-box-text' markdown="1">

<span style="color:red;">(**CCF-A**)</span> [**Design Linear Constrained Neural Layers with Implicit Convex Optimization**](https://openreview.net/forum?id=LHCQSx0cQV) [[PDF](https://openreview.net/pdf?id=LHCQSx0cQV)]

[Junchi Yan](https://thinklab.sjtu.edu.cn), [Jiaxi Liu](https://ecthelionliu.github.io), [Yihui Tu](https://openreview.net/profile?id=~Yihui_Tu1), Fangyuan Zhou, **Wenzheng Pan**, Zhongteng Gui, [Liangliang Shi](https://www.simis.cn/zh/liangliang-shi/)

We propose **LinConLayer**, a plug-in differentiable neural layer that enforces general linear constraints via implicit convex optimization, yielding efficient BLCLayer and GLCLayer variants for constrained prediction in tasks such as graph matching, portfolio allocation, and linear programming.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><span class="badge">NeurIPS 2025</span><img src='https://wzever.github.io/_pages/images/ml4co_bench_101.png' alt="ml4co_bench_101" height="300"></div></div>
<div class='paper-box-text' markdown="1">

<span style="color:red;">(**CCF-A**)</span> [**ML4CO-Bench-101: Benchmark Machine Learning
for Classic Combinatorial Problems on Graphs**](https://openreview.net/forum?id=ye4ntB1Kzi) [[PDF](https://openreview.net/pdf?id=ye4ntB1Kzi)][[Code ![github-stars](https://img.shields.io/github/stars/Thinklab-SJTU/ML4CO-Bench-101?style=social)](https://github.com/Thinklab-SJTU/ML4CO-Bench-101)]

[Jiale Ma](https://heatingma.github.io/), **Wenzheng Pan**, [Yang Li](https://yangco-le.github.io), [Junchi Yan](https://thinklab.sjtu.edu.cn)


We establishe **ML4CO-Bench-101**, a standardized benchmark and modular evaluation framework that systematically categorizes, reproduces, and compares neural solvers across seven mainstream graph-based combinatorial optimization problems.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><span class="badge">ICML 2025</span><img src='https://wzever.github.io/_pages/images/coexpander.png' alt="coexpander" height="300"></div></div>
<div class='paper-box-text' markdown="1">

<span style="color:red;">(**CCF-A**)</span> [**COExpander: Adaptive Solution Expansion for Combinatorial Optimization**](https://openreview.net/forum?id=KMaBXMWsBM) [[PDF](https://openreview.net/pdf?id=KMaBXMWsBM)][[Code ![github-stars](https://img.shields.io/github/stars/Thinklab-SJTU/COExpander?style=social)](https://github.com/Thinklab-SJTU/COExpander)]

[Jiale Ma](https://heatingma.github.io/)\*, **Wenzheng Pan**\*, [Yang Li](https://yangco-le.github.io), [Junchi Yan](https://thinklab.sjtu.edu.cn)


We introduce **COExpander**, an adaptive expansion paradigm that bridges global prediction and local construction by progressively determining decision variables with dynamically controlled step sizes for scalable combinatorial optimization.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><span class="badge">ICLR 2025</span><img src='https://wzever.github.io/_pages/images/unico.png' alt="unico" height="300"></div></div>
<div class='paper-box-text' markdown="1">

<span style="color:red;">(**CCF-A**)</span> [**UniCO: On Unified Combinatorial Optimization via Problem Reduction to Matrix-Encoded General TSP**](https://openreview.net/forum?id=yEwakMNIex) [[PDF](https://openreview.net/pdf?id=yEwakMNIex)] [[Code ![github-stars](https://img.shields.io/github/stars/Thinklab-SJTU/UniCO?style=social)](https://github.com/Thinklab-SJTU/UniCO)]

**Wenzheng Pan**\*, [Hao Xiong](https://shawxh.github.io)\*, [Jiale Ma](https://heatingma.github.io/), Wentao Zhao, [Yang Li](https://yangco-le.github.io), [Junchi Yan](https://thinklab.sjtu.edu.cn)

We propose **UniCO**, a unified neural combinatorial optimization framework that reduces diverse COPs into matrix-encoded general TSP and solves them with tailored matrix-based RL and diffusion solvers: 1) MatPOENet, an RL-based sequential model with pseudo one-hot embedding (POE) scheme and 2) MatDIFFNet, a Diffusion-based generative model with the mix-noised reference mapping scheme.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><span class="badge">ICLR 2025</span><img src='https://wzever.github.io/_pages/images/UnifyML4TSP.png' alt="ml4tsp-bench" height="300"></div></div>
<div class='paper-box-text' markdown="1">

<span style="color:red;">(**CCF-A**)</span> [**Unify ML4TSP: Drawing Methodological Principles for TSP and Beyond from Streamlined Design Space of Learning and Search**](https://openreview.net/forum?id=grU1VKEOLi) [[PDF](https://openreview.net/pdf?id=grU1VKEOLi)][[Code ![github-stars](https://img.shields.io/github/stars/Thinklab-SJTU/ML4TSPBench?style=social)](https://github.com/Thinklab-SJTU/ML4TSPBench)]

[Yang Li](https://yangco-le.github.io), [Jiale Ma](https://heatingma.github.io/), **Wenzheng Pan**, [Runzhong Wang](http://runzhong.wang), [Haoyu Geng](https://scholar.google.com/citations?user=_R_RZpAAAAAJ&hl=zh-CN), [Nianzu Yang](https://yangnianzu0515.github.io), [Junchi Yan](https://thinklab.sjtu.edu.cn)

We present **ML4TSPBench**, a modular framework that decomposes learning-based TSP solvers into reusable learning and search components, revealing key design principles for stronger and more principled ML4CO methods.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><span class="badge">JMLR 2024</span><img src='https://wzever.github.io/_pages/images/pygmtools.png' alt="pygmtools" height="300"></div></div>
<div class='paper-box-text' markdown="1">

<span style="color:red;">(**CCF-A**)</span> [**Pygmtools: A Python Graph Matching Toolkit**](https://jmlr.org/papers/v25/23-0572.html) [[PDF](https://jmlr.org/papers/volume25/23-0572/23-0572.pdf)][[Code ![github-stars](https://img.shields.io/github/stars/Thinklab-SJTU/pygmtools?style=social)](https://github.com/Thinklab-SJTU/pygmtools)]

[Runzhong Wang](http://runzhong.wang), [Ziao Guo](https://ziao-guo.github.io), **Wenzheng Pan**, [Jiale Ma](https://heatingma.github.io/), Yikai Zhang, Nan Yang, [Qi Liu](https://scholar.google.com/citations?user=NOesDE8AAAAJ&hl=zh-CN), Longxuan Wei, Hanxue Zhang, Chang Liu, [Zetian Jiang](https://scholar.google.com/citations?user=VzyV9GoAAAAJ&hl=zh-CN), [Xiaokang Yang](https://scholar.google.com/citations?user=yDEavdMAAAAJ&hl=zh-CN), [Junchi Yan](https://thinklab.sjtu.edu.cn)


We release **Pygmtools**, an open-source Python toolkit that unifies classical, multi-graph, and learning-based graph matching solvers across multiple numerical backends for research and practical applications.
</div>
</div>
