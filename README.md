AI systems builder with a PhD in theoretical physics. I build LLM-powered tools for code review, currently focused on smart contract security.

[LinkedIn](https://linkedin.com/in/elena-petreska) · [ResearchGate](https://researchgate.net/profile/Elena-Petreska)

## What I'm building

**Autonomous security audit agent** (Python, Claude API)
- Multi-agent Solver–Verifier loop: the Solver builds an attack scenario, and an independent Verifier confirms it or sends it back with feedback. A finding is confirmed only after two consecutive passing reviews.
- Agentic RAG over 265 public audit reports (3,110 passages), embedded locally (nomic-embed-text via Ollama) and stored in Chroma. The agent calls it as a tool.
- The same search runs as an MCP server, which I use during manual reviews from Claude Code.
- Structured JSON output for confirmed findings, prompt caching, retries with back-off, checkpoint/resume, parallel runs, and sandboxed Docker execution.
- Tested on live audit contests. Source is private because it is in active use.

## Projects

- **Autonomous security audit agent** (Python, Claude API) · [Architecture & design overview](https://github.com/EPetreska/security-agent-overview)
- [full-stack-nft-marketplace](https://github.com/EPetreska/full-stack-nft-marketplace): Next.js, TypeScript, Solidity, Hardhat, IPFS, Ethers.js

## Stack

Python, TypeScript, Claude API, RAG, embeddings, Chroma, MCP, Docker, Git, Linux, Solidity, Foundry, Hardhat, CodeQL, Semgrep

## Background

- PhD in Physics, The Graduate Center, CUNY (2014)
- Postdoctoral researcher in nuclear and particle physics (2014–2020): École Polytechnique, Santiago de Compostela University, VU Amsterdam & Nikhef
- 15+ peer-reviewed papers; talks at 20+ international conferences
- Leona Woods Distinguished Postdoctoral Lectureship Award, Brookhaven National Laboratory (2017)
