# Ruthwik Arepelly

> **Open to AIPM and product-adjacent roles** at early-stage AI startups (pre-seed to Series D, teams under 30) building LLMs, RAG, or eval tooling. [LinkedIn](https://www.linkedin.com/in/ruthwik-arepelly/) · [Email](mailto:rello4585@gmail.com)

I build evaluation-first AI systems — and I can tell you exactly why each one works, where it breaks, and what the numbers say.

7+ years building 0→1 products. Co-founded Photon (EdTech fintech, 75+ schools, $100K ARR). Now building at the intersection of LLMs, RAG, and AI evaluation.

**Start here → [Mechanic Trust case study](https://github.com/Ruthwik-Data/mechanictrust)** — the clearest example of how I design evaluation-first AI products.

---

## What Each Project Proves

| Project | Problem Solved | What It Demonstrates | Live |
|---------|----------------|----------------------|------|
| [Self-Improving Prompt Agent](https://github.com/Ruthwik-Data/self-improving-prompt-agent) | How do you improve a prompt without guessing? | Built an eval loop that ran 10 rounds — score went 0.10 → 0.80. Key insight: better prompts come from better evals, not more attempts | — |
| [finrag-eval](https://github.com/Ruthwik-Data/finrag-eval) | Financial RAG hallucinates confidently — and you can't tell | Found 2/3 hallucinations were honest refusals, 1/3 were confidently wrong. Filed a metric-level bug in DeepEval that the team is now fixing | — |
| [GitScope](https://github.com/Ruthwik-Data/gitscope) | Evaluating a GitHub repo takes hours of manual reading | Built an MCP-powered agent that gives PMs structured repo analysis in seconds — PM-first output, not raw code | — |
| [Mechanic Trust](https://github.com/Ruthwik-Data/mechanictrust) | Auto repair shops exploit trust gaps with opaque pricing | Case study: designed the trust, explainability, and pricing transparency layer for a high-friction AI product | — |
| [ReceiptIQ](https://github.com/Ruthwik-Data/receiptiq) | Accountants manually copy-paste receipt data for hours | GPT-4o Vision pipeline with confidence scoring — forces the AI to be honest about what it's uncertain about | [Demo](https://receiptiq-topaz.vercel.app/) |
| [Warmlist](https://github.com/Ruthwik-Data/warmlist) | PMs lose track of warm contacts who could open doors | GPT-4o-mini CRM that surfaces who to reach out to and why — using LLMs for PM work, not just AI products | — |
| [SugarShield](https://github.com/Ruthwik-Data/sugarshield) | AI classifiers over-warn or miss hidden sugar — you can't tell which failure mode you're in | Built eval infrastructure into the product: 0 false negatives by design, conservative bias as explicit product decision, 87% trigger match rate. Strict vs. Lenient mode comparison built-in | [Demo](https://sugarshield.vercel.app/) · [Eval](https://sugarshield.vercel.app/eval) |

---

## Case Studies

How I think through AI product decisions — not just what I built, but why, what failed, and what the system gets wrong:

**Published**
- **[Mechanic Trust](https://github.com/Ruthwik-Data/mechanictrust)** — Trust-critical design in consumer AI: explainability, pricing transparency, failure mode planning

**Case Study Pipeline** — detailed write-ups in progress, expected June 2026:
- **[finrag-eval](https://github.com/Ruthwik-Data/finrag-eval)** — Evaluation infrastructure for financial RAG: where metrics lie, where hallucinations hide
- **[Self-Improving Prompt Agent](https://github.com/Ruthwik-Data/self-improving-prompt-agent)** — Recursive eval loops: what happens when the optimizer is only as good as its evaluator

---

## Open Source Signal

## Open Source Signal

I don't just use evaluation and AI tooling. I find where they break, why, and what to ship next.

- **[confident-ai/deepeval](https://github.com/confident-ai/deepeval/issues/2594)** — Filed root-cause bug on `ContextualPrecisionMetric` over-penalizing overlapping chunks in financial RAG. Drove technical consensus on the group_by API fix — the Confident AI team is shipping it in the next release. This is evaluation obsession in practice.

- **[confident-ai/deepeval](https://github.com/confident-ai/deepeval/pull/2743)** — PR to improve `ContextualPrecisionMetric` with retrieved-context source grouping and fixed weighted precision. Came directly from hands-on financial RAG evaluation work.

- **[mem0ai/memory-benchmarks](https://github.com/mem0ai/memory-benchmarks/pull/12)** — Added failure-mode regression scenarios for memory systems — because benchmarks that don't surface failure modes aren't useful for real-world agents.

- **[weaviate/weaviate](https://github.com/weaviate/weaviate/issues/11627)** — Opened research-driven issue on hybrid search alpha auto-tuning for domain-specific corpora. Surfaced retrieval behavior patterns from financial-document work that the team is now investigating.

---

## Stack I Work In

**Evaluation:** DeepEval, Claude as evaluator, LLM-as-judge patterns, custom eval harnesses, ground-truth scoring
**RAG:** pgvector, Supabase, LangChain, OpenAI embeddings, section-aware chunking
**Agents:** MCP, Claude agents, tool-use patterns, agentic loops, prompt optimization
**Shipping:** Python, TypeScript, Next.js, Vercel, SQL, Docker
**Models:** GPT-4o Vision, Claude Opus, Claude Sonnet, DeepEval for benchmarking

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

- **Photon (Co-founder):** Built B2B SaaS payments platform for schools — 75+ schools in India, $100K ARR, 8-person team
- **Digital Connect:** AI product — built and shipped features for university admin workflows
- **BS Computer Science** · **MSc Business Analytics**, Trine University

---

## What Sets Me Apart

Most AI PMs talk about outputs. I focus on whether the system is trustworthy.

That means evaluating the evaluator (DeepEval Issue #2594), designing products around failure modes before launch (SugarShield: 0 false negatives by design), and measuring improvement through behavior change, not vanity metrics (Self-Improving Prompt Agent: 0.10 → 0.80).

I don't just use AI tools. I find where they break, why they break, and what to ship next because of it.

---

[LinkedIn](https://www.linkedin.com/in/ruthwik-arepelly/) · [Email](mailto:rello4585@gmail.com) · [Medium](https://medium.com/@rello4585)
