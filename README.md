<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:09090b,50:18181b,100:27272a&height=150&section=header&text=Syed%20Sarim%20Ahsan&fontSize=38&fontColor=fafafa&fontAlignY=42&desc=AI%20Research%20Engineer%20%C2%B7%20LLM%20Systems%20%C2%B7%20Kernel%20Optimization&descSize=13&descColor=a1a1aa&descAlignY=64&animation=fadeIn"/>
</div>

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-09090b?style=flat-square&logo=vercel&logoColor=white)](https://syedsarimahsan.netlify.app/)&nbsp;
[![Google Scholar](https://img.shields.io/badge/Google_Scholar-4285F4?style=flat-square&logo=google-scholar&logoColor=white)](https://scholar.google.com/citations?user=rI6n0xoAAAAJ&hl=en)&nbsp;
[![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/sarimahsan101)&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/syed-sarim-ahsan-544198247/)&nbsp;
[![ORCID](https://img.shields.io/badge/ORCID-A6CE39?style=flat-square&logo=orcid&logoColor=white)](https://orcid.org/0009-0003-2878-6754)&nbsp;
[![ResearchGate](https://img.shields.io/badge/ResearchGate-00CCBB?style=flat-square&logo=researchgate&logoColor=white)](https://www.researchgate.net/profile/Syed-Sarim-Ahsan)&nbsp;
[![Medium](https://img.shields.io/badge/Medium-12100E?style=flat-square&logo=medium&logoColor=white)](https://medium.com/@sarim.ahsan101)

</div>

<br/>

AI Research Engineer and Computer Engineering undergraduate at SSUET, working as a Data Science Intern at 10Pearls and an Application Support Engineer at GIS. My research focuses on **LLM Optimization & Efficient Inference**, **GPU Kernel Acceleration**, **Post-Training Alignment**, and **Mechanistic Interpretability**.

I study and implement intelligent systems from first principles — spanning custom OpenAI Triton and CUDA C++ kernels, GPU inference acceleration engines, post-training alignment (GRPO, DPO), and empirical hidden-state probing.

<br/>

<div align="center">

`5,600+ Open-Source Downloads` &nbsp;•&nbsp; `4+ Research Papers` &nbsp;•&nbsp; `7+ Systems & ML Projects` &nbsp;•&nbsp; `PyPI Author (interplens)`

</div>

<br/>

---

### 🔬 Research & Engineering Focus

- **LLM Systems & Inference**: Paged attention, prefix caching, KV-cache continuity, depth-adaptive inference, speculative decoding, and vLLM acceleration.
- **Kernel & GPU Engineering**: Custom OpenAI Triton and CUDA C++ kernels, NVIDIA Nsight Compute (`ncu`) profiling, shared memory tiling, online softmax, and CUDA Graphs.
- **Post-Training & Alignment**: Group Relative Policy Optimization (GRPO), Direct Preference Optimization (DPO), RLHF reward engineering, and knowledge distillation.
- **Empirical Interpretability & Probing**: Internal hidden-state linear probing, pre-generation hallucination detection, logit lens, and activation-normalization interaction dynamics.

<br/>

---

### 🛠️ Technical Stack

```
Languages     : Python, C++, C, CUDA C++, SQL, Bash
ML & Kernels  : PyTorch, OpenAI Triton, CUDA, Hugging Face (TRL, Transformers, PEFT), vLLM, AMD ROCm
Profiling     : NVIDIA Nsight Compute (NCU), PyTorch Profiler, CUDA Graphs
Agentic AI    : LangGraph, LangChain, RAG / CRAG, FAISS
Backend & DB  : FastAPI, Node.js, PostgreSQL, Redis, Docker, Linux, Git, CI/CD
```

<br/>

---

### 📚 Selected Open-Source & Research Highlights

- **[miniflash-triton](https://github.com/sarimahsan/miniflash-triton)**: Paged, prefix-sharing LLM inference core in OpenAI Triton and PyTorch featuring fused prefill attention, zero-copy paged GQA decode, INT8 KV cache, and CUDA-graph replay (1.47× faster batch-1 decode, 2.2× batch-32 throughput, 8.4× lower TTFT on NVIDIA L4).
- **[Kernix](https://github.com/sarimahsan/Kernix)**: Profiler-grounded GPU kernel optimization engine trained on 490K+ Nsight Compute (`ncu`) hardware executions across T4, L4, A100, and Blackwell, powering **[Kernix-14B](https://huggingface.co/sarimahsan101/Kernix-14B)** and **[Kernix-3B](https://huggingface.co/sarimahsan101/Kernix-3B)**.
- **[FastTransformer](https://github.com/sarimahsan/transformer-cuda)** & **[CUDA ML Framework](https://github.com/sarimahsan/cuda-ml-from-scratch)**: Pure CUDA C++ deep learning primitives (2D tiled GEMM, online FlashSoftmax, Welford norm, fused 4-gate LSTM) and hardware-aligned Transformer co-design reaching 1.45× speedup over `torch.compile`.
- **[InterpLens](https://pypi.org/project/interplens/)**: Open-source mechanistic interpretability toolkit (`pip install interplens`) for zero-copy residual stream extraction, logit lens projection, and causal patching ([GitHub](https://github.com/sarimahsan/interplens)).
- **[KV-Cache Continuity in Depth-Adaptive Transformers](https://doi.org/10.13140/RG.2.2.10326.00329)**: Preprint introducing a teacher-forced disentanglement protocol separating attention memory poisoning from readout mismatch via Native Projection and affine repair ([Code](https://github.com/sarimahsan/kv-cache-continuity)).
- **[Qwen2.5-3B GRPO Alignment](https://huggingface.co/sarimahsan101/qwen2.5-3b-grpo-gsm8k)**: LoRA-finetuned reasoning model trained with Group Relative Policy Optimization on GSM8K with verifiable XML reasoning traces.

<br/>

---

### 📊 GitHub Activity

<div align="center">

<img height="150" src="https://github-readme-stats.vercel.app/api?username=sarimahsan&show_icons=true&theme=dark&bg_color=09090b&title_color=f4f4f5&icon_color=a1a1aa&text_color=d4d4d8&border_color=27272a&hide_border=false&count_private=true" />
&nbsp;&nbsp;
<img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sarimahsan&layout=compact&theme=dark&bg_color=09090b&title_color=f4f4f5&text_color=d4d4d8&border_color=27272a&hide_border=false&langs_count=6" />

</div>

<br/>

---

<div align="center">
  <sub>© 2026 Syed Sarim Ahsan &bull; <a href="https://syedsarimahsan.netlify.app/">syedsarimahsan.netlify.app</a></sub>
</div>
