<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2563EB,50:06B6D4,100:10B981&height=170&section=header&text=AI%20Engineering%20%7C%20Inference%20%7C%20Agents&fontSize=30&fontColor=ffffff&animation=fadeIn&fontAlignY=38" width="100%" alt="AI Engineering, Inference, and Agents" />

# Pradeep K

### AI Engineer · Faster Inference · More Reliable Agents

I build efficient AI systems, from GPU kernels and LLM serving to grounded,
observable agent products.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/pradeepkarna)
[![GitHub](https://img.shields.io/badge/GitHub-111111?style=flat&logo=github&logoColor=white)](https://github.com/pradeek1120)
[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat&logo=huggingface&logoColor=111111)](https://huggingface.co/Pradeerock)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:pradeepkarna1120@gmail.com)

`Bengaluru, India` · Open to AI Engineer, AI Inference Engineer, LLM Engineer, and GenAI roles

[![Inference](https://img.shields.io/badge/Inference-2563EB?style=for-the-badge)](https://github.com/pradeek1120/llm-kernel-optimization-amd-mi355x)
[![Agents](https://img.shields.io/badge/Agents-06B6D4?style=for-the-badge)](https://github.com/pradeek1120/Multi-Agent-Productivity-Assistant)
[![Reliable AI](https://img.shields.io/badge/Reliable%20AI-10B981?style=for-the-badge)](https://github.com/pradeek1120/self-healing-rag)

</div>

## What I Build

| Fast Inference | Agentic Systems | Reliable ML Products |
| --- | --- | --- |
| ROCm, MI300X/MI355X, FP8, MXFP4, Triton, vLLM, profiling | RAG, LangGraph, Google ADK, MCP, multi-agent workflows | Evaluation, grounding, FastAPI, Docker, Cloud Run, Vertex AI |

I focus on the engineering details that make AI useful in the real world:
latency, cost, evaluation, reliability, and deployment.

## Featured Work

### ⚙️ [ProfiloAI - AMD GPU Performance Doctor](https://github.com/pradeek1120/profiloai)

An AI assistant for AMD ROCm developers. It reads profiler output or training
metrics, explains likely GPU bottlenecks, and suggests concrete optimizations.

**Explore:** [Live demo](https://huggingface.co/spaces/Pradeerock/profiloai) · [README](https://github.com/pradeek1120/profiloai/blob/main/README.md) · [SFT training](https://github.com/pradeek1120/profiloai/blob/main/training/04_finetune_sft.py) · [Benchmarking](https://github.com/pradeek1120/profiloai/blob/main/evaluation/benchmark_comparison.py)

`LoRA` `DPO` `MI300X` `ROCm` `vLLM` `Gradio`

### 🚀 [LLM Kernel Optimization on AMD MI355X](https://github.com/pradeek1120/llm-kernel-optimization-amd-mi355x)

A low-level inference case study covering MXFP4 GEMM, MoE MXFP4, and Mixed MLA
decode. It documents quantization-aware dispatch, runtime-path tuning, metadata
reuse, and benchmark-driven iteration while preserving correctness.

**Explore:** [README](https://github.com/pradeek1120/llm-kernel-optimization-amd-mi355x/blob/main/README.md) · [MXFP4 GEMM](https://github.com/pradeek1120/llm-kernel-optimization-amd-mi355x/blob/main/submissions/amd-mxfp4-mm/submission_v6.py) · [MoE MXFP4](https://github.com/pradeek1120/llm-kernel-optimization-amd-mi355x/blob/main/submissions/amd-moe-mxfp4/submission_v2.py) · [Mixed MLA](https://github.com/pradeek1120/llm-kernel-optimization-amd-mi355x/blob/main/submissions/amd-mixed-mla/submission_v5.py) · [Benchmark summary](https://github.com/pradeek1120/llm-kernel-optimization-amd-mi355x/blob/main/docs/benchmark-summary.md)

`FP8` `MXFP4` `GEMM` `Kernel Optimization` `Latency Benchmarking`

### 🛠️ [Self-Healing RAG Environment](https://github.com/pradeek1120/self-healing-rag)

An OpenEnv benchmark for agents working with stale or conflicting knowledge. The
agent detects hallucinations, identifies outdated sources, repairs the knowledge
base, and verifies corrected answers.

**Explore:** [Live demo](https://huggingface.co/spaces/Pradeerock/self-healing-rag) · [API docs](https://pradeerock-self-healing-rag.hf.space/docs) · [README](https://github.com/pradeek1120/self-healing-rag/blob/main/README.md) · [Inference](https://github.com/pradeek1120/self-healing-rag/blob/main/inference.py) · [Task suite](https://github.com/pradeek1120/self-healing-rag/blob/main/tasks.py)

`RAG Evaluation` `OpenEnv` `Grounding` `AI Safety`

### 🤖 [Multi-Agent Productivity Assistant](https://github.com/pradeek1120/Multi-Agent-Productivity-Assistant)

An API-first assistant that turns a natural-language goal into a structured
workflow. Agents retrieve context, plan work, create tasks and notes, schedule
calendar events, and return clean results through FastAPI.

**Explore:** [README](https://github.com/pradeek1120/Multi-Agent-Productivity-Assistant/blob/main/README.md) · [Agent workflow](https://github.com/pradeek1120/Multi-Agent-Productivity-Assistant/blob/main/productivity_agent/agent.py) · [MCP tools](https://github.com/pradeek1120/Multi-Agent-Productivity-Assistant/blob/main/toolbox/tools.yaml)

`FastAPI` `Gemini` `Google ADK` `MCP` `AlloyDB`

## Technical Toolkit

| Area | Tools |
| --- | --- |
| Languages | Python · C++ · C · SQL · R |
| ML | PyTorch · Transformers · PEFT · TRL · Scikit-learn · XGBoost |
| LLM and agents | LangChain · LangGraph · LlamaIndex · Google ADK · MCP · CrewAI |
| Serving | ROCm · Triton Inference Server · vLLM · Docker · FastAPI · Redis |
| Cloud | Cloud Run · Vertex AI · AlloyDB · Azure OpenAI |

## Currently Exploring

- FlashAttention, KV-cache optimization, Triton, and vLLM internals
- Distributed inference, serving systems, and ML systems design
- Evaluation methods for grounded and reliable AI agents

---

> Building efficient, scalable AI systems, from GPU kernels to intelligent agents.
