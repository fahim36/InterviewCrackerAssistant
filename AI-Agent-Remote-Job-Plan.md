# Plan for an International Remote AI Agent Developer Job from Bangladesh

*Researched: 25 Sep 2026 · Your profile: have built LLM apps, weak on fundamentals, ~15 hrs/week, freelance + full-time in parallel*

---

## 1. Market Research Summary

### Demand is real and growing fast
| Signal | Data |
|---|---|
| Agentic AI skills in US job posts | ~280% growth, ~90k postings (Stanford AI Index 2026, second-hand) |
| US AI-engineering postings | ~1,550 new/week; **32% fully remote** |
| Forward Deployed Engineer posts | +1,000% YoY (Jan–Aug 2026, Lightcast via Fortune) |
| UK: LangGraph / MCP permanent ads | 12 → 135 / 7 → 103 year-over-year |
| Upwork: AI integration / AI chatbot demand | +178% / +71% YoY |

**Titles to search:** AI Engineer · Agentic AI Engineer · AI Agent Engineer · Applied AI Engineer · LLM Engineer · AI Automation Engineer · Forward Deployed Engineer · AI Solutions Engineer.

### Why it's hard from Bangladesh
- Most "remote" posts are **US-only or single-country**. General boards (WWR, RemoteOK, LinkedIn) are mostly closed to you.
- True junior roles are scarce. About two-thirds of US AI postings are mid or senior.
- A "LangChain + Pinecone + ChatGPT wrapper" resume is now **baseline, even a yellow flag**. Evals, observability and production numbers are what get you through screening.

**What works:** contractor platforms, vetted talent networks, BD-filtered boards, and APAC, Australian and European companies where the time zones overlap.

### Most-requested skills, ranked from 2025–26 postings
1. **Python**: 62–73% of postings
2. **Cloud**: AWS dominant, then Azure and GCP; Amazon Bedrock is common
3. **LLM APIs and tool calling**: OpenAI and Anthropic Claude
4. **RAG, vector DBs and embeddings**: pgvector, Qdrant, Pinecone; hybrid search and reranking
5. **LangGraph**: the leading orchestration framework (LangChain appears alongside it in 93% of cases)
6. **MCP (Model Context Protocol)**: fastest-rising
7. **Evals and observability**: LangSmith, Langfuse, Braintrust, Phoenix. *This is the #1 screening topic.*
8. **CI/CD, Docker, Kubernetes**
9. **TypeScript**: ~21% of postings; >95% of FDE roles ask for Python and/or TypeScript
10. **FastAPI and serverless deployment**
11. CrewAI, AutoGen, LlamaIndex: secondary
12. **n8n, Make, Zapier**: mainly freelance and "AI Automation Engineer" roles

### Realistic pay for a Bangladesh-based developer (USD)
| Channel | Range |
|---|---|
| New Upwork/Fiverr AI-automation freelancer | $15–35/hr at first → $40–80/hr with reviews |
| AI coding-trainer contracts (Turing, Mercor, micro1) | ~$20–50/hr |
| Remote full-time for South Asia (mid-level) | ~$25k–75k/yr ($2–6.5k/month) |
| Vetted networks (Lemon.io, Arc, Turing dev) | $27–60/hr mid; $60–95/hr for agent/RAG specialists |
| Local benchmark (Dhaka, mid AI engineer) | BDT 120–180k/month |

---

## 2. Channels Ranked by Speed to First Dollar

| # | Channel | BD OK? | Speed | Notes |
|---|---|---|---|---|
| 1 | **Turing** (LLM trainer / coding eval) | ✅ Bangladesh named in its contract ads | 2–4 weeks | Needs 20+ hrs/week and 4h overlap with US Pacific. Take it only if it fits your time. |
| 2 | **Mercor** | Likely (Wise payout) | 1–4 weeks | AI interview; pays weekly |
| 3 | **micro1** | Global | 1–4 weeks | 20–30 min AI interview ("Zara"); engineering roles $50–150/hr |
| 4 | **Upwork** | ✅ | 2–8 weeks | Pays out via Direct-to-Local-Bank in BDT ($0.99) or Payoneer |
| 5 | **Fiverr** | ✅ BD is a top-5 country | 2–8 weeks | AI-automation gigs +136% |
| 6 | **Arc.dev** | ✅ has a BD job page | 3–6 weeks | Example: "AI Automation Engineer (n8n, Claude Code)" at $25–40k/yr |
| 7 | **Crossover** | ✅ BD AI-engineer page | 4–8 weeks | Hard tests plus time-tracking; pays well |
| 8 | **Himalayas / Jobgether / Remote Rocketship** (filter: Bangladesh) | ✅ | Weeks to months | CoverGo, Automattic, AssemblyAI hire in BD |
| 9 | **Toptal** | ✅ | 1–3 months | Top ~3% pass. Apply around month 4–5. |

