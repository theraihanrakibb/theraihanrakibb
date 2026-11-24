<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/studio/hero-dark.gif" />
  <source media="(prefers-color-scheme: light)" srcset="assets/studio/hero-light.gif" />
  <img src="assets/studio/hero-light.gif" width="100%" alt="Raihan — ML systems. Actions speak louder than words." />
</picture>

<p>
  <b>LLM inference &nbsp;·&nbsp; GPU kernels &nbsp;·&nbsp; Distributed systems</b>
</p>

<p>
  <a href="https://theraihanrakibb.github.io/">Portfolio</a> &nbsp; / &nbsp;
  <a href="https://linkedin.com/in/theraihanrakib">LinkedIn</a> &nbsp; / &nbsp;
  <a href="mailto:raihanrakib.143@gmail.com">Email</a> &nbsp; / &nbsp;
  <a href="Raihan_Research_Resume.pdf">Research CV</a> &nbsp; / &nbsp;
  <a href="Raihan_Technical_Resume.pdf">Technical CV</a>
</p>

## Selected work

<p>
  <a href="https://github.com/kvcache-ai/Mooncake"><img src="assets/studio/mooncake.png" width="49%" alt="Mooncake: contributing process-group collectives and expert-parallel dispatch. C++ and RDMA." /></a>
  <a href="https://github.com/theraihanrakibb/nvfp4-dit"><img src="assets/studio/nvfp4.png" width="49%" alt="NVFP4-DiT: 4-bit audio-guided video diffusion with Triton and FP4." /></a>
  <a href="https://github.com/theraihanrakibb/ai-infra-portfolio"><img src="assets/studio/infra.png" width="49%" alt="AI Infrastructure Portfolio: ten Dockerized services with CI and reproducible quickstarts." /></a>
  <a href="https://github.com/theraihanrakibb/deepfake-av-detector"><img src="assets/studio/deepfake.png" width="49%" alt="Multimodal deepfake detection: M.E. thesis on audio, video, and temporal inconsistencies." /></a>
</p>

## Tech stack

<p>
  <strong>Languages &amp; GPU kernels</strong><br />
  <img src="https://img.shields.io/badge/Python-376DA0?style=flat-square&amp;logo=python&amp;logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&amp;logo=cplusplus&amp;logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/CUDA-4D7400?style=flat-square&amp;logo=nvidia&amp;logoColor=white" alt="CUDA" />
  <img src="https://img.shields.io/badge/Triton-B94017?style=flat-square" alt="Triton" />
  <img src="https://img.shields.io/badge/PyTorch-B83926?style=flat-square&amp;logo=pytorch&amp;logoColor=white" alt="PyTorch" />
</p>

<p>
  <strong>Inference &amp; memory</strong><br />
  <img src="https://img.shields.io/badge/SGLang-BD4820?style=flat-square" alt="SGLang" />
  <img src="https://img.shields.io/badge/vLLM-4D7400?style=flat-square" alt="vLLM" />
  <img src="https://img.shields.io/badge/Mooncake%20%2F%20RDMA-087B9A?style=flat-square" alt="Mooncake / RDMA" />
  <img src="https://img.shields.io/badge/KV%20cache-2757AD?style=flat-square" alt="KV cache" />
  <img src="https://img.shields.io/badge/Prefill%20%2F%20decode-4E47B0?style=flat-square" alt="Prefill / decode" />
  <img src="https://img.shields.io/badge/FP8%20%2F%20FP4-6C3CA1?style=flat-square" alt="FP8 / FP4" />
</p>

<p>
  <strong>Infrastructure &amp; profiling</strong><br />
  <img src="https://img.shields.io/badge/Docker-146BA8?style=flat-square&amp;logo=docker&amp;logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Kubernetes-3256AE?style=flat-square&amp;logo=kubernetes&amp;logoColor=white" alt="Kubernetes" />
  <img src="https://img.shields.io/badge/Linux-745800?style=flat-square&amp;logo=linux&amp;logoColor=white" alt="Linux" />
  <img src="https://img.shields.io/badge/Nsight-4D7400?style=flat-square" alt="Nsight" />
</p>

## Research & experience

I work on **distributed LLM inference and low-bit GPU kernels** to make long-context agent rollouts cheaper to run.

- **SJTU ReArch Lab · Research Intern** — CUDA and Triton kernels, plus FP8/FP4 KV-cache compression.
- **Approaching.AI · Distributed Inference R&D Intern** — Mooncake’s C++ transfer engine, RDMA, and KV-cache offloading for agent RL, in collaboration with Tsinghua MADSys.

### Selected results

> **55 s → 6.7 s time to first token** at a **92% KV-cache hit rate** with three-tier Mooncake RDMA offloading on 4× A800 80 GB GPUs.
>
> **3.2× kernel speedup** over FP16 with **one-quarter of the memory** for FP4-packed Triton kernels in NVFP4-DiT. IEEE TNNLS, under review.

### Education

**Northwestern Polytechnical University** · Xi’an, China

- **M.E. Software Engineering** · 2024–2027 · Rank 2/87 · GPA 88/100 · Chinese Government Scholarship
- **B.E. Computer Science** · 2020–2024 · Rank 5/56 · GPA 85/100 · Outstanding Graduate · Presidential Scholarship

**More projects** · [Distributed Training Launcher](https://github.com/theraihanrakibb/train-launcher) · [Confidential Spark Queries](https://github.com/theraihanrakibb/spark-ckks-query)
