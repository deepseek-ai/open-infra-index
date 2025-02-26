<!-- markdownlint-disable first-line-h1 -->
<!-- markdownlint-disable html -->
<!-- markdownlint-disable no-duplicate-header -->

<div align="center">
  <img src="https://github.com/deepseek-ai/DeepSeek-V2/blob/main/figures/logo.svg?raw=true" width="60%" alt="DeepSeek-Open-Infra" />
</div>
<hr>

# Hello, DeepSeek Open Infra!

## 202502 Open-Source Week
We're a tiny team @deepseek-ai pushing our limits in AGI exploration.

Starting **this week** , Feb 24, 2025 we'll open-source 5 repos – one daily drop – not because we've made grand claims, 
but simply as developers sharing our small-but-sincere progress with full transparency.

These are humble building blocks of our online service: documented, deployed and battle-tested in production. 
No vaporware, just sincere code that moved our tiny yet ambitious dream forward.

Why? Because every line shared becomes collective momentum that accelerates the journey.
Daily unlocks begin soon. No ivory towers - just pure garage-energy and community-driven innovation 🔧

Stay tuned – let's geek out in the open together.

### Day 1 - [FlashMLA](https://github.com/deepseek-ai/FlashMLA)
**Efficient MLA Decoding Kernel for Hopper GPUs**  
Optimized for variable-length sequences, battle-tested in production  

🔗 <a href="https://github.com/deepseek-ai/FlashMLA"><b>FlashMLA GitHub Repo</b></a>  
✅ BF16 support  
✅ Paged KV cache (block size 64)  
⚡ Performance: 3000 GB/s memory-bound | BF16 580 TFLOPS compute-bound on H800

### Day 2 - [DeepEP](https://github.com/deepseek-ai/DeepEP)

Excited to introduce **DeepEP** - the first open-source EP communication library for MoE model training and inference.

🔗 <a href="https://github.com/deepseek-ai/DeepEP"><b>DeepEP GitHub Repo</b></a>  
✅ Efficient and optimized all-to-all communication  
✅ Both intranode and internode support with NVLink and RDMA  
✅ High-throughput kernels for training and inference prefilling  
✅ Low-latency kernels for inference decoding  
✅ Native FP8 dispatch support  
✅ Flexible GPU resource control for computation-communication overlapping  

### Day 3 - [DeepGEMM](https://github.com/deepseek-ai/DeepGEMM)

Introducing DeepGEMM - an FP8 GEMM library that supports both dense and MoE GEMMs, powering V3/R1 training and inference.

⚡ Up to 1350+ FP8 TFLOPS on Hopper GPUs
✅ No heavy dependency, as clean as a tutorial
✅ Fully Just-In-Time compiled
✅ Core logic at ~300 lines - yet outperforms expert-tuned kernels across most matrix sizes
✅ Supports dense layout and two MoE layouts

🔗 GitHub: https://github.com/deepseek-ai/DeepGEMM



### Ongoing Releases...

## 2024 AI Infrastructure Paper (SC24)   
### Fire-Flyer AI-HPC: A Cost-Effective Software-Hardware Co-Design for Deep Learning

<a href="https://dl.acm.org/doi/10.1109/SC41406.2024.00089"><b>📄 Paper Link</b></a>
<a href="https://arxiv.org/abs/2408.14158"><b>📄 Arxiv Paper Link</b></a>
