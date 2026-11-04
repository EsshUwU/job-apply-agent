# Job Apply Agent

An agent skill that helps you find relevant jobs, manage applications, and optionally prepare recruiter outreach based on your resume and preferences.

## Install

With [Node.js and npm](https://nodejs.org/) installed, run:

```bash
npx skills add https://github.com/EsshUwU/job-apply-agent --skill job-apply-agent
```

Follow the prompts to select your agent and installation scope. Restart your agent or start a new session if needed for it to discover the skill.

## Get started

1. Place your resume in your working directory.
2. Ask your agent: **“Use the job-apply-agent skill to help me find and apply for jobs.”**
3. Answer the agent's questions about your preferences and permissions, then review and confirm your profile.

The agent can search job boards and company career pages, track confirmed applications, and prepare outreach leads. Submitting applications and sending outreach are subject to your permissions. A browser tool with navigation and interaction is needed for the browser workflow; the skill will guide you if one is not available. You handle logins, verification, and CAPTCHAs yourself.

## Privacy

The skill keeps your preferences and campaign records in your working directory. These files may contain personal information, so review them before sharing or committing them. Do not give your agent passwords, one-time codes, or other authentication secrets.
