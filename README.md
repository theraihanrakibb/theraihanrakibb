<div align="center">

<h1>MD Rakibul Islam Raihan</h1>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=00D9FF&center=true&vCenter=true&width=760&lines=LLM+Inference;AI+Infrastructure;ML+Systems" alt="LLM Inference, AI Infrastructure, ML Systems" height="34" />

<p>
  <a href="mailto:raihanrakib.143@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" height="24" alt="Email" /></a>
  &nbsp;
  <a href="https://linkedin.com/in/theraihanrakib"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" height="24" alt="LinkedIn" /></a>
  &nbsp;
  <a href="https://theraihanrakibb.github.io/"><img src="https://img.shields.io/badge/Portfolio-FF6B6B?style=flat-square&logo=google-chrome&logoColor=white" height="24" alt="Portfolio" /></a>
  &nbsp;
  <a href="https://github.com/theraihanrakibb/theraihanrakibb/blob/main/Raihan_Technical_Resume.pdf"><img src="https://img.shields.io/badge/Technical%20Resume-2027-00B4D8?style=flat-square&logo=adobe-acrobat-reader&logoColor=white" height="24" alt="Technical resume" /></a>
  &nbsp;
  <a href="https://github.com/theraihanrakibb/theraihanrakibb/blob/main/Raihan_Research_Resume.pdf"><img src="https://img.shields.io/badge/Research%20Resume-2027-00B4D8?style=flat-square&logo=adobe-acrobat-reader&logoColor=white" height="24" alt="Research resume" /></a>
</p>

<p>
  <img src="https://img.shields.io/badge/LLM%20Inference-00B4D8?style=flat-square&logo=serverless&logoColor=white" height="22" alt="LLM Inference" />
  <img src="https://img.shields.io/badge/AI%20Infrastructure-4361EE?style=flat-square&logo=databricks&logoColor=white" height="22" alt="AI Infrastructure" />
  <img src="https://img.shields.io/badge/ML%20Systems-7209B7?style=flat-square&logo=nvidia&logoColor=white" height="22" alt="ML Systems" />
</p>

<p align="justify"><b>Focus:</b> LLM Inference &nbsp;|&nbsp; AI Infrastructure &nbsp;|&nbsp; ML Systems</p>

</div>

---

<p align="justify">My research focuses on Machine Learning Systems (MLSys). Specifically, I aim to bridge the gap between the LLM inference stack (disaggregated serving, KV-cache offloading, RDMA) and the memory-intensive demands of Agentic Reinforcement Learning (Agent RL). My goal is to design systems that make long-context agent rollouts cheaper and more scalable.</p>

<p align="justify">At InfiX.ai I cut long-context time to first token 8.3× (55 s to 6.7 s) at a 92% KV-cache hit rate with three-tier offload over Mooncake RDMA on 4× A800-80GB.</p>

<p align="justify"><b>Open to ML Systems / LLM Inference Engineering roles from Jul 2027.</b></p>

---

### Headline

<p align="center"><b>🌙 Mooncake PG-EP</b> &nbsp; <a href="https://github.com/kvcache-ai/Mooncake/pull/5755"><img src="https://img.shields.io/badge/PR%20%235755-Open%20Review-00B4D8?style=flat-square&logo=github&logoColor=white" height="22" alt="PR 5755 open review" /></a></p>

<p align="justify">Process-group collectives (Ring, OneShot, hierarchical AllReduce) and expert-parallel token dispatch for disaggregated LLM serving. The combined PG/EP build passes 68 CTest entries and four host checks, including the EP dispatch-slot test. My hierarchical AllReduce topology is in upstream review against <a href="https://github.com/kvcache-ai/Mooncake">kvcache-ai/Mooncake</a>.</p>

### Now

| Role | Where | What I do |
|------|-------|-----------|
| **Large Model Inference Distributed System R&D Intern** | Approaching.AI · Tsinghua MADSys collaboration · Nov 2026 to present | Core Mooncake development for agent RL rollouts: the C++ transfer engine over RDMA and KV-cache offloading |
| **Research Intern** | SJTU ReArch Lab · Nov 2026 to present | Low-bit inference kernels in CUDA/Triton and FP8/FP4 KV-cache compression |

---

### Selected work

| Project | What it does |
|---------|--------------|
| [NVFP4-DiT](https://github.com/theraihanrakibb/nvfp4-dit) | 4-bit audio-guided video diffusion. FP4-packed Triton kernels are 3.2× faster than FP16 and use 4× less memory. IEEE TNNLS, under review. |
| [AI Infrastructure Portfolio](https://github.com/theraihanrakibb/ai-infra-portfolio) | Ten Dockerized AI-infra services with CI and reproducible quickstarts. |
| [Multimodal Deepfake Detection](https://github.com/theraihanrakibb/deepfake-av-detector) | M.E. thesis: audio-visual-temporal framework for deepfake video detection. |
| [Confidential Spark Queries](https://github.com/theraihanrakibb/spark-ckks-query) | B.E. thesis: distributed confidential query protocol with CKKS homomorphic encryption. |
| [Distributed Training Launcher](https://github.com/theraihanrakibb/train-launcher) | Fault-tolerant multi-node PyTorch launcher with retry and checkpoint recovery. |

---

### Tech stack

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" height="22" alt="Python" />
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white" height="22" alt="C++" />
  <img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" height="22" alt="CUDA" />
  <img src="https://img.shields.io/badge/Triton-FF6B35?style=flat-square" height="22" alt="Triton" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" height="22" alt="PyTorch" />
  <br/>
  <img src="https://img.shields.io/badge/SGLang-FF6B35?style=flat-square" height="22" alt="SGLang" />
  <img src="https://img.shields.io/badge/vLLM-76B900?style=flat-square" height="22" alt="vLLM" />
  <img src="https://img.shields.io/badge/Mooncake%2FRDMA-00B4D8?style=flat-square" height="22" alt="Mooncake and RDMA" />
  <img src="https://img.shields.io/badge/KV%20Cache-4361EE?style=flat-square" height="22" alt="KV cache" />
  <img src="https://img.shields.io/badge/PD%20Disaggregation-4361EE?style=flat-square" height="22" alt="PD disaggregation" />
  <img src="https://img.shields.io/badge/FP8%2FFP4-7209B7?style=flat-square" height="22" alt="FP8 and FP4" />
  <br/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" height="22" alt="Docker" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" height="22" alt="Kubernetes" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" height="22" alt="Linux" />
  <img src="https://img.shields.io/badge/Nsight-76B900?style=flat-square" height="22" alt="Nsight" />
</p>

---

### Education

<p align="justify"><b>Northwestern Polytechnical University</b> · Xi'an, China</p>

| Degree | Period | Details |
|--------|--------|---------|
| **M.E. Software Engineering** | 2024–2027 | GPA 88/100 · Rank 2/87 · Chinese Government Scholarship |
| **B.E. Computer Science** | 2020–2024 | GPA 85/100 · Rank 5/56 · Outstanding Graduate · Presidential Scholarship |

<details>
<summary>Contribution graph</summary>

<div align="center">
  <img src="assets/contribution-graph.png" width="100%" alt="GitHub contribution graph" />
</div>

</details>
