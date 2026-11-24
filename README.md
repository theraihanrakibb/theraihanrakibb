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

<br/>

<sub>SELECTED WORK — EXPLORE A PROJECT</sub>

<p>
  <a href="https://github.com/kvcache-ai/Mooncake"><img src="assets/studio/mooncake.png" width="49%" alt="Mooncake: contributing process-group collectives and expert-parallel dispatch. C++ and RDMA." /></a>
  <a href="https://github.com/theraihanrakibb/nvfp4-dit"><img src="assets/studio/nvfp4.png" width="49%" alt="NVFP4-DiT: 4-bit audio-guided video diffusion with Triton and FP4." /></a>
  <a href="https://github.com/theraihanrakibb/ai-infra-portfolio"><img src="assets/studio/infra.png" width="49%" alt="AI Infrastructure Portfolio: ten Dockerized services with CI and reproducible quickstarts." /></a>
  <a href="https://github.com/theraihanrakibb/deepfake-av-detector"><img src="assets/studio/deepfake.png" width="49%" alt="Multimodal deepfake detection: M.E. thesis on audio, video, and temporal inconsistencies." /></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&amp;logo=python&amp;logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&amp;logo=c%2B%2B&amp;logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&amp;logo=nvidia&amp;logoColor=white" alt="CUDA" />
  <img src="https://img.shields.io/badge/Triton-FF6B35?style=flat-square" alt="Triton" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&amp;logo=pytorch&amp;logoColor=white" alt="PyTorch" />
</p>

<details>
<summary><b>Behind the work</b> · research &amp; experience</summary>

My research connects disaggregated LLM serving, KV-cache offloading, and RDMA with the memory demands of agentic reinforcement learning. My goal is to make long-context agent rollouts cheaper and more scalable.

**Research Intern · SJTU ReArch Lab**  
November 2026–present. Low-bit CUDA/Triton inference kernels and FP8/FP4 KV-cache compression.

**Large Model Inference Distributed System R&D Intern · Approaching.AI**  
November 2026–present. Tsinghua MADSys collaboration: Mooncake's C++ transfer engine, RDMA, and KV-cache offloading for agent RL rollouts.

**Tools:** SGLang, vLLM, Mooncake, Linux, Docker, Kubernetes, NVIDIA Nsight.

</details>

<details>
<summary><b>A closer look</b> · results &amp; more projects</summary>

**Inference:** 8.3× lower TTFT (55 s → 6.7 s), at 92% KV-cache hit rate with three-tier offload over Mooncake RDMA on 4× A800-80GB.

**NVFP4-DiT:** FP4-packed Triton kernels are 3.2× faster than FP16 and use 4× less memory. IEEE TNNLS, under review.

**[Distributed Training Launcher](https://github.com/theraihanrakibb/train-launcher):** fault-tolerant multi-node PyTorch launcher with retries and checkpoint recovery.

**[Confidential Spark Queries](https://github.com/theraihanrakibb/spark-ckks-query):** B.E. thesis on distributed confidential queries with CKKS homomorphic encryption.

</details>

<details>
<summary><b>Background</b> · education</summary>

**Northwestern Polytechnical University · Xi'an, China**

**M.E. Software Engineering · 2024–2027**  
GPA 88/100 · Rank 2/87 · Chinese Government Scholarship.

**B.E. Computer Science · 2020–2024**  
GPA 85/100 · Rank 5/56 · Outstanding Graduate · Presidential Scholarship.

</details>
