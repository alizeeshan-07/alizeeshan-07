# Hi, I'm Ali Zeeshan 👋

**Head of AI @ Adept Tech Solutions · Agentic AI, Optimization Agents, LLMs & Fine-tuning · Independent AI Consultant**

[![Website](https://img.shields.io/badge/Website-131718?style=flat&logo=hugo&logoColor=white)](https://alizeeshan-07.github.io/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ali-zeeshan-49596660/)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-FFD21E?style=flat&logoColor=black)](https://huggingface.co/alizeeshan-07)
[![Upwork](https://img.shields.io/badge/Upwork-6FDA44?style=flat&logo=upwork&logoColor=white)](https://www.upwork.com/freelancers/alizeeshan)

**Research scientist working on closed-loop AI systems that learn under hard physical, communication, and cost budgets — engineered end-to-end and backed by provable guarantees.**

I sit at the intersection of wireless systems engineering, machine learning theory, foundation models, and edge/federated deployment. My work follows one organizing idea:

> **The timescale hierarchy.** Slow reasoners (LLM agents, seconds) handle intent and planning. Fast learned controllers (multi-agent RL, milliseconds) handle scheduling and resource allocation. Control theory (constrained MDPs, Lyapunov analysis, barrier functions, conformal prediction) guarantees safety at every timescale. Digital twins are where everything is trained and certified before touching reality.

In short: **the learning does the optimizing, the mathematics does the promising.**

---

## 🔭 Currently

- 🤖 Building **agentic AI systems** and **agents for optimization** @ Adept Tech Solutions — multi-agent orchestration, tool-use agents, MCP, LLM-in-the-loop decision systems
- 🧠 **Fine-tuning and adapting LLMs** for production — LoRA/QLoRA, RL fine-tuning of agents, quantized deployment on edge hardware
- 🛡️ Attaching **provable guarantees** to learned controllers and agents — constrained MDPs, Lyapunov stability, barrier filters, conformal prediction
- 📡 **Deep RL for CR-NOMA backscatter communication** (PhD research @ NUST)

---

## 🔬 Research interests

| Theme | What I work on |
|---|---|
| 🤖 **Agentic AI & reasoning models** | Training LLM agents (RL fine-tuning, RLVR, process reward models, tool use) rather than only prompting them; inference-time compute allocation — when to think, how long, on which model |
| 🎯 **Agents for optimization** | LLM strategists above learned controllers, token-budgeted decision making, cost-aware routing and cascades as budgeted MDPs |
| 🛡️ **Safe & verifiable autonomy** | CMDPs, Lyapunov/ISS stability, control barrier functions & safety filters, conformal guarantees for learned controllers and LLM agents |
| 📡 **AI-native 6G / AI-RAN** | DRL/MARL schedulers, LLM intent layers, digital-twin-in-the-loop network control (3GPP Rel-20/21, IMT-2030 window) |
| ⚡ **Edge AI & efficient inference** | Device–edge–cloud cascades and escalation, quantized small models, system-level efficiency (budgets, caching, energy) |
| 🌍 **World models & digital twins** | Learned simulators, twins as agent gyms, sim-to-real with causal analysis |
| 🕸️ **Multi-agent RL** | Cooperative MARL (QMIX/MAPPO) for distributed resource allocation, swarms, and UAV coordination |
| 🔗 **Distributed & federated learning** | Federated LoRA/PEFT for device and agent fleets under wireless constraints |
| 📖 **Modern retrieval topologies** | Agentic RAG, retrieval as a budgeted action, groundedness guarantees |

**Application domains:** satellite–terrestrial networks · UAV swarms and the low-altitude economy · integrated sensing and communication (ISAC) · IoT and industrial edge

---

## 🧰 Toolbox

**ML/RL:** `PyTorch` · `QMIX/MAPPO (EPyMARL, BenchMARL)` · `PPO/SAC` · `verl/TRL` · `HF Transformers / PEFT` · `LoRA/QLoRA` · `AWQ/GPTQ`

**Agents & LLM systems:** `LangGraph` · `CrewAI` · `MCP` · `RouteLLM` · multi-agent orchestration · tool-use & function calling

**Wireless & twins:** `NVIDIA Sionna` · `Aerial Omniverse Digital Twin (AODT)` · `cuMAC` · `OpenNTN (3GPP TR 38.811)` · `Hypatia` · `srsRAN/OAI`

**Edge & serving:** `vLLM` · `llama.cpp` · `ExecuTorch` · `Jetson Orin` · `SmolVLM / Qwen-VL` class models

**Control & guarantees:** `CBF-QP safety filters (OSQP/cvxpy)` · constrained MDPs · conformal prediction · two-timescale stochastic approximation

**Methodology:** pre-registered hypotheses · explicit ablations · causal DAGs · validated LLM-as-judge evaluation · negative results treated as results

---

## 📄 Selected work

- **Coupled Composite Barrier (CCB)** — safety-constrained trajectory optimization for UAV-ISAC systems. Heterogeneous constraints (radar detection probability, CRB localization accuracy, no-fly zones) are aggregated into a single smooth barrier via softmin and enforced by a QP that minimally modifies deep-RL actions at deployment time. *(venue & link coming)*
- **TwinLoopLLM** — closed-loop digital-twin RAN scheduling: a token-budgeted LLM strategist over cooperative MARL schedulers, with intent-as-observation, two-timescale stability under bounded intent staleness, and a CMDP-optimal query rate. *(venue & link coming)*
- *(more coming — watch this space)*

---

## 📚 Currently learning

- **Large reasoning models** — RLVR/GRPO pipelines, process reward models, test-time scaling and budget forcing
- **LLM pretraining from scratch** — small-scale, aimed at domain foundation models (RF/telemetry), not frontier chasing
- **Edge AI deployment** — on-device training and adaptation, NPU profiling, energy-aware inference

Every track ends in an artifact — a from-scratch reproduction, a benchmarked system, or a paper. Never a course certificate.

---

## 🤝 Open to

Collaborations on guarantee-bearing learning systems (wireless, robotics, edge AI), reviewing for ML and communications venues, and conversations about safe autonomy in deployed systems.

📫 **Reach me:** [alphaops@adept-techsolutions.com](mailto:alphaops@adept-techsolutions.com) · [Website](https://alizeeshan-07.github.io/) · [LinkedIn](https://www.linkedin.com/in/ali-zeeshan-49596660/) · [Hugging Face](https://huggingface.co/alizeeshan-07)

---

*"Never propose an LLM where a millisecond control policy belongs — and never ship a learned controller without a certificate."*
