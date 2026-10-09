### Hi, I'm Nish 👋

I'm an AI/ML engineer. I build agentic LLM systems and computer vision pipelines, and I care whether the teams using them actually adopt them. I'm finishing my MS in Information Systems Management at **Carnegie Mellon** (Dec 2026) as a Cooper Fellow, and I'm looking for **Forward Deployed / Applied AI** roles.

- 🏦 **BNY AI Hub** (AI/ML Engineer Intern, 2026). Turned a document-extraction pipeline into a self-service agent-builder platform: 25+ agents across 6 production use cases, onboarding cut from a week to a day, ~155K analyst hours a year saved.
- 🎾 **Slamdunk.AI** (Founding AI/ML Engineer). Real-time athlete tracking (YOLOv8, MediaPipe, ONNX) and a RAG coaching recommender. Joined as an intern and ended up leading the recommendation team.
- ⛳ **Open-source golf CV.** Golf ball and club detection and swing-path tracking from phone video (YOLO11, SAM 2).
- 🛡️ **Research.** Mitigating Excessive Agency (OWASP LLM06) in LLM agents: graph-based access control and ABAC on top of LLM Guard, benchmarked with AgentDojo.
- 🧪 **Published.** GNNs for blood-brain barrier permeability prediction, [IEEE 2023](https://doi.org/10.1109/ICACITE57410.2023.10182598) (88.7% test accuracy, 0.96 AUROC). [Reproducible code](https://github.com/nishsm/bbb-gcn).

---

### 📌 Featured projects

| Project | What it does | Stack |
|---|---|---|
| [**⛳ SwingTrace**](https://github.com/nishsm/swingtrace) | Open-source golf swing tracer: finds the club shaft, head and hands in phone video and rebuilds the club-head path through motion blur. Tracks the club in **93% of frames** on unseen videos. [Colab demo](https://colab.research.google.com/github/nishsm/swingtrace/blob/main/notebooks/swingtrace_quickstart.ipynb) · [Model](https://huggingface.co/nishsm/swingtrace) | YOLO11, PyTorch, OpenCV, Hugging Face |
| [**golf-ball-tracking**](https://github.com/nishsm/golf-ball-tracking) | Why a 0.935 mAP@50-95 ball detector found the ball in under 10% of real frames, and the hybrid YOLO + SAM 2 tracker built after that. | YOLO11, SAM 2, PyTorch |
| [**Blood-brain barrier GNN**](https://github.com/nishsm/bbb-gcn) | Graph convolutional networks that predict which drug molecules cross the blood-brain barrier, to speed up Alzheimer's drug screening. Built with a Dr. Reddy's research analyst. | PyTorch, RDKit, GCN, scikit-learn |
| [**Autonomous SOC agent**](https://github.com/nishsm/autonomous-soc-agent) | Two-agent security-operations pipeline: an observer flags anomalous network flows (Isolation Forest trained on CICIDS2017), and a planner drafts incident recovery plans with a local LLM grounded in a FAISS playbook knowledge base. | LangGraph, scikit-learn, FAISS, Ollama |
<!-- ADD: resume-tailoring tool (local LLM, Ollama) if public -->

---

### 🧰 Tech

**LLM and agents:** LangGraph · MCP · tool calling · RAG · FAISS · LoRA fine-tuning · structured outputs · guardrails · Ollama
**Computer vision:** YOLO (v8, 11) · SAM 2 · MediaPipe · ONNX · OpenCV · object tracking
**ML:** PyTorch · TensorFlow · PyTorch Geometric · scikit-learn
**Engineering:** Python · TypeScript · SQL · C++ · FastAPI · Docker · AWS · Playwright

---

📫 [LinkedIn](https://www.linkedin.com/in/nishanthsm01/) · nishanthsm01@gmail.com · Pittsburgh, PA
