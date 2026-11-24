<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/studio/hero-raihan-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="assets/studio/hero-raihan-light.svg" />
  <img src="assets/studio/hero-raihan-light.svg" width="100%" alt="Raihan — ML systems. Actions speak louder than words." />
</picture>

<p align="center">
  <br />
  <a href="https://theraihanrakibb.github.io/"><img src="https://img.shields.io/badge/Portfolio-B64730?style=flat-square&amp;logo=googlechrome&amp;logoColor=white" alt="Portfolio" /></a>
  <a href="https://linkedin.com/in/theraihanrakib"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square" alt="LinkedIn" /></a>
  <a href="mailto:raihanrakib.143@gmail.com"><img src="https://img.shields.io/badge/Email-A72D3D?style=flat-square&amp;logo=gmail&amp;logoColor=white" alt="Email" /></a>
  <a href="Raihan_Research_Resume.pdf"><img src="https://img.shields.io/badge/Research%20CV-6641A2?style=flat-square" alt="Research CV" /></a>
  <a href="Raihan_Technical_Resume.pdf"><img src="https://img.shields.io/badge/Technical%20CV-08788D?style=flat-square" alt="Technical CV" /></a>
</p>

## Selected work

<p>
  <a href="https://github.com/kvcache-ai/Mooncake"><img src="assets/studio/mooncake.png" width="49%" alt="Mooncake: contributing process-group collectives and expert-parallel dispatch. C++ and RDMA." /></a>
  <a href="https://github.com/theraihanrakibb/nvfp4-dit"><img src="assets/studio/nvfp4.png" width="49%" alt="NVFP4-DiT: 4-bit audio-guided video diffusion with Triton and FP4." /></a>
  <a href="https://github.com/theraihanrakibb/ai-infra-portfolio"><img src="assets/studio/infra.png" width="49%" alt="AI Infrastructure Portfolio: ten Dockerized services with CI and reproducible quickstarts." /></a>
  <a href="https://github.com/theraihanrakibb/deepfake-av-detector"><img src="assets/studio/deepfake.png" width="49%" alt="Multimodal deepfake detection: M.E. thesis on audio, video, and temporal inconsistencies." /></a>
</p>

## Tech stack

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

## Research & experience

I work on distributed LLM inference and low-bit GPU kernels to make long-context agent rollouts cheaper to run.

**[SJTU ReArch Lab][rearch]** · Research Intern  
I develop CUDA and Triton inference kernels and work on FP8 and FP4 KV-cache compression.

**[Approaching.AI][approaching]** · Distributed Inference R&D Intern  
I work on [Mooncake](https://github.com/kvcache-ai/Mooncake) and agent RL, in collaboration with [Tsinghua MADSys](https://madsys.cs.tsinghua.edu.cn/).

## Selected results

**55 s → 6.7 s** · Time to first token  
Three-tier KV-cache offloading with [Mooncake][mooncake] over RDMA on four NVIDIA A800 GPUs (80 GB each), at a **92% cache hit rate**.

**3.2× speedup · ¼ of the memory** · FP4 vs. FP16  
FP4-packed Triton kernels in [NVFP4-DiT][nvfp4]. The paper is under review at IEEE TNNLS.

## Education

[**Northwestern Polytechnical University**](https://en.nwpu.edu.cn/) · Xi’an, China  
**M.E. in Software Engineering** · 2024–2027\
Rank **2/87** · GPA 88/100 · Chinese Government Scholarship

[**Northwestern Polytechnical University**](https://en.nwpu.edu.cn/) · Xi’an, China  
**B.E. in Computer Science** · 2020–2024\
Rank **5/56** · GPA 85/100 · Outstanding Graduate · Presidential Scholarship

---

**More projects** · [LLM Gateway](https://github.com/theraihanrakibb/llm-gateway) · [Mini LLM Serve](https://github.com/theraihanrakibb/mini-llm-serve) · [LLM Benchmark](https://github.com/theraihanrakibb/llm-benchmark) · [KV Cache Simulator](https://github.com/theraihanrakibb/kv-cache-simulator)

[rearch]: https://github.com/SJTU-ReArch-Group
[approaching]: https://approaching-ai.com/en/
[mooncake]: https://github.com/kvcache-ai/Mooncake
[nvfp4]: https://github.com/theraihanrakibb/nvfp4-dit
