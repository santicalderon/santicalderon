# Hey, I'm Santiago 👋

**AI Systems Builder · Performance marketer turned autonomous infrastructure engineer · Copenhagen**

> I ran paid media at agency scale for 2 years. Then I spent 6 months building the system that should have existed.

I designed and shipped a production-grade multi-agent AI platform from scratch — solo, no team, no budget. It runs 24/7 on dedicated infrastructure, generates content autonomously, writes and repairs its own code, and monitors its own health without human intervention.

[Portfolio](https://kernel.mi-kernel2026.xyz) · [LinkedIn](https://www.linkedin.com/in/santiagocalderongonzalez/)

---

## 🚀 What I Ship

- **Autonomous AI systems** — multi-agent orchestration, stigmergy coordination, no central controller
- **Self-healing infrastructure** — agents that write, test, and repair their own code iteratively
- **LLM routing + cost control** — intelligent caching, budget gates, 64% cost reduction in production
- **Production pipelines** — not demos, not POCs — systems with uptime, real outputs, and measurable outcomes

---

## 🏆 Highlighted Work

[autonomous-ai-platform](https://github.com/santicalderon/autonomous-ai-platform) — multi-agent platform built solo in 6 months. Self-healing code loops, D16 autonomous codebase maintenance, stigmergy coordination. 24 videos published, $0 ad spend. Found the system lying to me — rearchitected the measurement layer. Still running.

[burnstop](https://github.com/santicalderon/burnstop) — pre-flight budget gate for AI agent runaways. Hard-stop before token-1. Drop-in adapters for LangChain, LangGraph, AutoGen, CrewAI. Because the model that loops is the same one you'd ask to self-throttle.

[claude-memory-mcp](https://github.com/santicalderon/claude-memory-mcp) — cross-session persistent memory for Claude Code via MCP. Git-tracked, markdown-native.

[agentic-receipts](https://github.com/santicalderon/agentic-receipts) — DID-signed audit trail for autonomous agent actions. EU AI Act / SOC2 / ISO 42001 ready. Pure stdlib.

---

## 📝 What I learned building in production

- **Theater vs output**: a system can look active (logs, graphs, crons firing) while producing zero real outcomes. I found this inside my own platform and rearchitected the measurement layer from scratch. Every signal now has to prove a real output exists, not just that a process ran.
- **Race conditions at scale**: 60+ concurrent cron jobs colliding — solved with fcntl mutex + O_EXCL atomic file claims
- **LLM cost blowups**: multi-tier routing + intelligent caching layer → 64% cost reduction without degrading output quality

---

📍 Copenhagen, Denmark · EU citizen · Open to AI/automation roles in Europe or remote  
📧 calderonsantiago98@gmail.com
