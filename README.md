<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="assets/header-light.svg" />
  <img src="assets/header-light.svg" width="100%" alt="MD Rakibul Islam Raihan — ML systems research and engineering" />
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com?font=Fira+Code&amp;weight=600&amp;size=19&amp;pause=1600&amp;color=67E8F9&amp;center=true&amp;vCenter=true&amp;width=650&amp;lines=LLM+Inference+%C2%B7+Distributed+Systems;GPU+Kernels+%C2%B7+Low-bit+Computing;Building+systems+for+long-context+agents" />
  <source media="(prefers-color-scheme: light)" srcset="https://readme-typing-svg.demolab.com?font=Fira+Code&amp;weight=600&amp;size=19&amp;pause=1600&amp;color=087EAB&amp;center=true&amp;vCenter=true&amp;width=650&amp;lines=LLM+Inference+%C2%B7+Distributed+Systems;GPU+Kernels+%C2%B7+Low-bit+Computing;Building+systems+for+long-context+agents" />
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&amp;weight=600&amp;size=19&amp;pause=1600&amp;color=087EAB&amp;center=true&amp;vCenter=true&amp;width=650&amp;lines=LLM+Inference+%C2%B7+Distributed+Systems;GPU+Kernels+%C2%B7+Low-bit+Computing;Building+systems+for+long-context+agents" width="650" height="38" alt="LLM inference, distributed systems, GPU kernels, and low-bit computing" />
</picture>

<br/>

<p align="center">
  <a href="mailto:raihanrakib.143@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" height="22" alt="Email" /></a>
  <a href="https://linkedin.com/in/theraihanrakib"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" height="22" alt="LinkedIn" /></a>
  <a href="https://theraihanrakibb.github.io/"><img src="https://img.shields.io/badge/Portfolio-FF6B6B?style=flat-square&logo=google-chrome&logoColor=white" height="22" alt="Portfolio" /></a>
  <a href="https://github.com/theraihanrakibb/theraihanrakibb/raw/main/Raihan_Resume_Bundle.zip"><img src="https://img.shields.io/badge/Resume-00B4D8?style=flat-square&logo=adobe-acrobat-reader&logoColor=white" height="22" alt="Resume bundle" /></a>
</p>

</div>

<hr/>

## 🔬 Research

I work on **machine learning systems (MLSys)**, connecting LLM inference—disaggregated serving, KV-cache offloading, and RDMA—with the memory demands of **agentic reinforcement learning**. My goal is to make long-context agent rollouts cheaper and more scalable.

> **8.3× lower TTFT** (55 s to 6.7 s) at **92% KV-cache hit** with three-tier offload over Mooncake RDMA on 4× A800-80GB.

## 🌙 Featured work

### 🌙 Mooncake PG-EP

Contributing process-group collectives and expert-parallel dispatch to [kvcache-ai/Mooncake](https://github.com/kvcache-ai/Mooncake).

## ⚡ Currently

| Role | Where | Work |
|------|-------|------|
| 🔬 **Large Model Inference Distributed System R&D Intern** | Approaching.AI · Tsinghua MADSys collaboration · Nov 2026 to present | Core Mooncake work for agent RL rollouts: the C++ transfer engine over RDMA and KV-cache offloading |
| 🔬 **Research Intern** | SJTU ReArch Lab · Nov 2026 to present | Low-bit inference kernels in CUDA/Triton and FP8/FP4 KV-cache compression |

## 🚀 Selected projects

| Project | Details |
|---------|---------|
| **[NVFP4-DiT](https://github.com/theraihanrakibb/nvfp4-dit)** | 4-bit audio-guided video diffusion. FP4-packed Triton kernels are 3.2× faster than FP16 and use 4× less memory. IEEE TNNLS, under review. |
| **[AI Infrastructure Portfolio](https://github.com/theraihanrakibb/ai-infra-portfolio)** | Ten Dockerized AI-infra services with CI and reproducible quickstarts. |
| **[Multimodal Deepfake Detection](https://github.com/theraihanrakibb/deepfake-av-detector)** | M.E. thesis: audio-visual-temporal framework for deepfake video detection. |
| **[Confidential Spark Queries](https://github.com/theraihanrakibb/spark-ckks-query)** | B.E. thesis: distributed confidential query protocol with CKKS homomorphic encryption. |
| **[Distributed Training Launcher](https://github.com/theraihanrakibb/train-launcher)** | Fault-tolerant multi-node PyTorch launcher with retry and checkpoint recovery. |

## 🛠 Tech stack

<div align="center">

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white" alt="C++" />
<img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="CUDA" />
<img src="https://img.shields.io/badge/Triton-FF6B35?style=flat-square" alt="Triton" />
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
<br/>
<img src="https://img.shields.io/badge/SGLang-FF6B35?style=flat-square" alt="SGLang" />
<img src="https://img.shields.io/badge/vLLM-76B900?style=flat-square" alt="vLLM" />
<img src="https://img.shields.io/badge/Mooncake%2FRDMA-00B4D8?style=flat-square" alt="Mooncake and RDMA" />
<img src="https://img.shields.io/badge/KV%20Cache-4361EE?style=flat-square" alt="KV cache" />
<img src="https://img.shields.io/badge/PD%20Disaggregation-4361EE?style=flat-square" alt="PD disaggregation" />
<img src="https://img.shields.io/badge/FP8%2FFP4-7209B7?style=flat-square" alt="FP8 and FP4" />
<br/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="Kubernetes" />
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux" />
<img src="https://img.shields.io/badge/Nsight-76B900?style=flat-square" alt="Nsight" />

</div>

## 🎓 Education

**Northwestern Polytechnical University · Xi'an, China**

| Degree | Details |
|--------|---------|
| **M.E. Software Engineering** | **2024–2027. GPA 88/100 · Rank 2/87 · Chinese Government Scholarship.** |
| **B.E. Computer Science** | **2020–2024. GPA 85/100 · Rank 5/56 · Outstanding Graduate · Presidential Scholarship.** |

## 📈 Activity

<div align="center">

<img src="https://img.shields.io/github/followers/theraihanrakibb?style=for-the-badge&logo=github&label=followers&color=00B4D8" alt="GitHub followers" />
<img src="https://img.shields.io/github/stars/theraihanrakibb?style=for-the-badge&logo=github&label=stars&color=FFD21E" alt="GitHub stars" />
<img src="https://komarev.com/ghpvc/?username=theraihanrakibb&label=Profile%20Views&color=0e75b6&style=for-the-badge" alt="Profile views" />

</div>

<details>
<summary>View contribution activity</summary>

<img src="assets/contribution-graph.png" width="100%" alt="GitHub contribution graph" />

</details>

<hr/>

<div align="center">
  <sub>Actions speak louder than words.</sub>
</div>
