<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=26&duration=3200&pause=900&color=6C8CFF&center=true&vCenter=true&width=720&lines=Hi%2C+I'm+Ahmet+Yusuf+Bursal+%F0%9F%91%8B;AI+Engineer+%C2%B7+Agentic+Systems+%26+MCP;Agentspace+%C2%B7+Vertex+AI+%C2%B7+Claude;From+LLM+agents+to+FPGA+silicon;Rovers%2C+drones+and+autonomous+robotics" alt="Typing intro" />

**Computer Engineering @ Istanbul Medeniyet University**

I build **AI that actually ships** — enterprise agents, MCP integrations and retrieval pipelines —
and I go all the way down the stack to **C, Linux kernels, FPGAs and autonomous robots**.

<a href="https://www.linkedin.com/in/ahmet-yusuf-bursal-03324321b/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
<a href="https://aopcreativeagency.com/"><img src="https://img.shields.io/badge/Live_work-aopcreativeagency.com-111111?style=for-the-badge&logo=googlechrome&logoColor=white"></a>
<img src="https://komarev.com/ghpvc/?username=bursal0&style=for-the-badge&color=6C8CFF&label=PROFILE+VIEWS" />

</div>

---

## ⚡ What I do

```yaml
ai_engineering:   [LLM agents, multi-agent orchestration, tool routing, MCP servers, RAG, reranking]
enterprise_ai:    [Google Agentspace, Vertex AI, Gemini, Anthropic Claude, MCP servers, company-specific agents, CRM automation]
machine_learning: [PyTorch, JAX (vmap/jit on GPU), transfer learning, CNNs, gradient boosting, model serving]
full_stack:       [FastAPI, Flask, TypeScript, Cloudflare Workers/D1/R2, serverless, motion-heavy web]
systems:          [C, POSIX processes & IPC, shells, Linux kernel modules]
hardware:         [FPGA digital design, Raspberry Pi, embedded C, rovers, drones, autonomous navigation]
robotics_math:    [inverse kinematics, SVD, damped least squares, Levenberg–Marquardt, convergence analysis]
```

## 🏢 Experience

### 💼 AI & CRM Engineer — **Peranet**
*Enterprise AI · CRM platforms · Google Cloud · Anthropic Claude*

- 🤖 **Enterprise agentic AI on Google Agentspace** — architected and shipped **company-specific AI agents** for client organisations, grounded in each company's internal knowledge, documents and workflows
- 🔌 **Model Context Protocol (MCP) servers** — engineered custom MCP integrations that expose proprietary tools, data sources and business operations to agents through a standard, secure interface
- ☁️ **Google Vertex AI** — built generative-AI pipelines: prompt engineering, embeddings, batch prediction and multimodal inference on Gemini models
- 🧠 **Claude-based systems** — designed and integrated LLM solutions on Anthropic's Claude for production business use cases
- 🧩 **CRM & help-desk engineering** — developed, customised and automated CRM / service-desk platforms: workflow automation, data integration and AI-assisted customer operations

### 🛰️ Hardware, Robotics & Autonomy
- 🚗 **Autonomous rover** — end-to-end autonomy stack on Raspberry Pi: perception, decision-making and closed-loop motor control
- 🔲 **FPGA digital design** — hardware description, synthesis and on-board implementation of digital systems
- 🚁 **Rovers & UAVs** — built, integrated and programmed ground rovers and drones
- 🦾 **Robot kinematics research** — numerically stable IK near singularities, being prepared for real rover manipulators

### 📊 Data Science
- Extensive portfolio of notebooks and competition entries on **Kaggle** — feature engineering, gradient boosting and deep learning

---

## 🚀 Featured work

<table>
<tr>
<td width="50%" valign="top">

