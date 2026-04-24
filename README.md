# Hi, I'm Tanuj 👋

**AI Product Leader • Builder of agentic systems • Open-source maximalist**

I design and ship real-world **Agentic AI** — multi-agent systems, voice agents, and LLM-powered workflows that solve actual problems for real people. By day I lead product at [SimplAI](https://simplai.ai). By night (and most weekends) I'm here on GitHub, **rebuilding everything I care about in public** and open-sourcing it for anyone who wants to learn, fork, or build on top of it.

> If you've ever thought *"I wish someone would just show me how an agent is actually wired end-to-end"* — that's the gap I'm trying to close, one repo at a time.

---

## 🧭 Why this profile exists

I've spent years shipping AI features behind closed walls. The playbooks, evals, prompts, orchestration patterns, failure modes — all of it locked inside private repos. I kept thinking: the stuff I'd have killed to read when I was starting out is the exact stuff I'm now writing every day.

So I'm doing the obvious thing: **building it all again, in the open.**

This profile is my public workshop. Every repo here is:

- **Open source** (MIT unless otherwise noted) — fork it, ship it, sell it, I don't mind.
- **Production-shaped**, not toy code — the same patterns I'd use at work, just without the NDAs.
- **Documented for humans** — a real README, a real "why this exists," and honest notes on what's broken.
- **Built in public** — issues are roadmaps, PRs are conversations, and "I don't know yet" is an acceptable answer.

If even one person reads the code, learns something, and ships their own thing — this was worth it.

---

## 🛠️ What I'm rebuilding (and why)

I'm not trying to build *products*. I'm trying to build **reference implementations** for the patterns that kept showing up across every AI project I've worked on. Here's the current map:

### 🎯 [`career-agents`](https://github.com/tanujtp/career-agents)
An AI-powered career operating system — specialised agents for job search, resume tailoring, outreach, interview prep, and follow-ups, orchestrated together.\n
**Why:** The job market is broken on both sides. Every candidate deserves a career co-pilot that actually remembers their story. This is also a great playground for **multi-agent orchestration** with real, messy human-in-the-loop workflows.

### 📄 [`ai-resume-screening-engine`](https://github.com/tanujtp/ai-resume-screening-engine)
An open-source resume screening engine that matches resumes to JDs, extracts structured insights, scores candidates, and highlights strengths and gaps — with explanations.
**Why:** ATS systems are black boxes that throw away great candidates. If screening is going to be automated (it is), the least we can do is make the logic **inspectable, bias-auditable, and open**.

### 🏏 [`cricket-dashboard`](https://github.com/tanujtp/cricket-dashboard)
A live cricket match intelligence dashboard built with Next.js — scores, context, and AI-generated commentary.
**Why:** Pure joy project. Also a clean reference for **real-time data + LLM summarisation + responsive UI** without the overhead of building an "AI product."

### 🌾 [`farmer-voice-agent`](https://github.com/tanujtp/farmer-voice-agent)
A voice agent built for farmers — conversational, multilingual, designed for low-bandwidth and low-literacy contexts.
**Why:** Most "voice AI" demos assume a developer in San Francisco with perfect English and a MacBook. The interesting work is in the other 95% of the world. This is my attempt to take voice agents where they're actually needed.

### 🔎 [`company-finder`](https://github.com/tanujtp/company-finder)
A smart company discovery tool — describe what you're looking for, get a ranked list with context.
**Why:** Lead-gen is one of the most obvious applied-AI use cases, and most existing tools are either gated behind $10k/yr contracts or terrible. The patterns here (entity resolution, enrichment, ranking, explainability) show up everywhere.

### 💸 [`finance-dashboard`](https://github.com/tanujtp/finance-dashboard)
A personal finance dashboard with AI-assisted categorisation and insights.
**Why:** Everyone's personal finance app is either spying on them, upselling them, or both. I wanted one I could own end-to-end.

### 📚 [`docs`](https://github.com/tanujtp/docs)
The living handbook — prompts, eval patterns, agent architectures, lessons learned, and post-mortems from all the repos above.
**Why:** Code without context is just noise. This is where the **"how I think about this"** lives.

More coming. The general rule: if I'm about to build it at work, I ask whether a **generic, de-identified version** could live here first. Most of the time, the answer is yes.

---

## 🌱 What I believe

A few things I've come to believe strongly, that shape everything in these repos:

1. **Agents are a product problem, not just a model problem.** The LLM is ~20% of the work. Orchestration, eval, memory, tool design, failure recovery, and UX carry the rest.
2. **"Open source AI" means open source *all* of it.** Prompts, evals, traces, failure cases — not just a README pointing at a closed model. I'll publish the ugly parts.
3. **Community > solo genius.** Everything I know, I learned from someone else's repo, blog post, or weekend hack. The only debt I can pay is forward.
4. **Ship, then polish.** I'd rather put up a working-but-rough repo today than a perfect one in six months. The feedback you get from "it's live" is worth ten imagined design reviews.
5. **Indian builders deserve a front-row seat.** A lot of agentic-AI discourse is US-centric. The problems worth solving — and the builders ready to solve them — are everywhere.

---

## 🤝 How you can get involved

I genuinely want this to be built **with** the community, not just *for* it. If any of this resonates, here's how to jump in — pick whichever matches your energy today:

- **⭐ Star the repos you find useful.** It's a tiny thing but it tells me (and others) what's worth investing more time in.
- **🐛 Open issues.** Bug reports, feature ideas, "this README confused me," "here's a better prompt" — all welcome. No issue is too small.
- **🔀 Send PRs.** First-time contributors especially welcome. I'll review with care, not with a gatekeeping stick. If you're not sure where to start, look for issues tagged `good first issue` or `help wanted`.
- **💡 Propose a new repo.** If there's an agentic pattern you wish had a clean open-source reference, open a discussion. I'm always looking for the next thing to rebuild.
- **📣 Share what you build on top.** Fork anything here, ship something, and tag me. Seeing downstream builds is the single best feedback loop in open source.
- **✍️ Write with me.** If you want to co-author a deep-dive on something we've both worked on — DM me. I'd rather publish a great joint post than a mediocre solo one.
- **🫂 Just say hi.** Starting out? Stuck on something? Thinking about a career pivot into AI? My inbox is open, and I remember how useful "a 20-minute chat with someone further along" was for me.

**Code of conduct:** be kind, be curious, assume good faith. That's it.

---

## 🧰 The stack I tend to reach for

Not dogma — just what's been working for me lately:

- **Languages:** Python for agents and backends, TypeScript for anything user-facing, MDX for docs.
- **LLM orchestration:** mix of custom orchestration and frameworks like LangGraph / CrewAI / direct tool-use — depends on the shape of the problem.
- **Frontend:** Next.js + Tailwind, shadcn/ui when I want to move fast.
- **Infra:** Vercel for web, serverless functions where sensible, Postgres + pgvector when I need memory/retrieval.
- **Evals:** always. Usually hand-rolled at first, then graduated to something structured once patterns emerge.
- **Voice:** open-source ASR/TTS where possible, hosted when latency matters.

I change my mind about tooling often. The repo READMEs have the current truth.

---

## 📬 Where to find me

- 🌐 Portfolio → [tanujparmar.me](https://tanujparmar.me/)
- 💼 LinkedIn → [linkedin.com/in/tanujparmar](https://www.linkedin.com/in/tanujparmar/)
- 💻 GitHub → you're already here
- ✉️ Email → tanuj.parmar23@gmail.com

If you're building something in agentic AI, especially something slightly off the beaten path — I want to hear about it.

---

## 🙏 A small ask

If you fork anything here and it helps you ship something, **pay it forward**: open-source one thing you'd normally keep private. The commons only grows if we all put something back.

That's the whole thing. See you in the PRs. 🫡

<sub>Last updated: April 2026 • Built with care from India, for the world.</sub>
