# Claude 101 – Short Notes
---
> [!WARNING]
> This is a comprehensive guide for using Claude AI, created based on the Claude 101 course and intended for revision and learning purposes only. Completion of this guide does **not** guarantee certification, course completion, or any official credential from Anthropic or the course provider.

---

## What is Claude?

- AI assistant by Anthropic, built using **Constitutional AI**.
- A thinking partner, not just a chatbot.
- Core principles: **Helpful · Honest · Harmless**

**Main uses:** Writing, Research, Coding, Problem-solving, Learning

**Key features:**
- Follows tone/style instructions
- Large context window
- Extended Thinking mode (deeper reasoning)
- Learning Mode (guides thinking instead of giving direct answers)

---

## Claude Products at a Glance

| Product | Best For |
|---|---|
| **Claude.ai** | General use – chat, writing, research, analysis |
| **Claude Code** | Software development – write, debug, run, commit |
| **Claude Cowork** | Long multi-step tasks – research, reports, automation |
| **Claude in Slack** | Team collaboration – summaries, drafts, meeting notes |
| **Claude for Excel** | Spreadsheets – formulas, charts, models |
| **Claude for PowerPoint** | Presentations – create, rewrite, format |
| **Claude for Chrome** | Browser – summarize pages, fill forms, navigate |

> **Memory trick:** Think → Build → Execute → Collaborate → Analyze → Present → Browse

---

## Prompting Basics

**Golden Rule: Talk to Claude like a coworker — natural, clear, concise.**

### Prompt Formula
```
Context + Task + Rules
```
- **Context** – Who you are, what you're trying to achieve
- **Task** – What you want Claude to do (write / analyze / build / explain)
- **Rules** – Tone, format, length, examples

### Getting Better Results
```
Good Prompt + Relevant Files + Iteration
```
- Upload PDFs, DOCX, CSV, images, code files for richer context.
- Don't do one prompt and stop — iterate:
  1. Ask → 2. Review → 3. Refine → 4. Follow up

### Fixing Common Problems

| Problem | Fix |
|---|---|
| Too generic | Add more context |
| Too long/short | Specify length |
| Wrong format | Give an example/template |
| Wrong tone | Explicitly describe tone |
| Incorrect facts | Verify important information |

---

## AI Fluency – The 4D Framework

| D | Meaning |
|---|---|
| **Delegation** | Decide what AI does vs. what you do |
| **Description** | Clearly explain task, context, rules |
| **Discernment** | Evaluate and verify AI outputs |
| **Diligence** | Use AI responsibly and ethically |

---

## Evals (Testing Claude)

Purpose: Find where Claude performs well, where it needs review, and how to improve prompts.

1. Collect 5–10 real examples
2. Write prompts for similar tasks
3. Compare Claude's output
4. Improve prompts based on results

---

## Claude Desktop – Three Modes

| Mode | Use For | Think of it as |
|---|---|---|
| **Chat** | Questions, brainstorming, writing | Quick conversations |
| **Cowork** | Research, analysis, long tasks | AI employee |
| **Code** | Programming, terminal, Git | AI software engineer |

**Code sub-modes:** Ask (approve every change) · Code (auto edits, ask before commands) · Plan (strategy first)

**Access:** Chat is free; Cowork and Code require Pro+.

---

## Projects

A **Project** = dedicated workspace with memory, chat history, knowledge base, and custom instructions.

**Use when:** Work is ongoing, involves reusable files, repeated instructions, or team collaboration.

**Three components:**
1. **Knowledge Base** – Uploaded files Claude uses in every chat (no re-uploading needed)
2. **Project Instructions** – Tone, style, rules applied automatically
3. **Memory** – Files, instructions, and past chats are remembered

> When files get large, Claude uses **RAG** (searches only relevant sections automatically).

**Team permissions:** View · Edit · Owner

---

## Artifacts

**Artifacts** = standalone outputs shown in a separate window — for content you want to reuse, edit, download, or share.

**Created when content is:** large (15+ lines), self-contained, reusable, or interactive.

**Types:** Documents · Code · HTML pages · Diagrams · SVG graphics · React apps

**Sharing:** Public link (no Claude account needed) or internal team sharing (Team/Enterprise).

> If Claude doesn't create one automatically, just ask: *"Create this as an artifact."*

---

## Skills

**Skills** = reusable workflows/procedures that teach Claude how to do specific tasks.

| Type | Examples |
|---|---|
| **Anthropic Skills** | Excel, PowerPoint, Word, PDF generation (auto-used) |
| **Custom Skills** | Brand guidelines, report writing, compliance checks |

**Creating a custom skill:** Describe the workflow → answer Claude's questions → upload examples → save.

---

## Connectors

**Connectors** = Claude's bridge to external tools and services via **MCP** (Model Context Protocol — *"USB-C for AI"*).

**Types:**
- **Web Connectors** – Gmail, Google Drive, Slack, Notion, Jira, Asana, Stripe
- **Desktop Extensions** – Local files, browser, native apps (requires Claude Desktop)

**Use cases:** Check/create tasks · Search emails · Draft replies · Analyze business data

**Security:** Only accesses data you already have permission to see; permissions revocable anytime.

---

## Enterprise Search

Company-wide knowledge search across connected tools (Slack, Drive, SharePoint, Gmail, Teams, etc.).

**Use for:** Status updates · Policy lookups · Research · Onboarding · Project tracking

**Security:** Respects existing permissions; conversations remain private.

---

## Research Mode

Claude's **deep-investigation mode** — plans, searches multiple sources, follows leads, synthesizes findings, and produces a cited report.

**Process:** Plan → Search → Analyze → Report (takes 5–45 min)

**Best for:** Market research, competitor analysis, technical investigations, comprehensive reports.

### Research Prompt Formula
```
Goal + Scope + Constraints + Output Format
```
**Weak:** "Tell me about AI."
**Strong:** "Analyze the AI coding assistant market — competitors, pricing, strengths, weaknesses, future trends. Present as a structured report."

### When to use what instead

| Feature | Use For |
|---|---|
| Web Search | Quick facts, simple questions |
| Extended Thinking | Math, logic, coding problems |
| Enterprise Search | Internal company knowledge |
| Research | Deep, multi-source investigation |

---

## Feature Summary

| Feature | Purpose |
|---|---|
| Projects | Store knowledge |
| Skills | Execute workflows |
| Connectors | Access external tools |
| Enterprise Search | Search company-wide |
| Research | Deep multi-source reports |
| Artifacts | Reusable standalone outputs |

---

## Most Important Takeaways

- **Good Prompt** = Context + Task + Rules
- **Good Results** = Prompt + Files + Iteration
- **Good AI User** = Delegation + Description + Discernment + Diligence
- **Don't judge Claude by one response** — improve through iteration and evaluation.
- Claude is not just for chatting — it's a **general-purpose work assistant**.
