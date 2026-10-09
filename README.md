### Hi, I'm Nish 👋

**I build AI systems that people actually end up using.**

Most of my work starts the same way: I go sit with the people doing the work by hand, figure out what they actually need, and then build something reusable instead of a one-off. Agentic LLM platforms, RAG, computer vision in production. The model is usually the easy part. Getting a team to trust it and adopt it is the job.

I'm finishing an MS in Information Systems Management at **Carnegie Mellon** (Cooper Fellow, Dec 2026), and I'm looking for **Forward Deployed Engineer / Applied AI** roles, where building and talking to customers are the same job. Open to relocating.

---

### Where I've had impact

**BNY · AI Hub** (AI/ML Engineer Intern, 2026)
Took a document-extraction pipeline that every team wired up differently and turned it into a self-service platform for building agents. Business teams describe a workflow, and the platform assembles, secures and ships the agent.
- 25+ agents across 6 production use cases, 10+ live deployments
- New use-case onboarding cut from **a week to a day**
- An estimated **155K analyst hours a year** saved
- Found and fixed four silent failure modes nobody had flagged (access, context, tool scope, secrets), then added a review loop where every human correction becomes improvement data

**Slamdunk.AI** (Founding AI/ML Engineer, ~2.5 years)
Joined an AI sports-coaching startup as an intern and left leading its recommendation team.
- Real-time athlete tracking (YOLOv8, MediaPipe, ONNX) at 96% detection accuracy, with cloud costs down 70%
- Wasn't happy with the coaching recommender I'd built, so I went and talked to tennis coaches, then rebuilt it: feedback latency went from 3 minutes to under 15 seconds
- Led a 3-person team that shipped the production MVP in 3 months

**Research**
- Now: keeping LLM agents from taking actions they shouldn't (OWASP LLM06, Excessive Agency). Graph-based access control on top of LLM Guard, red-teamed with AgentDojo.
- Published: graph neural networks for predicting which drugs cross the blood-brain barrier ([IEEE 2023](https://doi.org/10.1109/ICACITE57410.2023.10182598)).

---

### How I work

1. **Go to the user first.** Ops teams, tennis coaches, a pharma analyst: the best spec I ever get comes from watching someone do the job.
2. **Don't trust "it works."** A 0.935 mAP model that missed the ball in over 90% of real frames taught me to evaluate on the real thing, not the validation set.
3. **Build it so the next one is easier.** A fix that only helps one use case is a patch. The goal is a platform.

---

### 🔭 Side projects

Most of my professional work lives in private codebases. These are smaller things I build to learn and to scratch an itch, so they're a glimpse of how I think rather than a full picture.

| | |
|---|---|
| [**⛳ SwingTrace**](https://github.com/nishsm/swingtrace) | Open-source golf swing tracer. Tracks the club through motion blur in 93% of frames on unseen phone videos. [Try it in Colab](https://colab.research.google.com/github/nishsm/swingtrace/blob/main/notebooks/swingtrace_quickstart.ipynb) · [Model](https://huggingface.co/nishsm/swingtrace) |
| [**Autonomous SOC agent**](https://github.com/nishsm/autonomous-soc-agent) | Two LangGraph agents for security operations. One flags anomalous network traffic, the other drafts a recovery plan using a local LLM and a playbook knowledge base. |
| [**🧠 BBBNet**](https://github.com/nishsm/bbbnet) | Reproducible version of my IEEE paper: will this drug reach the brain? Graph neural network on 7K+ molecules. |
| [**golf-ball-tracking**](https://github.com/nishsm/golf-ball-tracking) | Write-up of the "great validation score, useless in production" lesson, and the YOLO + SAM 2 tracker built after it. |

---

**Stack I reach for:** Python · TypeScript · LangGraph · MCP · RAG · PyTorch · YOLO · SAM 2 · FastAPI · Docker · AWS

📫 [LinkedIn](https://www.linkedin.com/in/nishanthsm01/) · nishanthsm01@gmail.com · Pittsburgh, PA