**Skip:** DataAnnotation and Alignerr (PayPal-only or US-only), Contra (Stripe payouts), and anything that pays only via PayPal.
**Outlier:** possible via Airtm, but unreliable.

### Payment and legal admin (do this in Week 1)
- **Payoneer:** open an account; it's the default for Upwork, Fiverr and Deel.
- **PayPal:** still not live in BD. A Bangladesh Bank framework (Jul 2026) allows it in future.
- **Wise:** can't receive USD, but platforms can pay you in BDT through it.
- **Tax:** IT/software/AI freelance income is **tax-exempt until 30 June 2027** if it comes in through a bank. A salary from a foreign employer is taxable. Confirm with a tax adviser.
- **Bangladesh Bank circular (22 Jul 2026):** you can keep 50% in an FC/ERQ account, receive up to $20k without declaration, and banks now issue freelancer cards.
- **Freelancer ID:** register at **freelancers.gov.bd** once you've earned $50. It's free, lasts 3 years, and helps with banking.
- **Crypto (USDT etc.):** don't. It's illegal for payments in BD and gets bKash/Nagad accounts frozen.

---

## 3. Weekly Time Budget (15 hrs)

| Block | Hours | What |
|---|---|---|
| **Fundamentals** | 5 | Syllabus track A (interview foundations) |
| **Build** | 7 | Syllabus track B (agent engineering) plus portfolio projects |
| **Hunt** | 3 | Proposals, applications, one LinkedIn/X build-log post a week |

Suggested schedule: 1h on each weekday (fundamentals) plus 5h on each weekend day (build and hunt).

---

## 4. Syllabus (16 weeks)

Two tracks run in parallel.
- **Track A: fundamentals.** This is what interviews test.
- **Track B: agent engineering.** This is what the portfolio and freelance work need.

### Phase 0: Launch (Week 1). Start earning in parallel from day one
- [ ] Open Payoneer; verify NID/passport on Upwork and Fiverr
- [ ] Apply: **Turing, Mercor, micro1** (practice for their AI interviews: explain code out loud and talk through trade-offs)
- [ ] Upwork profile headline: *"AI Agent & Automation Developer: LLM agents, RAG, n8n, Python"*
- [ ] Fiverr: 2 gigs ("I will build an AI agent / RAG chatbot for your docs", "I will automate your workflow with n8n + AI")
- [ ] Pick one existing LLM project of yours, clean up its README, and add a 2-min Loom demo. This is your case study #0.

---

### Phase 1: Foundations (Weeks 1–4)

**Track A: CS and Python fundamentals**
| Week | Topics | Done when you can… |
|---|---|---|
| 1 | **Python internals:** data model, mutability, `*args/**kwargs`, closures, decorators, generators, context managers, iterators | explain *why*, not just *how*, for each one |
| 2 | **Python for production:** type hints, `pydantic` v2, `asyncio` (event loop, `gather`, semaphores, cancellation), exceptions, logging, `pytest` (fixtures, mocking) | write an async client that calls an API 50× concurrently with rate-limiting and retries |
| 3 | **DSA core:** arrays/hashing, two pointers, sliding window, stacks, binary search (NeetCode 150, the first ~40) | solve easy problems in 15 min and mediums in 30 min |
| 4 | **Backend fundamentals:** HTTP, REST, status codes, auth (API keys, JWT, OAuth basics), **SQL** (joins, indexes, transactions), Postgres, Git (rebase, PRs) | build a CRUD FastAPI + Postgres service with tests |

**Track B: LLM fundamentals** (interviewers probe these)
- How LLMs work at a conceptual level:
  - tokens and tokenization
  - embeddings
  - attention and transformer blocks
  - context windows
  - temperature, top-p
  - why hallucinations happen
- API mechanics: messages and roles, **tool/function calling** (the JSON schema, the loop), **structured outputs**, streaming, **prompt caching**, token and cost math
- **Build: an agent loop from scratch with no framework.** Write a `while` loop: LLM → tool call → execute → append the result → repeat, with max steps, error handling and a cost tracker. *This is the most common "do you really understand agents?" interview question.*

---

### Phase 2: Agentic Core (Weeks 5–8)

