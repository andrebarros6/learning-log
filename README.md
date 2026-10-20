# Learning Log

Learning to build with AI, in public — one concept a week, with an exercise you can actually run.

**[Read the curriculum →](https://barrosbuilds.com/log)** · Free, weekly, unsubscribe whenever.

---

## What this is

I could get Claude, MCP servers, RAG and agents working across five shipped products. I could not tell you why one setup worked and the next returned garbage.

So I'm learning it properly, out loud, where people can watch. Every week: one concept and one hands-on exercise.

I use Claude to build the lesson and the exercise. Then I do the exercise myself, before anyone else sees it — that part doesn't get delegated.

**I'm not an expert. That's the point.** This is a build log, not a course from someone who already figured it out.

## Who it's for

People who've used a chat model and want to build with one properly.

**What I assume:** you've used Claude or ChatGPT, and you want to know whether its output is right, not just whether it looks right. You can read code when you need to — you won't write much of it; increasingly that's the whole point. And you're willing to open a terminal: about half the exercises are short scripts you run against the API (see [What you'll need](#what-youll-need)).

**What you don't need:** to already know how to check the output — setting up those checks is most of what this teaches. Nor any experience building with an LLM, an ML background, or a job title with "engineer" in it. If you ship things with Claude and care whether it's right, that counts.

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

Exercise repos are linked as each issue ships. All are generated from a [common template](https://github.com/andrebarros6/learning-log-exercise-template), so they share the same shape. The **Kind** column tells you what you'll be doing — see [Three kinds of exercise](#three-kinds-of-exercise).

### Track 1 — Working with the models

Getting real output from the chat products.

| # | Issue | Kind | Exercise |
|---|---|---|---|
| 1 | What the model actually sees | Script | [Exercise](https://github.com/andrebarros6/learning-log-01-what-the-model-sees) |
| 2 | Prompting as engineering | Inside Claude | — |
| 3 | Structured outputs | Chat, then script | — |
| 4 | Reusable setup | Inside Claude | — |
| 5 | Context engineering | Inside Claude | — |

### Track 2 — Coding with agents

Handing real work to a coding agent, and reviewing what comes back.

| # | Issue | Kind | Exercise |
|---|---|---|---|
| 6 | First real task | Inside Claude | — |
| 7 | CLAUDE.md | Inside Claude | — |
| 8 | Plan before code | Inside Claude | — |
| 9 | Review loops | Inside Claude | — |
| 10 | What not to delegate | Inside Claude | — |
| 11 | Long tasks | Inside Claude | — |

### Track 3 — Knowing it worked

Replacing "it looks good" with something you can measure.

| # | Issue | Kind | Exercise |
|---|---|---|---|
| 12 | Evals | Script | — |
| 13 | Building a golden dataset | Script | — |
| 14 | LLM-as-judge | Script | — |

### Track 4 — Extending the tools

Connecting models to your own systems.

| # | Issue | Kind | Exercise |
|---|---|---|---|
| 15 | MCP | Written | — |
| 16 | Using existing MCP servers | Inside Claude | — |
| 17 | Building your first MCP server | Script | — |
| 18 | Connecting a model to your own database | Inside Claude | — |
| 19 | Skills | Inside Claude | — |
| 20 | Why drop below the products | Written | — |

### Track 5 — Building your own

Below the products, to the API.

| # | Issue | Kind | Exercise |
|---|---|---|---|
| 21 | The request loop | Script | — |
| 22 | Tool use | Script | — |
| 23 | Embeddings and vector search | Script | — |
| 24 | Agents | Script | — |
| 25 | RAG, end to end | Script | — |
| 26 | Prompt injection and guardrails | Script | — |

### Track 6 — Agents that run without you

Scheduled, persistent, and bounded — the ones you aren't watching.

| # | Issue | Kind | Exercise |
|---|---|---|---|
| 27 | Retrieval quality and its limits | Script | — |
| 28 | Memory that outlives the session | Script | — |
| 29 | Delegation | Script | — |
| 30 | Agents on a schedule | Script | — |

---

## How the exercises work

### Three kinds of exercise

| Kind | What you do | How you check your work |
|---|---|---|
| **Script** | Run code that calls the API, in a terminal | `pytest` |
| **Inside Claude** | Work in Claude or Claude Code, keeping a log as you go | Your log against the solution branch |
| **Written** | Argue a decision on paper — no tool | Your reasoning, written down |

More than half are scripts, and that's deliberate rather than drift. Some things only the API will tell you (issue 1 counts tokens, which the chat window never shows). Evals are scripts by nature. And from issue 21 the course drops below the products to the API on purpose — issue 20 is where you decide whether to follow. From issue 12 on, you're encouraged to drive the scripts with Claude Code: ask it to build the thing, then check what it built.

### What you'll need

- **A terminal and git.** Any terminal works. If you don't have a setup you like, use [VS Code](https://code.visualstudio.com/) — it's free, has a terminal built in, and Claude Code runs inside it.
- **Python 3.10 or newer**, for the script exercises.
- **An Anthropic API key**, from issue 1. Get one from the [Claude Console](https://platform.claude.com/). This is **separate from a Claude Pro or Max subscription** — having one doesn't give you the other. Each exercise states what it costs to run.
- **Claude Code**, from issue 6.

### Every exercise, in order

1. **Read the issue** — the concept comes first, by email or in the [archive](https://barrosbuilds.com/log).
2. **Open the exercise repo's README** — the theory restated, then *What you'll do*.
3. **Set up** — clone it and follow the README's setup.
4. **Run it on the sample.** Every repo ships one, so it works before you bring anything of your own.
5. **Check your work** — tests for scripts, your log for the others.
6. **Compare with the solution** — `git checkout solution`. `SOLUTION.md` on that branch has my version and what I found.
7. **Apply it to your own work.** This is where it stops being homework — and your own material has no solution to compare against, which is the point.
8. **Stuck or found something stale?** Ask in [Discussions](../../discussions).

Each repo's README header states its kind, what it needs and what it costs, so you know before you clone.

## Contributing

Found a bug in an exercise, or a step that's gone stale as a tool changed? Open an issue on that exercise's repo. Corrections are genuinely welcome — things breaking in public is the format, not an embarrassment.

## Elsewhere

- **Newsletter and archive** — [barrosbuilds.com/log](https://barrosbuilds.com/log)
- **Everything else I'm building** — [barrosbuilds.com](https://barrosbuilds.com)
