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
| [SugarShield](https://github.com/Ruthwik-Data/sugarshield) | Consumers can't tell if food ingredients are safe without research | Computer vision + ML pipeline that scans ingredient labels and flags harmful additives in real time | [Demo](https://sugarshield.vercel.app/) |
| [mechanictrust](https://github.com/Ruthwik-Data/mechanictrust) | Auto repair shops exploit trust gaps with opaque pricing | AI product case study on trust design, explainability, and pricing transparency in high-friction services | — |
| [ReceiptIQ](https://github.com/Ruthwik-Data/receiptiq) | Manual receipt parsing wastes hours for accountants and freelancers | GPT-4o Vision extraction pipeline with structured JSON/CSV export; confidence scoring for trust-critical output | [Demo](https://receiptiq.vercel.app/) |
| [Warmlist](https://github.com/Ruthwik-Data/warmlist) | PMs lose track of warm contacts who could open doors | GPT-4o-mini powered CRM that surfaces relationship context and surfaces who to reach out to and why | — |

---

## Case Studies

How I think through AI product decisions — not just what I built, but why and what the system gets wrong:

- **[Mechanic Trust](https://github.com/Ruthwik-Data/mechanictrust)** — Trust-critical design in consumer AI: explainability, pricing transparency, failure mode planning
- **[finrag-eval](https://github.com/Ruthwik-Data/finrag-eval)** — Evaluation infrastructure for financial RAG: where metrics lie, where hallucinations hide
- **[Self-Improving Prompt Agent](https://github.com/Ruthwik-Data/self-improving-prompt-agent)** — Recursive eval loops: what happens when the optimizer is only as good as its evaluator

---

## Open Source Signal

**DeepEval Issue [#2594](https://github.com/confident-ai/deepeval/issues/2594)** — Filed a root-cause bug report on `ContextualPrecisionMetric` over-penalizing overlapping chunks in financial RAG. Drove technical consensus on the `group_by` API fix. The Confident AI team is shipping it in the next release.

This is what evaluation obsession looks like in practice: I wasn't just using the tool — I found where the metric itself was wrong.

---

## Stack I Work In

**Evaluation:** DeepEval, LLM-as-judge, custom eval harnesses, ground-truth scoring

**RAG:** pgvector, Supabase, LangChain, OpenAI embeddings, section-aware chunking

**Agents:** MCP, tool-use patterns, agentic loops, prompt optimization

**Shipping:** Python, TypeScript, Next.js, Vercel, SQL, Docker

---

## Writing

I write about product thinking, AI systems, and what I learn from building:

- **[Product Learning: How Gifting Became a Growth Engine, Not a Feature](https://medium.com/@rello4585/product-learning-how-gifting-became-a-growth-engine-not-a-feature-68d1d7e7dad0)** — Feature → growth lever
- **[How I Turn User Complaints Into Feature Ideas (Simple 7-Step Method)](https://medium.com/@rello4585/how-i-turn-user-complaints-into-feature-ideas-simple-7-step-method-9d99c7ed843f)** — Product thinking framework
- **[From Venue to Platform: The Bernabéu as a Product](https://medium.com/@rello4585/from-venue-to-platform-the-bernab%C3%A9u-as-a-product-4f1ae98626a9)** — How physical spaces evolve into platforms
- **[How I Built SugarShield: From a Grocery Aisle Problem to a Working AI Product](https://medium.com/@rello4585/how-i-built-sugarshield-from-a-grocery-aisle-problem-to-a-working-ai-product-c11c58fe9d54)** — Full build case study
- **[Tap & Pray Is Not a Payment Strategy](https://medium.com/@rello4585/tap-pray-is-not-a-payment-strategy-2af7914161d0)** — Fintech product lessons
- **[Product Experiment: IntentTabs — Adding Friction to Fight Impulse](https://medium.com/@rello4585/product-experiment-intenttabs-adding-friction-to-fight-impulse-3f1e6553f7f8)** — Behavioral design in product

[View all on Medium →](https://medium.com/@rello4585)

---

## Background

- **Photon (Co-founder):** Built B2B SaaS payments platform for schools — 75+ schools in India, $100K ARR, 8-person team, automated payment reminder workflows
- **Digital Connect:** PM for unified digital platform serving universities and offline businesses
- **MSc Business Analytics**, Trine University

---

## I'm Open To

Product and product-adjacent roles (strategy, operations, GTM) at **pre-seed to Series D AI startups (teams under 30)** building reliable AI systems — evaluation infrastructure, RAG, agents.

[LinkedIn](https://www.linkedin.com/in/ruthwik-arepelly/) · [Email](mailto:rello4585@gmail.com) · [Medium](https://medium.com/@rello4585)
