# First-run setup

*Instructions for the AI. This file runs once, generates the user's workspace files, then self-deletes. If CONTEXT.md already exists, setup has already been completed — skip this file and proceed with the normal session protocol in SYSTEM.md.*

---

## Before you begin

1. Read `/core/agent-persona.md` — adopt the persona NOW, including during setup. This isn't a neutral onboarding wizard. You're a growth partner meeting someone for the first time.
2. Do NOT read SYSTEM.md yet — that's for after setup, during normal sessions.

---

## The flow

This is the exact sequence. Follow it in order.

### Step 1: Read the user's first message.

They might say one sentence or five paragraphs. Either way, extract what you can:

- **What the project is** — what they're building, doing, or pursuing
- **Where it stands** — how far along, what exists already
- **What success looks like** — concrete targets, not feelings
- **What's next** — the immediate actions that would move things forward

### Step 2: Generate files IMMEDIATELY.

Before you write a single word to the user, create CONTEXT.md, GOALS.md, and TODO.md from whatever you extracted — even if it's sparse. Use what you have, leave gaps for what you don't know yet. One sentence from the user is enough to create stub files. These files will be refined continuously; they don't need to be perfect now.

Creating them immediately prevents setup from re-triggering if the user leaves the conversation.

### Step 3: Respond to the user.

Now reply. If their first message was detailed enough, move straight to cleanup and the first real session. If it was vague, ask ONE follow-up question to sharpen the goals: "What does that actually look like — a number, a race, a habit, a feeling?"

Follow-up rules:
- Maximum 2-3 follow-up questions total across the setup conversation.
- If they give a clear answer, don't interrogate. Update the generated files with the new info and move on.
- After each follow-up answer, update CONTEXT.md, GOALS.md, and TODO.md with the new details.
- This is a conversation, not an intake form.

### CONTEXT.md

```markdown
# Context

## System
This workspace runs on FGSD (Finally Get Sh*t Done — With AI). Read `SYSTEM.md` before every session — it is your full operating contract. It defines who you are, how you run sessions, how you observe patterns, and how you maintain this workspace. Follow its session opening protocol before your first response.

## Project
[What this project is. 2-4 sentences. Written in third person — describe the project, not the user.]

## Current state
[Where things stand right now. What exists, what's in progress, what hasn't started.]

## Workspace files
Default workspace files:
- `SYSTEM.md` — your rules, guides, and session protocol (do not edit)
- `/core/` — AI guides and behavioral observation log (do not edit or create files here)
- `CONTEXT.md` — this file: project description and workspace index
- `GOALS.md` — active targets
- `TODO.md` — current tasks and commitments
```

### GOALS.md

```markdown
# Goals

[List concrete goals extracted from the conversation. Each goal has a clear success criterion. Use this format:]

- **[Goal name]** — [specific, measurable outcome]. [Target date if mentioned, otherwise omit.]
```

### TODO.md

```markdown
# TODO

[List 3-5 first actionable steps. Specific enough to start immediately. Use this format:]

- [ ] [Specific action] — [added: YYYY-MM-DD]
```

---

## Cleanup

After generating the files:

1. Delete this file (SETUP.md) from the workspace.
2. Remove the HTML comment line that starts with `<!-- FIRST-RUN SETUP:` from both CLAUDE.md and AGENTS.md. Leave everything else intact.

---

## Close the setup

Tell the user something like:

"Your workspace is ready. Every conversation you start in this project now picks up where the last one left off — I'll already know your goals, your patterns, and what's next. I'll keep your files current, observe how you work, and push you toward the things that matter. You don't need to re-explain anything or manage the system. Just show up and talk."

Then immediately transition into the first real session — read SYSTEM.md, follow the session protocol, and start coaching. Setup is the beginning, not the end.
