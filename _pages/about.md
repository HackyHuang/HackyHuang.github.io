---
permalink: /
title: "About Me"
excerpt: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am Kaixuan Huang (黄凯旋), a final year Ph.D. student in Electrical and Computer Engineering Department at Princeton University. I am fortunate to be advised by Professor [Mengdi Wang](https://mwang.princeton.edu/). Before that, I received B.S. in Mathematics and B.S. in Computer Science from Peking University. My research is partially supported by Google PHD Fellowship. 

Contact me via email <a href="mailto:kaixuanh@princeton.edu">kaixuanh@princeton.edu</a>; <a href="https://x.com/KaixuanHuang1">X Account</a>; wechat: [\[QR Code\]](../files/wechat.jpg).

Research Overview
----

My research focuses on identifying robustness issues of LLMs and solving them via scalable data pipelines and algorithmic innovations. My recent topics include:

**Robustness of RLHF and RLVR**:
- The alignment of LLMs can be easily broken by exploiting parameter-efficient finetuning (PEFT) methods. We used prefix tuning methods to construct adversarial prefixes that undo the safety alignment of LLMs <a href="https://arxiv.org/abs/2306.13213">[1]</a>. We also developed pruning and low-rank adaptation methods to identify and isolate safety-critical regions of LLMs <a href="https://arxiv.org/abs/2402.05162">[2]</a>.
- Reasoning models may memorize the problem-solving techniques from the training set and blindly apply them when the input problems are slightly perturbed <a href="https://arxiv.org/abs/2502.06453">[3]</a>.

**Inference-time Algorithms & Agents**: Scaling up inference-time compute and augmenting LLMs with tools are principled approaches to boost capabilities and improve robustness. 
- To accelerate high-quality data generation, we developed efficient decoding algorithm <a href="https://arxiv.org/abs/2405.19715">[4]</a> and inference-time alignment technique <a href="https://arxiv.org/abs/2410.16033">[5]</a>, borrowing techniques from traditional RL.
- Besides handcrafting agents <a href="https://arxiv.org/abs/2404.18021">[6]</a>, I have been thinking about distilling agents into foundation models and improving them through Reinforcement Learning.

I am also interested in long-term research that can lead to a paradigm shift for the current AI systems. 



News
-----

- 05/2025: I will give a talk at Google DeepMind about MATH-Perturb.
- 05/2025: MATH-Perturb is accepted in ICML 2025.
- 11/2024: Thrilled to receieve Google PHD Fellowship 2024.
- 10/2024: I will give a talk at INFORMS 2024 about CRISPR-GPT.
- 03/2024: I started my internship at Google DeepMind, working with Zheng Wen and Csaba Szepesvari.


Selected Works
-----

<div style="font-size:20px;">MATH-Perturb: Benchmarking LLMs' Math Reasoning Abilities against Hard Perturbations  </div>
<div style="font-size: 18px;"> ICML 2025 <a href="https://arxiv.org/abs/2502.06453">[link]</a> <a href="https://math-perturb.github.io/">[Website]</a> </div>
<div style="font-size: 16px;"><i> <b>Kaixuan Huang</b>, Jiacheng Guo, Zihao Li, Xiang Ji, Jiawei Ge, Wenzhe Li, Yingqing Guo, Tianle Cai, Hui Yuan, Runzhe Wang, Yue Wu, Ming Yin, Shange Tang, Yangsibo Huang, Chi Jin, Xinyun Chen, Chiyuan Zhang, Mengdi Wang </i></div>

<br/>


<div style="font-size:20px;">SpecDec++: Boosting Speculative Decoding via Adaptive Candidate Lengths   
<div style="font-size: 18px;"> ICML 2024 workshop on Efficient Systems for Foundation Models (ES-FoMo) <a href="https://arxiv.org/abs/2405.19715">[link]</a> <a href="https://github.com/Kaffaljidhmah2/SpecDec_pp/">[Code]</a> </div>
<div style="font-size: 16px;"><i> <b>Kaixuan Huang</b>, Xudong Guo, Mengdi Wang</i></div></div>

<br/>

<div style="font-size:20px;">CRISPR-GPT: An LLM Agent for Automated Design of Gene-Editing Experiments   </div>
<div style="font-size: 18px;"> to appear in Nature Biomedical Engineering <a href="https://arxiv.org/abs/2404.18021">[link]</a>
<div style="font-size: 16px;"><i> <b>Kaixuan Huang*</b>, Yuanhao Qu*, Henry Cousins, William A. Johnson, Di Yin, Mihir Shah, Denny Zhou, Russ Altman, Mengdi Wang, Le Cong</i></div>

<br/>

<div style="font-size:20px;">Embodied LLM Agents Learn to Cooperate in Organized Teams   </div>
<div style="font-size: 18px;"> arXiv preprint <a href="https://arxiv.org/abs/2403.12482">[link]</a></div>
<div style="font-size: 16px;"><i> Xudong Guo, <b>Kaixuan Huang</b>, Jiale Liu, Wenhui Fan, Natalia Vélez, Qingyun Wu, Huazheng Wang, Thomas L. Griffiths, Mengdi Wang </i></div>

<br/>

<div style="font-size:20px;">Assessing the Brittleness of Safety Alignment via Pruning and Low-Rank Modifications   </div>
<div style="font-size: 18px;"> ICML 2024, ICLR Secure and Trustworthy LLMs 2024 (<b>Best Paper</b>) <a href="https://arxiv.org/abs/2402.05162">[link]</a> <a href="https://github.com/boyiwei/alignment-attribution-code">[Code]</a> </div>
<div style="font-size: 16px;"><i> Boyi Wei*, <b>Kaixuan Huang*</b>, Yangsibo Huang*, Tinghao Xie, Xiangyu Qi, Mengzhou Xia, Prateek Mittal, Mengdi Wang, Peter Henderson </i></div>

<br/>

<div style="font-size:20px;">Visual Adversarial Examples Jailbreak Large Language Models   </div>
<div style="font-size: 18px;"> AAAI 2024 (<b>Oral</b>), ICML2023 Adv ML workshop (<b>Oral</b>). <a href="https://arxiv.org/abs/2306.13213">[link]</a> <a href="https://github.com/Unispac/Visual-Adversarial-Examples-Jailbreak-Large-Language-Models">[Code]</a> </div>
<div style="font-size: 16px;"><i> Xiangyu Qi*, <b>Kaixuan Huang*</b>, Ashwinee Panda, Peter Henderson, Mengdi Wang, Prateek Mittal </i></div>

<br/>

<div style="font-size:20px;">SORRY-Bench: Systematically Evaluating Large Language Model Safety Refusal Behaviors   </div>
<div style="font-size: 18px;"> ICLR 2025 <a href="https://arxiv.org/abs/2405.19524">[link]</a> <a href="https://sorry-bench.github.io/">[Website]</a> </div>
<div style="font-size: 16px;"><i> Tinghao Xie, Xiangyu Qi, Yi Zeng, Yangsibo Huang, Udari Madhushani Sehwag, <b>Kaixuan Huang </b>, Luxi He, Boyi Wei, Dacheng Li, Ying Sheng, Ruoxi Jia, Bo Li, Kai Li, Danqi Chen, Peter Henderson, Prateek Mittal </i></div>

<br/>

<div style="font-size:20px;">Scaling In-Context Demonstrations with Structured Attention   </div>
<div style="font-size: 18px;"> ICML 2023 Workshop on Efficient Systems for Foundation Models.  <a href="https://arxiv.org/abs/2307.02690">[link]</a></div>
<div style="font-size: 16px;"><i> Tianle Cai*, <b>Kaixuan Huang*</b>, Jason D. Lee, Mengdi Wang </i></div>

<br/>




