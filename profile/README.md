<p align="center">
  <a href="https://labor.so">
    <img src="https://labor.so/images/og.png" alt="OpenLabor — Hire AI Employees" width="100%">
  </a>
</p>

<p align="center">
  <strong>Open source AI employees you can hire, customize, and put to work.</strong>
</p>

<p align="center">
  <a href="https://openlabor.ai">openlabor.ai</a> &bull;
  <a href="https://labor.so">labor.so</a> &bull;
  <a href="https://github.com/OpenLabor/openlabor">openlabor</a>
</p>

---

## The idea

Most AI tools give you a personal assistant — a chatbot that answers your questions. OpenLabor is different. We build **AI employees** — agents with a role, a personality, specialized skills, and recurring missions. They don't wait for you to ask. They work on a schedule, connect to your platforms, and get things done.

**[OpenClaw](https://openclaw.com)** is an incredible open source engine for building personal AI assistants. We loved it so much, we built OpenLabor on top of it — extending the concept from *assistant* to *employee*. OpenClaw gives you a smart helper. OpenLabor gives you a team.

Everything that defines an AI employee is open source and lives as simple `.md` files in the **[openlabor repo](https://github.com/OpenLabor/openlabor)**. Anyone can create new roles, add skills, or design missions.

---

## Labor.so — the cloud platform

Don't want to set anything up? **[Labor.so](https://labor.so)** is the managed cloud version of OpenLabor.

- **Hire from the catalog** — pick a role, give them a name, they're ready in seconds
- **Plug in any skill** — browse community skills and activate them in one click
- **Assign missions** — set recurring tasks with a schedule and let them run
- **Connect platforms** — Telegram, Slack, WhatsApp, Discord, email — all built in
- **Usage-based pricing** — pay per credit, start free, scale as you grow

We manage the infrastructure, the AI orchestration, the platform connections, and the billing. You just hire and put them to work.

**[Try it free at labor.so](https://labor.so)**

---

## The openlabor repo

The **[openlabor repo](https://github.com/OpenLabor/openlabor)** is the heart of OpenLabor. It contains every employee definition, skill, and mission — all as Markdown files.

### Three types of files

| File | What it defines | Example |
|------|----------------|---------|
| `EMPLOYEE.md` | Who they are — role, personality, behavior, boundaries | A CTO who flags security concerns proactively and prefers code over explanations |
| `SKILL.md` | What they can do — triggers, workflows, scoring, APIs | A Domain Advisor that checks availability and scores names across 7 dimensions |
| `MISSION.md` | What they do on autopilot — schedule, steps, prompts | A Daily Code Review that scans all open PRs for bugs and security issues every morning |

### What's in there today

**5 employees** — CTO, CMO, SDR, Support, Writer
**1 skill** — Domain Advisor (with live API)
**4 missions** — Daily Social Content, Daily Outbound Prospecting, Daily Code Review, Campaign Performance Review

### Sample: SDR employee

```markdown
You are {{name}}, a SDR AI employee.

## Personality
You are a persistent, empathetic sales professional. You understand
prospect pain points and craft personalized outreach.

## Behavior Guidelines
- Personalize every outreach — reference the prospect's company and recent news
- Keep emails under 150 words with a single clear CTA
- Follow up at least 3 times before marking a lead as cold

## Boundaries
- You follow anti-spam regulations (CAN-SPAM, GDPR)
```

### Sample: Daily Code Review mission

```markdown
---
name: Daily Code Review Sweep
role: CTO
schedule: Daily at 9:00 AM
---

## Steps
1. Scan all open pull requests
2. Review for bugs, logic errors, and edge cases
3. Run security audit for vulnerabilities
4. Verify coding standards compliance
5. Post review comments and generate summary
```

---

## Contributing

Contributing is easy. Everything is a Markdown file — no code, no local setup, no CLI required.

### The fastest way to contribute

1. Go to **[OpenLabor/openlabor](https://github.com/OpenLabor/openlabor)**
2. Navigate to the folder (`employees/`, `skills/`, or `missions/`)
3. Click **"Add file" > "Create new file"** right in your browser
4. Name it (e.g. `skills/seo-auditor/SKILL.md`)
5. Write your content following the format of existing files
6. Click **"Propose new file"** — GitHub automatically creates a fork and opens a pull request

That's it. No need to install git, clone anything, or use the terminal. Just write Markdown in your browser and submit.

### What to contribute

**New employees** — define a new role with personality, skills, behavior guidelines, and boundaries.

**New skills** — give employees new capabilities with triggers, step-by-step workflows, and optionally APIs.

**New missions** — design recurring tasks with a schedule, role assignment, and step-by-step execution.

**Improvements** — better personality prompts, missing edge cases, clearer workflows, new triggers.

### Ideas

- **SEO Auditor** skill — analyze URLs for issues and opportunities
- **Competitor Analyzer** skill — research and compare competitors
- **Pricing Advisor** skill — evaluate SaaS pricing strategies
- **Weekly Newsletter** mission — curate and write a weekly industry digest
- **Customer Feedback Digest** mission — summarize tickets into product insights
- New roles: **HR Manager**, **Product Manager**, **Recruiter**, **CFO**

---

## Built on OpenClaw

OpenLabor is powered by **[OpenClaw](https://openclaw.com)** — the open source AI agent engine.

OpenClaw is a fantastic project that handles the hard parts: agent orchestration, multi-channel messaging, scheduled task execution, persistent memory, and real-time streaming. It's what makes it possible for AI employees to connect to Telegram, Slack, WhatsApp, and email — and to run missions autonomously on a schedule.

If OpenClaw is the engine, OpenLabor is the workforce built on top of it. We define the roles, skills, and missions. OpenClaw brings them to life.

---

## License

Community contributions are MIT licensed. Use them however you want.

---

<p align="center">
  <a href="https://openlabor.ai">openlabor.ai</a> &bull; <a href="https://labor.so">labor.so</a> &bull; <a href="https://github.com/OpenLabor/openlabor">openlabor</a>
  <br><br>
  <sub>Built by <a href="https://github.com/yoanndefay">@yoanndefay</a> and the open source community</sub>
</p>
