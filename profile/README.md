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
  <a href="https://github.com/OpenLabor/community">community</a>
</p>

---

## The idea

Most AI tools are chatbots. OpenLabor is different — we build **AI employees**. Each one has a role, a personality, skills, and missions. They work on a schedule. They connect to your platforms. They cost a fraction of a human hire.

Everything that defines an AI employee is open source and lives as simple `.md` files in the **[community repo](https://github.com/OpenLabor/community)**. Anyone can create a new role, add skills, or design missions.

## How AI employees are defined

Every employee is built from three Markdown files:

### `EMPLOYEE.md` — Who they are

Defines the role, personality, and behavior. This is their identity.

```markdown
You are {{name}}, a CMO AI employee.

## Personality
You are a creative, data-driven marketing leader. You balance brand
storytelling with measurable results. You speak in clear, engaging
language and always tie strategy back to business outcomes.

## Behavior Guidelines
- Lead with the benefit, not the feature
- Always suggest A/B testing for major campaigns
- Provide ready-to-publish copy when asked, not just outlines
- Adapt tone and content to the target platform

## Boundaries
- You do not post to social media directly unless connected to a platform
- You defer budget decisions to the user while providing ROI estimates
```

### `SKILL.md` — What they can do

Structured instructions that give an employee specialized capabilities. Skills include workflows, scoring frameworks, API integrations, and decision logic.

```markdown
---
name: domain-advisor
triggers: ["check domain", "find domain", "suggest domain"]
---

# Domain Advisor
Checks availability, brainstorms names, and scores every option
across 7 business dimensions.

## Workflow
1. Parse input for domain names or business description
2. Check availability via API
3. Score each domain on memorability, length, SEO, brandability...
4. Rank and present with reasoning

## API
GET /check?domains=example.com,example.ai
```

### `MISSION.md` — What they do on autopilot

Recurring tasks that run on a schedule — the real work.

```markdown
name: Daily Social Content Engine
schedule: Daily at 9:00 AM
role: CMO
estimatedCredits: 8

## Steps
1. Review yesterday's post performance metrics
2. Identify trending topics in our industry
3. Draft platform-native posts for X, LinkedIn, and Instagram
4. Apply hashtag strategy and schedule at optimal times
5. Log results for weekly analytics review
```

## What they actually do

These aren't toy demos. Here's a sample of real missions running on the platform:

| Mission | Role | Schedule | What happens |
|---------|------|----------|-------------|
| **Daily Outbound Prospecting** | SDR | Every morning | Researches prospects, writes personalized cold emails, schedules follow-ups |
| **Daily Code Review Sweep** | CTO | Every morning | Reviews all open PRs for bugs, security issues, and style violations |
| **Campaign Performance Review** | CMO | Weekly | Pulls data from all active campaigns, ranks by ROI, drafts executive summary |
| **Pipeline Follow-Up Sweep** | SDR | Daily | Re-engages stale deals with fresh intel and personalized outreach |
| **Brand Mention Monitor** | CMO | Every 6 hours | Scans social platforms for mentions, categorizes sentiment, drafts responses |
| **Weekly Security Audit** | CTO | Weekly | Scans codebase for vulnerabilities, checks dependencies, reports findings |

## Available roles

| Role | Department | What they do |
|------|-----------|-------------|
| **CTO** | Engineering | Code review, architecture, deployments, security audits, technical docs |
| **CMO** | Marketing | Social media, email campaigns, SEO, content strategy, brand management |
| **SDR** | Sales | Cold outreach, lead qualification, pipeline management, follow-up sequences |
| **Support** | Customer Success | Ticket handling, FAQ automation, customer onboarding, escalation management |
| **Writer** | Content | Blog posts, newsletters, social copy, landing pages, case studies |
| **Designer** | Design | UI/UX, brand assets, social graphics, presentations |
| **Data Analyst** | Data | Reporting dashboards, market research, business intelligence |
| **COO** | Operations | Workflow automation, process optimization, KPI tracking |

## Contributing

The community repo is the heart of OpenLabor. Every role, skill, and mission is a Markdown file — no code required to contribute.

### Add a new skill

1. Fork [OpenLabor/community](https://github.com/OpenLabor/community)
2. Create `skills/your-skill-name/SKILL.md`
3. Follow the format: triggers, workflow steps, examples
4. Test it with any AI agent, then submit a PR

### Add a new mission

1. Create `missions/your-mission-name/MISSION.md`
2. Define the schedule, role, steps, and expected output
3. Submit a PR

### Improve an existing role

Found a better personality prompt? A missing behavior guideline? An edge case? Open a PR against the existing `EMPLOYEE.md` for that role.

### Ideas for contributions

- **SEO Auditor** skill — analyze URLs for SEO issues and opportunities
- **Competitor Analyzer** skill — research and compare competitors from public data
- **Pricing Advisor** skill — evaluate SaaS pricing strategies
- **Weekly Newsletter** mission — curate and write a weekly industry newsletter
- **Customer Feedback Digest** mission — summarize support tickets into product insights
- New roles: **HR Manager**, **Product Manager**, **Recruiter**

No contribution is too small. Fix a typo in a personality prompt. Add a step to a mission. Suggest a new trigger for a skill. It all helps.

## Built on OpenClaw

OpenLabor is powered by **[OpenClaw](https://openclaw.com)** — the open source AI agent engine. OpenClaw handles agent orchestration, multi-channel messaging (Telegram, Slack, WhatsApp, Discord, email), scheduled task execution, and real-time streaming. It's what makes it possible to give each AI employee persistent memory, platform connections, and autonomous task execution.

If you're building AI agents, check out OpenClaw — it's a remarkable project.

## License

Community contributions are MIT licensed. Use them however you want.

---

<p align="center">
  <a href="https://openlabor.ai">openlabor.ai</a> &bull; <a href="https://labor.so">labor.so</a> &bull; <a href="https://github.com/OpenLabor/community">community</a>
  <br><br>
  <sub>Built by <a href="https://github.com/yoanndefay">@yoanndefay</a> and the open source community</sub>
</p>
