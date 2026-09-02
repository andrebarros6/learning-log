# Learning Log

Learning to build with AI, in public — one concept a week, with an exercise you can actually run.

**[Read the curriculum →](https://barrosbuilds.com/log)** · Free, weekly, unsubscribe whenever.

---

## What this is

I could get Claude, MCP servers, RAG and agents working across five shipped products. I could not tell you why one setup worked and the next returned garbage.

So I'm learning it properly, out loud, where people can watch. Every week: one concept, one hands-on exercise, and an honest log of what broke.

I use Claude to build the lesson and the exercise. Then I do the exercise myself, before anyone else sees it — that part doesn't get delegated. The parts that break get published too. That's most of the value.

**I'm not an expert. That's the point.** This is a build log, not a course from someone who already figured it out.

## Who it's for

People who've used a chat model and want to build with one properly.

**What I assume:** you've used Claude or ChatGPT, and you can read code, run it, and tell when it's wrong. You don't have to write much of it — increasingly that's the whole point — but you do need to spot a plausible answer that isn't right.

**What you don't need:** any experience building with an LLM, an ML background, or a job title with "engineer" in it. If you ship things with Claude and read what it gives you, that counts.

If you've never used an LLM at all, start elsewhere and come back — this doesn't explain what a prompt is.

## This repo

An index. Each issue ships its own public exercise repo; this is where you find them, and where discussion happens for all of them.

- **Exercises** — one repo per issue, linked in the table below as they ship
- **[Discussions](../../discussions)** — one place for questions about any exercise
- **The issues themselves** — delivered by email, archived at [barrosbuilds.com/log](https://barrosbuilds.com/log)

Everything here is public and free. The exercises are yours to keep, and they stay updated as the tools change.

---

## The curriculum

Thirty issues, six tracks. You start at issue 1 whenever you join — the sequence doesn't assume you read last week's.

Exercise repos are linked as each issue ships.

### Track 1 — Working with the models

Getting real output from the chat products.

| # | Issue | Exercise |
|---|---|---|
| 1 | What the model actually sees | — |
| 2 | Prompting as engineering | — |
| 3 | Structured outputs | — |
| 4 | Reusable setup | — |
| 5 | Context engineering | — |

### Track 2 — Coding with agents

Handing real work to a coding agent, and reviewing what comes back.

| # | Issue | Exercise |
|---|---|---|
| 6 | First real task | — |
| 7 | CLAUDE.md | — |
| 8 | Plan before code | — |
| 9 | Review loops | — |
| 10 | What not to delegate | — |
| 11 | Long tasks | — |

### Track 3 — Knowing it worked

Replacing "it looks good" with something you can measure.

| # | Issue | Exercise |
|---|---|---|
| 12 | Evals | — |
| 13 | Building a golden dataset | — |
| 14 | LLM-as-judge | — |

### Track 4 — Extending the tools

Connecting models to your own systems.

| # | Issue | Exercise |
|---|---|---|
| 15 | MCP | — |
| 16 | Using existing MCP servers | — |
| 17 | Building your first MCP server | — |
| 18 | Connecting a model to your own database | — |
| 19 | Skills | — |
| 20 | Why drop below the products | — |

### Track 5 — Building your own

Below the products, to the API.

| # | Issue | Exercise |
|---|---|---|
| 21 | The request loop | — |
| 22 | Tool use | — |
| 23 | Embeddings and vector search | — |
| 24 | Agents | — |
| 25 | RAG, end to end | — |
| 26 | Prompt injection and guardrails | — |

### Track 6 — Agents that run without you

Scheduled, persistent, and bounded — the ones you aren't watching.

| # | Issue | Exercise |
|---|---|---|
| 27 | Retrieval quality and its limits | — |
| 28 | Memory that outlives the session | — |
| 29 | Delegation | — |
| 30 | Agents on a schedule | — |

---

## How the exercises work

Each exercise repo has the same shape:

- **README** with the theory — stable, doesn't change
- **A runnable starter** — versioned, updated as the tools change
- **A solution branch** — check yourself against it after you've tried
- **A discussion thread** — [here](../../discussions), so questions live in one place

They're designed to be applied to your own projects, not just followed. Most exercises end with a line pushing you to point it at something of yours — that's where the learning actually happens.

## Contributing

Found a bug in an exercise, or a step that's gone stale as a tool changed? Open an issue on that exercise's repo. Corrections are genuinely welcome — things breaking in public is the format, not an embarrassment.

## Elsewhere

- **Newsletter and archive** — [barrosbuilds.com/log](https://barrosbuilds.com/log)
- **Everything else I'm building** — [barrosbuilds.com](https://barrosbuilds.com)