**Track A**
- Weeks 5–6: **DSA continued:** linked lists, trees, BFS/DFS, heaps, graphs (NeetCode 150 #40–90)
- Weeks 7–8: **Docker** (multi-stage builds, compose), **Linux/bash basics**, **CI with GitHub Actions** (lint, test, build on every PR)

**Track B**
| Week | Topics | Output |
|---|---|---|
| 5 | **Agent patterns:** ReAct, plan-and-execute, reflection, routing, orchestrator-workers, evaluator-optimizer (read *Anthropic: Building Effective Agents*). When NOT to use an agent (workflows vs agents). | a notes doc on the patterns with trade-offs |
| 6 | **LangGraph:** state, nodes and edges, conditional routing, **checkpointing/persistence**, **human-in-the-loop** interrupts, supervisor multi-agent, memory (short- vs long-term) | multi-step agent with approval step |
| 7 | **RAG done properly:** chunking strategies, embeddings, **pgvector**, hybrid search (BM25 + vector), **reranking**, query rewriting, citations. **Retrieval metrics:** recall@k, MRR, faithfulness | RAG with a measured retrieval score |
| 8 | **MCP:** protocol concepts (tools, resources, prompts, transports: stdio vs streamable HTTP), build an MCP server in Python, connect it to Claude/Cursor, auth basics | **publish an MCP server** to GitHub and the MCP registry |

---

### Phase 3: Production-Grade Agents (Weeks 9–12). This is what separates you from "wrapper" developers

**Track A**
- Weeks 9–10: **System design basics:** caching, queues (Redis, Celery/RQ), rate limiting, horizontal scaling, idempotency, retries and backoff, SQL vs NoSQL
- Weeks 11–12: **TypeScript basics** (types, async, Node) plus the **Vercel AI SDK** or the TS OpenAI/Anthropic SDK. This opens up the >95% of FDE roles that ask for Python and/or TypeScript.

**Track B**
| Week | Topics | Output |
|---|---|---|
| 9 | **Evals** (the #1 screening topic): golden datasets, code-based checks, **LLM-as-judge** (and how to validate the judge), pairwise comparisons, regression evals in CI, error analysis on real traces (read Hamel Husain's evals posts) | eval suite that runs in GitHub Actions |
| 10 | **Observability:** **Langfuse** or LangSmith tracing, cost per run, latency p50/p95, tool-failure rates, user feedback loops | dashboard screenshot for your README |
| 11 | **Safety and reliability:** prompt injection (direct and indirect), **OWASP LLM Top 10** (especially "excessive agency"), guardrails, output validation, sandboxing tool execution, least-privilege tools, fallbacks and model routing | threat-model section in each README |
| 12 | **Deployment:** FastAPI + streaming (SSE), Docker, deploy to AWS (Lambda/ECS or Bedrock) *or* Modal/Railway/Fly; secrets, env config; **cost optimization** (caching, smaller models for sub-tasks, prompt compression) | live URL for the flagship project |

---

### Phase 4: Interview Mastery and Scaling (Weeks 13–16)
- **LLM system design practice.** Design each of these out loud, in 45 minutes:
  - a customer-support agent for 10k users/day
  - a document-QA system over 1M PDFs
  - a coding agent
  - a multi-tenant RAG system with access control
- **Take-home practice.** Some companies give a 90-minute test: a working agent with planted bugs to find and fix. Practise debugging other people's agent code.
- **Behavioral (STAR).** Prepare 6 stories: conflict, failure, ambiguity, ownership, a client you handled, and a time you cut cost or latency.
- **DSA maintenance:** 3 problems a week.
- **Mock interviews:** Pramp or peers.
- **Framework breadth:** skim the **OpenAI Agents SDK** and the **Claude Agent SDK**, so you can say "I chose LangGraph over X because…".
- **n8n** (freelance): webhooks, AI Agent node, error workflows, self-hosting on a VPS. Many Upwork jobs are "fix/build my n8n + AI workflow".

---

## 5. Portfolio (build during Phases 2–3)

Every project README must include: an architecture diagram, **eval results**, **cost per run**, **p95 latency**, known failure modes, a threat model, and a 2-min demo video.

| # | Project | Proves | Target buyer |
|---|---|---|---|
| 1 | **Support/Ops agent**: RAG over docs + tools (ticket lookup, refund API mock) + human approval + Langfuse + eval suite in CI. Deployed. | Production agent engineering | Full-time AI Engineer roles |
| 2 | **Multi-agent workflow** (e.g., research → draft → review agent, or invoice/contract extraction → validation → CRM push), built with LangGraph checkpointing | Orchestration, reliability | Applied AI / FDE roles |
| 3 | **Published MCP server** for a useful API (e.g., Bangladeshi e-commerce, Google Sheets, a popular SaaS) | Newest in-demand skill; public proof | Everyone; good for LinkedIn posts |
| 4 | **n8n + LLM automation case study** (lead qualification, email triage, WhatsApp bot) with before/after numbers | Business value | Upwork/Fiverr clients |
| + | **2–3 merged open-source PRs** (LangGraph, Langfuse, MCP SDKs, agent frameworks: docs fixes and small bugs count) | Code quality checked by other engineers | Recruiters value these highly |

Recruiters treat these as **red flags**:
- five frameworks with no depth in any
- notebook-only projects
- no observability tool named
- "implemented RAG" with no retrieval metric
- no mention of inference cost

---

## 6. Job-Hunt Operating System (3 hrs/week)

| When | Action |
|---|---|
| Weeks 1–2 | Turing, Mercor, micro1 applications; Upwork and Fiverr profiles live |
| Every week | **8–12 Upwork proposals.** Target "fix my broken automation/agent" posts (less competition). Open with a 2-line diagnosis of their problem plus a link to a matching case study. |
| Every week | **5 targeted full-time applications** on Himalayas, Jobgether and Remote Rocketship (BD filter), plus Arc.dev. Favour APAC, Australian, European and remote-first startups. |
| Every week | 1 LinkedIn build-log post (what you built, a metric, a lesson). Connect with founders and AI-engineering leads. |
| Week 6+ | Apply to **Arc.dev**, **Crossover** |
| Week 12+ | Apply to **Toptal**, Lemon.io; senior-leaning full-time roles; FDE roles if you enjoy client work |

**Application tips from Bangladesh:**
- State your working-hours overlap up front, e.g. "Available 2pm–11pm BST = full EU overlap / US East mornings".
- Offer to be paid via **Deel/Remote.com** (removes the employer's compliance worry).
- Keep a backup internet connection and a good mic; say so in interviews.
- Never use mouse-jigglers on time-tracked contracts (Crossover and similar).

---

## 7. Realistic Timeline
| Milestone | Target |
|---|---|
| First USD income (trainer contract or first small gig) | **Weeks 2–6** |
| 3–5 Upwork reviews, $30–40/hr | Months 2–3 |
| Portfolio complete (projects 1–4) | Month 3 |
| Vetted network / first remote contract role | Months 3–5 |
| Full-time international remote offer | **Months 4–8** (varies with market and interviews) |

---

## 8. Core Resources (mostly free)

**Agents and LLM engineering**
- Anthropic: *Building Effective Agents* (blog) and Anthropic's courses on GitHub (prompt engineering, tool use)
- LangChain Academy: *Introduction to LangGraph* (free)
- Hugging Face *AI Agents Course* (free)
- DeepLearning.AI short courses: MCP, LangGraph, evaluating agents
- modelcontextprotocol.io docs and the Python SDK
- Hamel Husain's evals blog posts; Langfuse docs
- Book: Chip Huyen, *AI Engineering* (O'Reilly, 2025)
- OWASP Top 10 for LLM Applications

**Fundamentals**
- Karpathy: *Intro to LLMs* and *Let's build GPT* (YouTube)
- 3Blue1Brown: transformer and attention videos
- *Fluent Python* (Ramalho): Python internals
- NeetCode 150 (DSA)
- FastAPI official tutorial; Docker "Get Started"; SQLBolt / PostgreSQL tutorial
- *System Design Primer* (GitHub)

---

## Sources (selected)
- Axial Search, AI engineering jobs: https://axialsearch.com/insights/ai-engineering-jobs
- Fortune, FDE growth (Sep 2026): https://fortune.com/2026/09/03/forward-deployed-engineers-fast-growing-six-figure-silicon-valley-job-integrate-ai-with-customers-tech-careers-palantir/
- ITJobsWatch, LangGraph / MCP: https://www.itjobswatch.co.uk/jobs/uk/langgraph.do
- Upwork in-demand skills 2026: https://www.upwork.com/press/releases/upworks-in-demand-skills-2026-demand-for-top-ai-skills-more-than-doubles-as-ai-is-embedded-into-everyday-work
- HeroHunt, hiring AI agent engineers: https://www.herohunt.ai/blog/how-to-recruit-ai-agent-engineers-in-2026/
- DigitalApplied, AI dev hiring skills: https://www.digitalapplied.com/blog/ai-developer-hiring-skills-that-matter-2026
- Arc.dev Bangladesh: https://arc.dev/en-bd/remote-jobs
- Crossover BD: https://www.crossover.com/jobs/ai-engineer/bd
- Himalayas BD companies: https://himalayas.app/companies/countries/bangladesh
- Mercor payments: https://talent.docs.mercor.com/how-to/payments
- Upwork local bank payouts: https://support.upwork.com/hc/en-us/articles/211060578
- Dhaka Tribune, BB freelancer circular: https://www.dhakatribune.com/business/banks/415725/bb-eases-foreign-transactions-policy-for
- Daily Star, remote income tax: https://www.thedailystar.net/business/news/foreign-remittance-income-freelancing-or-remote-work-tax-free-or-taxable-4084906
- TBS, PayPal status: https://www.tbsnews.net/economy/banking/paypal-bangladesh-how-close-long-awaited-entry-1522191
- Freelancer ID portal: https://www.freelancers.gov.bd/

*Caveats: some pay and rate figures come from staffing or outsourcing vendors and are indicative. Country eligibility on the AI-trainer platforms changes often, so verify at sign-up. Confirm the tax points with a tax adviser.*
