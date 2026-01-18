# Aman Jaglan

### Building agents that learn continuously from production

**Co-Founder & CTO at [Marshmallo AI](https://marshmallo.ai)**

[Research](https://arxiv.org/abs/2511.01093) · [Arc Research](https://www.arc.computer/research) · [ATLAS Docs](https://docs.arc.computer) · [HuggingFace](https://huggingface.co/arc-intelligence)

---

## Current

At Marshmallo, building the **Continual Agentic Learning Platform**. Agents observe, evaluate, learn, and deploy in a closed loop. Intelligence compounds over time instead of staying static after deployment.

| Observe | Evaluate | Learn |
|---------|----------|-------|
| Capture every step, tool call, reasoning and action. | Score each task using LLM judges. | Generate learnings that deploy back into the agent. |

---

## Research

**[Continual Learning, Not Training: Online Adaptation For Agents](https://arxiv.org/abs/2511.01093)**
*Aman Jaglan, Jarrod Barnes*

ATLAS achieves 54.1% success with GPT-5-mini as Student, outperforming GPT-5 (High) by 13% while reducing cost by 86%. Cross-validation improves accuracy from 28% to 41% without retraining.

---

## Previous — Arc Computer

Built [ATLAS](https://github.com/arc-computer/ATLAS) and [Atlas SDK](https://github.com/arc-computer/atlas-sdk), an open-source continual learning framework for production LLM agents.

| Component | What it does |
|-----------|--------------|
| **Reinforced Continual Learning** | Teacher-Student framework. Teachers generate thinking traces to guide Students. Cross-domain transfer without domain-specific fine-tuning. |
| **Cross-Domain Learning** | Teacher trained on mathematics (46% on AIME-25), transfers reasoning to enterprise tasks. |
| **Inference-Time Adaptation** | 54.1% task success vs GPT-5 High's 48.0% at 86% lower cost. Gradient-free, runtime adaptation. |
| **On-Policy Distillation** | 10x more compute-efficient than RL. Two-gear training pattern for production. |
| **Atlas SDK** | Runtime wrapper capturing causality traces. Enables offline training via GRPO and GKD. |

**Results**: +15.7% accuracy, +31% task completion, 97% non-degradation rate.

---

## Focus

- Continual learning for autonomous agents
- Reinforcement learning from production feedback
- Knowledge distillation and transfer
- Agent reliability at scale
