# Pradeep K

### AI Engineer focused on inference, ML systems, and intelligent agents

I build production-minded AI systems: from GPU kernels and LLM serving to grounded, observable agent workflows.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/pradeepkarna)
[![GitHub](https://img.shields.io/badge/GitHub-111111?style=flat&logo=github&logoColor=white)](https://github.com/pradeek1120)
[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat&logo=huggingface&logoColor=111111)](https://huggingface.co/Pradeerock)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:pradeepkarna1120@gmail.com)

`Bengaluru, India` | Open to AI Engineer, AI Inference Engineer, LLM Engineer, and GenAI roles

---

## What I Work On

| Inference & GPU | LLM & Agents | Reliable ML Systems |
| --- | --- | --- |
| ROCm, MI300X/MI355X, FP8, MXFP4, Triton, vLLM, profiling | RAG, LangGraph, Google ADK, MCP, multi-agent workflows | Evaluation, grounding, FastAPI, Docker, Cloud Run, Vertex AI |

I am an AI/ML graduate interested in the engineering details that make AI useful in the real world: latency, cost, evaluation, reliability, and deployment.

## Featured Projects

### [ProfiloAI - AMD GPU Performance Doctor](https://github.com/pradeek1120/profiloai)

An AI assistant for AMD ROCm developers. It reads profiler output or training metrics, explains the likely GPU bottleneck in plain English, and suggests a concrete optimization. The project includes MI300X fine-tuning, DPO alignment, evaluation, vLLM serving, and a Gradio demo.

**Explore:** [README](https://github.com/pradeek1120/profiloai/blob/main/README.md) · [SFT training](https://github.com/pradeek1120/profiloai/blob/main/training/04_finetune_sft.py) · [Benchmarking](https://github.com/pradeek1120/profiloai/blob/main/evaluation/benchmark_comparison.py)

`LoRA` `DPO` `MI300X` `ROCm` `vLLM` `Gradio`

### [LLM Kernel Optimization on AMD MI355X](https://github.com/pradeek1120/llm-kernel-optimization-amd-mi355x)

A low-level inference case study built around three AMD GPU workloads: MXFP4 GEMM, MoE MXFP4, and Mixed MLA decode. It documents how quantization-aware kernel dispatch, runtime-path tuning, metadata reuse, and benchmark-driven iteration improved latency while preserving correctness.

**Explore:** [README](https://github.com/pradeek1120/llm-kernel-optimization-amd-mi355x/blob/main/README.md) · [MXFP4 GEMM](https://github.com/pradeek1120/llm-kernel-optimization-amd-mi355x/blob/main/submissions/amd-mxfp4-mm/submission_v6.py) · [MoE MXFP4](https://github.com/pradeek1120/llm-kernel-optimization-amd-mi355x/blob/main/submissions/amd-moe-mxfp4/submission_v2.py) · [Mixed MLA](https://github.com/pradeek1120/llm-kernel-optimization-amd-mi355x/blob/main/submissions/amd-mixed-mla/submission_v5.py) · [Benchmark summary](https://github.com/pradeek1120/llm-kernel-optimization-amd-mi355x/blob/main/docs/benchmark-summary.md)

*The repository is currently private, so viewers need access to open these project files.*

`FP8` `MXFP4` `GEMM` `Kernel Optimization` `Latency Benchmarking`

### [Self-Healing RAG Environment](https://github.com/pradeek1120/self-healing-rag)

An OpenEnv benchmark for agents that work with stale or conflicting knowledge. The agent must detect a hallucination, identify the outdated source document, repair the knowledge base, and verify the corrected answer. Ground-truth labels stay hidden from the agent to make the evaluation meaningful.

**Explore:** [README](https://github.com/pradeek1120/self-healing-rag/blob/main/README.md) · [Agent inference](https://github.com/pradeek1120/self-healing-rag/blob/main/inference.py) · [Task suite](https://github.com/pradeek1120/self-healing-rag/blob/main/tasks.py)

`RAG Evaluation` `OpenEnv` `Grounding` `AI Safety`

### [Multi-Agent Productivity Assistant](https://github.com/pradeek1120/Multi-Agent-Productivity-Assistant)

An API-first assistant that turns a natural-language goal into a structured workflow. Its agents retrieve context, plan the work, create tasks and notes, schedule calendar events, and return a clean result through a FastAPI endpoint. The system uses Gemini, Google ADK, MCP Toolbox, AlloyDB, and Cloud Run.

**Explore:** [README](https://github.com/pradeek1120/Multi-Agent-Productivity-Assistant/blob/main/README.md) · [Agent workflow](https://github.com/pradeek1120/Multi-Agent-Productivity-Assistant/blob/main/productivity_agent/agent.py) · [MCP tools](https://github.com/pradeek1120/Multi-Agent-Productivity-Assistant/blob/main/toolbox/tools.yaml)

`FastAPI` `Gemini` `Google ADK` `MCP` `AlloyDB`

## Toolkit

**Languages:** Python, C++, C, SQL, R  
**ML:** PyTorch, Transformers, PEFT, TRL, Scikit-learn, XGBoost  
**LLM:** LangChain, LangGraph, LlamaIndex, Google ADK, MCP, CrewAI  
**Serving:** ROCm, Triton Inference Server, vLLM, Docker, FastAPI, Redis  
**Cloud:** Cloud Run, Vertex AI, AlloyDB, Azure OpenAI

## Credentials & Current Focus

- Oracle Cloud Infrastructure Generative AI Professional
- NVIDIA: Building RAG Agents with LLMs; Fundamentals of Deep Learning
- Exploring FlashAttention, KV-cache optimization, Triton, vLLM internals, distributed serving, and ML systems design

---

> Building efficient, scalable, and production-ready AI systems, from GPU kernels to intelligent agents.
