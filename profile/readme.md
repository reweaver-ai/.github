# ReWeaver AI

![STOP CODING IN THE DARK - an image of a box with a light inside it representing the "AI Black Box" of assisted coding](https://media.licdn.com/dms/image/v2/D563DAQFpHe_dXGRWBA/image-scale_191_1128/B56Z03HTV4JwAc-/0/1774746154675/reweaver_ai_cover?e=1782838800&v=beta&t=TozNxEsevRwvTej7IY-Uf4ZSOc8lSDjx1gugTyl0lGw)

**Governance for AI-generated code.** AI writes a fast-growing share of what ships to production — and it drifts from the standards teams are trying to hold: their design system, their conventions, their reliability and security practices. ReWeaver AI is a deterministic governance engine that catches that drift, surfaces it, and keeps a human in control of every change.

The point isn't to slow AI down. It's to make AI velocity convert into code you can actually ship.

---

## What we believe

AI coding tools are sold on the speed of the first draft. The cost shows up later — in the rework, the silent defects, and the design system that quietly stopped matching the codebase three sprints ago. The answer isn't better generation. It's verification.

> **Skills tell the model what to do. Governance verifies that it did.**

So we draw a hard line between the two:

- **Detection is deterministic.** Rule- and AST-based, with no model in the loop — the same code produces the same findings every time, each citing a specific WCAG criterion, CWE, or framework pattern. No "an LLM thought this looked wrong."
- **Fixes stay human-controlled.** Where a deterministic rewrite exists, it's applied; where judgment is needed, a local model drafts a fix you can re-roll until it fits. Either way it reaches your codebase as a pull request you review and merge. Nothing is changed or merged on its own.
- **Everything is on the record.** Every decision lives in your git history, where it's auditable.

We check production-readiness across nine dimensions — design consistency, user experience, accessibility, maintainability, reliability, security, architecture, and testability — and our standout is **bidirectional design-code synchronization**: we treat your codebase and your Figma design system as one connected pair and surface every divergence, in either direction.

---

## Where to start

**Product & overview** → **[reweaver.ai](https://www.reweaver.ai)**

**Try it live** → [Playground](https://www.reweaver.ai/playground) — paste in AI-generated code and watch the deterministic engine surface drift in real time, no install required. The fastest way to see governance in action before you join the beta.

**Read the thesis** → [The design-code roundtrip that isn't](https://www.reweaver.ai/post/the-design-code-roundtrip-that-isn-t)

**Get the toolkit + join the beta** → [AI Drift Prevention Toolkit](https://info.reweaver.ai/AI-coding-survival-kit)


---

## What's here on GitHub

We're in early alpha, and the engine itself isn't public yet. What *is* public is the open, free, prompt-layer starting point — the part you can use today, with any AI coding assistant, before you ever touch the product.

### [survival-kit](https://github.com/reweaver-ai/survival-kit) &nbsp;·&nbsp; `MIT`

**The AI Coding Survival Kit** — a portable, tool-agnostic set of system prompts, rules files, and skills that push AI assistants (Claude, Cursor, Copilot, and others) toward production-grade code instead of code that merely compiles. Built from systematic analysis of real vibe-coded repositories, where the same failure patterns showed up again and again: silent fallbacks masking errors, untyped parameters, god-object files, cascading error-masking chains. Every rule addresses a pattern observed in the wild — none are theoretical.

Drop-in configs for Claude Code (`CLAUDE.md`), Cursor (`.cursorrules`), Copilot (`.github/copilot-instructions.md`), and any system prompt.

Prefer a guided version? The same battle-tested files come packaged with a 10-page guide as the **[AI Drift Prevention Toolkit](https://info.reweaver.ai/AI-coding-survival-kit)** — grab the repo directly, or get the toolkit and join the beta list.

> The survival kit shapes what your AI assistant *writes*. ReWeaver AI is what *verifies* that it actually held — deterministically, on every change. Use the kit today; the product is where governance gets enforced.

---

## Who we are

A small team building the governance-and-assurance layer for AI-assisted software — the part that comes after generation and makes generation sustainable. We're early, and honest about it: alpha product, growing cohort of users, public beta ahead.

If the problem of AI code that *looks* done but isn't resonates with you — as a user, a contributor, or someone who just wants to compare notes — we'd like to hear from you.

**[Website](https://www.reweaver.ai)** &nbsp;·&nbsp; **[About](https://www.reweaver.ai/about)** &nbsp;·&nbsp; **[Discord](https://discord.gg/hdY8c3Hn)** &nbsp;·&nbsp; **[LinkedIn](https://www.linkedin.com/company/gojongo-labs)** &nbsp;·&nbsp; **[X](https://www.x.com/reweaver_ai)**
