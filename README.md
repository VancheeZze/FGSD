# Finally Get Sh\*t Done — With AI (FGSD)

An AI coach for one project or goal. Every time you open a chat, it already knows where you are, tells you what to do next, and pushes back when you drift, make excuses or start something shiny instead.

Use it for anything you want to finish: a side business, a fitness goal, learning a skill, a creative project. No coding needed. It's a folder of plain text files that you point Claude or ChatGPT at.

**What a session looks like.** You open a chat. Instead of "How can I help?", it opens with what matters, something like: *"The README rewrite has been waiting on you for a week. What's blocking it?"* Then it helps you pick one next step and updates your goals and tasks as you talk. It learns how you work as you go. You never configure it or manage the files yourself.

**If you're a developer:** yes, under the hood it's docs, a roadmap and a task list. The point is the coach on top of them.

**Watch the 1-minute demo:**

[![FGSD demo video](https://img.youtube.com/vi/cyTCbMsLwWc/hqdefault.jpg)](https://youtu.be/cyTCbMsLwWc)

Free and open source. **Star or watch this repo** to hear when v2 lands.

---

## Quick start

### Get the folder

1. On the [repo page](https://github.com/VancheeZze/FGSD), click **Code → Download ZIP**.
2. Unzip it somewhere on your computer.

Use the ZIP rather than `git clone`: this folder will hold your personal project notes, and a clone makes it easy to push them to a public fork by accident.

### Claude (Cowork)

1. Open Claude desktop app → Cowork mode → select this folder.
2. Start a conversation. The AI will introduce itself and ask about your project.

That's it. Everything else is automatic.

### Claude (Code)

1. Open a terminal, navigate to this folder.
2. Run `claude` — the AI will introduce itself and ask about your project.

### ChatGPT (desktop app)

1. Open ChatGPT desktop app → Projects → create a new project → **Use an existing folder** → select this folder.
2. Start a conversation. The AI will introduce itself and ask about your project.

Note: if ChatGPT doesn't auto-discover the system files, tell it: "Read SYSTEM.md and follow its instructions."

### Other AI platforms

This system works with any AI that can read files. Point your AI to `SYSTEM.md` as its instructions, make sure it can access the other files in this folder, and start a conversation.

---

## What happens next

The first conversation is a short setup — the AI asks about your project, what you're working toward, and creates a few working files from your answers. Takes about two minutes.

After that, every conversation in this project picks up where the last one left off. The AI:

- **Tells you what's next** and pushes you toward the hard, important things you'd rather avoid
- **Holds you accountable** to what you said you'd do
- **Notices your patterns** over time (procrastination, avoidance, shiny object syndrome and more) and calls them out
- **Remembers** your project context, goals and commitments across every conversation in this project
- **Maintains** your workspace files automatically. You never need to touch them

You don't manage the system. You just show up and talk — about your project, yourself, your goals, whatever's on your mind. The AI handles everything else.

---

## One project per folder

This system is designed for a single project or goal. Want to use it for another area of your life? Download a fresh copy of this folder and set it up separately.

---

## What's in this folder

You don't need to know this — but if you're curious:

| File | What it does |
|------|-------------|
| `CLAUDE.md` | Entry point for Claude. You can add your own project instructions below the growth system section. |
| `AGENTS.md` | Entry point for ChatGPT. Same content as CLAUDE.md — auto-discovered by ChatGPT desktop app. |
| `SYSTEM.md` | The AI's behavioral rules — how it runs sessions, tracks patterns, maintains files. |
| `SETUP.md` | First-run setup wizard. Removed automatically after your first conversation. |
| `/core/` | The AI's reference guides and observation log. Never edit anything in here. |
| `LICENSE` | The license (CC BY 4.0). |

After setup, three new files appear:

| File | What it does |
|------|-------------|
| `CONTEXT.md` | Your project description and workspace map. |
| `GOALS.md` | Your active targets. |
| `TODO.md` | Your current tasks and commitments. |

These are working files the AI maintains for you. You *can* edit them directly if you want — the AI will see your changes next conversation.

---

## Questions?

**Will the AI change my files?**
Yes — but only files inside this folder. Nothing outside this folder is visible to the AI. Inside the folder, the AI keeps your workspace current by updating CONTEXT.md, GOALS.md, TODO.md, and its own observation log as you talk. You never need to do this manually.

**Can I use this for personal goals, not just work projects?**
Absolutely. Fitness, learning, habit building, creative projects, personal growth — anything you want to make progress on.

**What if I break something?**
The only files that matter are `SYSTEM.md` and the `/core/` folder — don't edit those. Everything else is your space. You can create files, delete files, reorganize — the AI will adapt. If something goes wrong, as long as `SYSTEM.md` and `/core/` are intact, the system will self-recover.

---

## Feedback

Found a bug, have an idea, or want to share how you're using it? [Open an issue](https://github.com/VancheeZze/FGSD/issues). Real feedback decides what goes into next versions.

---

## Support

FGSD is free. If it's helping you get sh\*t done, **[support me on Gumroad](https://vanchezze.gumroad.com/l/finally-get-shit-done-ai)**. It's the same system, and your support keeps this project going.

---

## License

Created by **Ivan Rudiuk (Vanchezze)**. Licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). You're free to use, adapt and share it, including commercially, as long as you credit the source and note any changes. Full text in `LICENSE`.
