# Ruthwik Arepelly

I build evaluation-first AI systems — and I can tell you exactly why each one works, where it breaks, and what the numbers say.

7+ years building 0→1 products. Co-founded Photon (EdTech fintech, 75+ schools, $100K ARR). Now building at the intersection of LLMs, RAG, and AI evaluation.

---

## What Each Project Proves

| Project | Problem Solved | What It Demonstrates | Live |
|---------|----------------|----------------------|------|
| [Self-Improving Prompt Agent](https://github.com/Ruthwik-Data/self-improving-prompt-agent) | Prompt engineering is manual and unmeasurable | Eval-loop thinking; score went 0.10 → 0.80 in 10 rounds; optimization is bounded by evaluation quality | — |
| [finrag-eval](https://github.com/Ruthwik-Data/finrag-eval) | Financial RAG hallucinates confidently on SEC filings | Production RAG eval mindset; found confident hallucination (2/3 honest refusals, 1/3 wrong-but-precise answer); filed a metric-level bug in DeepEval | — |
| [GitScope](https://github.com/Ruthwik-Data/gitscope) | Evaluating a GitHub repo takes hours of manual analysis | AI decision-tool design; PM-first framing; structured output over raw data | — |
| [SugarShield](https://github.com/Ruthwik-Data/sugarshield) | Consumers can't tell if food ingredients are safe without research | Computer vision + ML pipeline that scans ingredient labels and flags harmful additives in real time | [Demo](https://sugarshield.vercel.app) |
| [mechanictrust](https://github.com/Ruthwik-Data/mechanictrust) | Auto repair shops exploit trust gaps with opaque pricing | AI product case study on trust design, explainability, and pricing transparency in high-friction services | — |

---

## Open Source Signal

**DeepEval Issue [#2594](https://github.com/confident-ai/deepeval/issues/2594)** — Filed a root-cause bug report on `ContextualPrecisionMetric` over-penalizing overlapping chunks in financial RAG. Drove technical consensus on the `group_by` API fix. The Confident AI team is shipping it in the next release.

This is what evaluation obsession looks like in practice: I wasn't just using the tool — I found where the metric itself was wrong.

---

## Stack I Work In

**Evaluation:** DeepEval, custom eval harnesses, manual ground-truth scoring, RAGAS

**RAG:** pgvector, Supabase, LangChain, section-aware chunking, Ollama, OpenAI embeddings

**Agents:** Tool-use patterns, MCP, agentic loops, prompt optimization

**Shipping:** Python, Next.js, Vercel, Docker, SQL, full-stack prototyping

---

## Background

* **Photon (Co-founder):** Built B2B SaaS payments platform for schools — 75+ schools in India, $100K ARR, 8-person team, automated payment reminder workflows
* **Digital Connect:** PM for unified digital platform serving universities and offline businesses
* **MSc Business Analytics**, Trine University

---

## I'm Open To

**AIPM or founding PM roles at Series A–B AI-native startups** — specifically teams building LLM infrastructure, RAG systems, eval tooling, or AI agents. Target companies: Patronus AI, Arize, Confident AI, HUD, or similar. I care most about whether the system actually works, not just whether it demos well.

[LinkedIn](https://www.linkedin.com/in/ruthwik-arepelly/) · [Email](mailto:rello4585@gmail.com) · [Writing on Medium](https://medium.com/@rello4585/how-i-built-sugarshield-from-a-grocery-aisle-problem-to-a-working-ai-product-c11c58fe9d54)
