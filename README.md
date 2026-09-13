# AI Adoption Readiness Check

**A 12-question diagnostic that shows where your organisation is actually ready to adopt AI — and what to fix first.**

👉 **[Take the assessment →](https://hi-kay.github.io/ai-readiness-check/)**

---

## Why this exists

I spent three years helping cement and concrete producers adopt AI. The business case was rarely the hard part. Once you have shown a plant director what better quality control is worth, the maths is not what stops them.

What stops them is everything around the maths. Whether management uses the tool themselves. Whether anyone has told the lab team what to actually do with it. Whether IT can provision access this month. Whether the works council has seen it. Whether people quietly believe the thing is there to replace them.

An ROI calculator answers *"what is the prize?"* — I built [one of those too](https://hi-kay.github.io/ai-value-calculator/). This tool answers the question that decides whether you ever collect it: **"can this organisation actually get there, and what is in the way?"**

---

## What it measures

Four pillars, three questions each. Every one of them is somewhere I have watched a rollout succeed or stall:

| Pillar | The question underneath |
|---|---|
| **Strategy & Leadership** | Do leaders use it themselves, or only announce it? |
| **Governance, Trust & Safety** | Is the path to production clear — data rules, privacy, works council? |
| **Workflows & System Integration** | Is AI reaching the systems where the work lives, or stuck in ad-hoc chat? |
| **Enablement & Champions Network** | Was there onboarding and peer support, or just a licence? |

Each pillar is scored red, amber or green. You get an overall readiness score, a maturity stage (Exploring → Building → Scaling → Embedded), a pillar-by-pillar breakdown, and **a concrete first action for every weak answer, worst first**. The action is tied to the specific question, not the pillar average — which is the part that actually matters.

---

## Four design decisions worth explaining

**A pillar cannot be "Strong" while one of its answers is weak.** Two strong answers and one "Never" average 67%, which would pass a plain threshold and hide the gap. Any answer in the bottom two options caps its pillar at "Developing" and produces its own action card.


**It is built to produce uncomfortable answers.** The four-point scale has no neutral middle, so "we sort of have that" is not an available answer. A flattering score is worthless: the value of a diagnostic is that it finds something.

**Governance includes the works council.** Most AI readiness assessments are written in the US and quietly assume US conditions. In German enterprises the Betriebsrat is a genuine gate on rolling out a tool that changes how employees work — and involving them late is, in my experience, the single most common reason a rollout slips by months. An early Betriebsvereinbarung is far faster than one negotiated after a stalled rollout. Any readiness model for DACH that omits this is measuring the wrong country.

**The recommendations are written for the person filling it in.** Not "here is what a vendor should do for you" — the actions are yours to take. Where an account team can help, it says so, once.

---

## Using it in practice

It works as a self-assessment, but it is more useful as a **conversation structure**. Run it live with the project team and the disagreements are the real output: when the sponsor scores leadership 3 and the team scores it 1, you have learned more than the score will ever tell you.

Everything runs in the browser. Nothing is uploaded, nothing is stored, no analytics — which is also what makes it safe to open in someone else's meeting room. **Print / Save PDF** produces a clean one-page result — score, pillar breakdown, action plan — to leave behind, with the questions themselves omitted.

---

## Tech

A single self-contained HTML file. Vanilla JavaScript, no framework, no build step, no dependencies, no network calls at all. Questions, hints and recommendations live in one `DIMENSIONS` array at the top of the script — fork it and rewrite them for your own context.

Accessible by keyboard and screen reader; the dark UI has a dedicated print stylesheet so exported PDFs are readable on paper.

Built with [Claude Code](https://claude.com/claude-code).

---

## About the author

**Heike Romanowski** — Dipl.-Ing., most recently Head of Value Engineering at [alcemy GmbH](https://alcemy.tech)

Customer Success Manager → DataOps lead → Head of Value Engineering, all in enterprise AI for heavy industry. Before that: bioprocess engineer, researcher, startup CTO.

- 🔗 [LinkedIn](https://linkedin.com/in/heike-romanowski)
- 🧮 [AI Value Calculator](https://hi-kay.github.io/ai-value-calculator/) — the ROI side of the same problem

---

*Fork it, adapt it, use it with your own teams. If you find it useful, a LinkedIn connection is always welcome.*