### 🦾 Robotics Research
- **[robot-ik-singularity-lab](https://github.com/bursal0/robot-ik-singularity-lab)** — numerically stable inverse kinematics near kinematic singularities. Convergence proofs (quadratic vs linear, closed-form contraction ρ = λ²/(σ²+λ²) matched to 6 decimals), adaptive SV & Levenberg–Marquardt damping, paired-bootstrap statistics, and **320,000-solve JAX/GPU workspace maps — 508× faster than NumPy**. Ships with an [interactive rover simulator ↗](https://bursal0.github.io/robot-ik-singularity-lab/) cross-validated **1026/1026** against the Python reference. Next stop: real rovers.

### 🧠 Agentic AI & Retrieval
- **[agenith-agent](https://github.com/bursal0/agenith-agent)** — modular agent architecture (Brain → Orchestrator → Tool Registry) with LLM-driven tool selection, retrieval-grounded PDF QA over FAISS, map-reduce whole-document reasoning and a quota-free automated test suite
- **[rag-pdf-chatbot](https://github.com/bursal0/rag-pdf-chatbot)** — hybrid retrieval-augmented generation: dense (FAISS + sentence embeddings) and sparse (BM25) retrieval combined by score fusion, followed by LLM cross-reranking and source-attributed, context-constrained answering

### 🔬 Deep Learning & ML
- **[cifar10-resnet18-classification](https://github.com/bursal0/cifar10-resnet18-classification)** — ImageNet-pretrained ResNet18 fine-tuned via transfer learning to **95.03 % test accuracy** (macro-F1 95.02 %), ~6.8 ms inference, failure-case analysis and out-of-distribution evaluation on real smartphone photos (6/6), served through Gradio
- **[mnist-mlp-handwritten-digit-recognition](https://github.com/bursal0/mnist-mlp-handwritten-digit-recognition)** — controlled ablation of MLP capacity and learning rate with a strict train/val/test protocol, plus domain-shift evaluation on my own handwriting
- **[SongRecommendation](https://github.com/bursal0/SongRecommendation)** — content-based recommender over 9-dimensional audio-feature space (standardised cosine similarity + genre prior), deployed full-stack with [live demo ↗](https://songrecommendation-production.up.railway.app/)
- **[house-price-api](https://github.com/bursal0/house-price-api)** — gradient-boosted regression (XGBoost) with log-target transformation and an end-to-end sklearn preprocessing pipeline, served as a production REST API

</td>
<td width="50%" valign="top">

### ⚙️ Systems Programming (C / POSIX)
- **[air-gapped-agency](https://github.com/bursal0/air-gapped-agency)** — fault-tolerant multi-agent orchestration without networking: fork/exec process supervision, `FD_CLOEXEC` startup-pipe handshakes, atomic rename-based publishing, single-writer file-mailbox IPC and crash recovery via PID liveness probing
- **[mining-robot](https://github.com/bursal0/mining-robot)** — autonomous exploration simulator with BFS shortest-path and **risk-weighted Dijkstra** planning, function-pointer policy dispatch, Minesweeper-style hazard sensing and an SDL2 renderer
- **[mini-shell](https://github.com/bursal0/mini-shell)** — Unix job-control shell: background process management, per-task log redirection and asynchronous status tracking

### 🌐 Production & Client Systems
- **[EDA Akademik Takip](https://github.com/bursal0/eda-akademik-takip-case-study)** — production education-operations platform on **Cloudflare Workers + D1 + R2** behind Cloudflare Access: server-side authorisation, relational data model, audit trails, verifiable backups and dual deployment environments
- **[AOP Creative Agency](https://github.com/bursal0/aop-agency-website-case-study)** — high-fidelity, scroll-driven motion website with a fail-closed edge-authenticated preview pipeline — [live ↗](https://aopcreativeagency.com/)

### 🔒 Private / NDA
- Company-specific **Agentspace agents & MCP servers** · **Vertex AI** pipelines · **Claude** integrations · **CRM** automation (Peranet)
- **Raspberry Pi autonomous rover** · **FPGA** designs · **drones**

</td>
</tr>
</table>

---

## 🛠️ Toolbox

<div align="center">

<img src="https://skillicons.dev/icons?i=python,c,ts,js,html,css,pytorch,sklearn,fastapi,flask,gcp,cloudflare,netlify,linux,raspberrypi,git,vscode&perline=9" />

</div>

## 📈 GitHub stats

<div align="center">
<img src="https://github-readme-stats.vercel.app/api?username=bursal0&show_icons=true&hide_border=true&count_private=true&theme=tokyonight" height="165" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=bursal0&layout=compact&hide_border=true&theme=tokyonight" height="165" />
</div>

<div align="center"><sub>Always building something — from prompts to processors.</sub></div>
