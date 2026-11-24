# MD Rakibul Islam Raihan

LLM inference and GPU systems engineer. I build serving systems around KV-cache offloading, prefill/decode disaggregation, and low-precision kernels.

M.E. Software Engineering, Northwestern Polytechnical University, graduating Jul 2027. Open to ML systems and inference engineering roles from Jul 2027.

[Email](mailto:raihanrakib.143@gmail.com) · [LinkedIn](https://linkedin.com/in/theraihanrakib) · [Portfolio](https://theraihanrakibb.github.io/) · [Technical resume](https://github.com/theraihanrakibb/theraihanrakibb/blob/main/Raihan_Technical_Resume.pdf) · [Research resume](https://github.com/theraihanrakibb/theraihanrakibb/blob/main/Raihan_Research_Resume.pdf)

## Now

Large Model Inference Distributed System R&D Intern at Approaching.AI, a Tsinghua MADSys collaboration (Nov 2026 – present), working on Mooncake: the C++ transfer engine over RDMA and KV-cache offloading for agent RL rollouts. Also Research Intern at SJTU ReArch Lab on low-bit inference kernels in CUDA/Triton and FP8/FP4 KV-cache compression.

At InfiX.ai (Apr – Jun 2026) I ran production serving on 4× A800 and 8× H200 clusters. Three-tier KV-cache offload over Mooncake RDMA cut long-context time to first token 8.3× (55 s to 6.7 s) at a 92% cache hit rate, and 2+2 prefill/decode disaggregation raised stable concurrency from 192 to 256 requests.

## Selected work

| Repo | What it does |
| --- | --- |
| [nvfp4-dit](https://github.com/theraihanrakibb/nvfp4-dit) | 4-bit audio-guided video diffusion. FP4-packed Triton kernels are 3.2× faster than FP16 and use 4× less memory. First-author paper at IEEE TNNLS (under review). |
| [ai-infra-portfolio](https://github.com/theraihanrakibb/ai-infra-portfolio) | Ten Dockerized AI-infra services with CI and reproducible quickstarts. |
| [deepfake-av-detector](https://github.com/theraihanrakibb/deepfake-av-detector) | M.E. thesis: audio-visual deepfake detection with temporal inconsistencies. |
| [spark-ckks-query](https://github.com/theraihanrakibb/spark-ckks-query) | B.E. thesis: confidential queries over Spark with CKKS homomorphic encryption. |
| [train-launcher](https://github.com/theraihanrakibb/train-launcher) | Fault-tolerant multi-node PyTorch launcher with retry and checkpoint recovery. |

## Research

First author of "NVFP4-DiT: Efficient 4-Bit Audio-Guided Video Diffusion Transformers for Low-Cost Video Generation" (IEEE TNNLS, Q1, under review). My M.E. thesis at ASLP@NPU covers multimodal audio-visual deepfake detection. I'm studying the memory cost of long-context agent RL rollouts and how KV-cache compression with disaggregated serving could make them cheaper.

## Education

Northwestern Polytechnical University, Xi'an. M.E. Software Engineering 2024–2027 (GPA 88/100, rank 2/87); B.E. Computer Science 2020–2024 (GPA 85/100, rank 5/56, Outstanding Graduate). Chinese Government Scholarship 2024–2027, Presidential Scholarship 2020–2024, Wu Yajun Scholarship 2024, Best Undergraduate Thesis Award 2024, NWPU AI Challenge Hackathon winner 2023.

## Stack

Mooncake, SGLang, vLLM, RDMA, CUDA C++, Triton, FP8/FP4, PyTorch, C++, Python, Docker, Kubernetes, Linux.
