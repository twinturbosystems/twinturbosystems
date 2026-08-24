# Ibrahim Builds

I build real things with AI agents, and test how well they actually hold up.

## Free starter kits

Each kit is a folder you download. Inside are ordinary text files: one holds the standing instructions, and each of the others is one named job. When you point an assistant at that folder, it reads those files before anything else, so it behaves like a specialist for that job instead of a general chatbot. You type one short command instead of re-explaining yourself, and your own details stay in files in the folder, on your machine.

The kits work with [Claude Code](https://docs.anthropic.com/en/docs/claude-code), Codex, or a browser chat like ChatGPT. Claude Code is the smoothest because the folder is built for it, and each kit ships a one-prompt setup for the others.

### AI Starter Kit

New to AI. It explains every term the first time it appears, goes one step at a time, and builds your first real thing with you.

[Download](https://github.com/twinturbosystems/ai-starter-harness/archive/refs/heads/main.zip) · [Repo](https://github.com/twinturbosystems/ai-starter-harness) · [One-prompt setup](https://github.com/twinturbosystems/ai-starter-harness/blob/main/ONE-PROMPT.md)

### Family Ops Kit

For parents. Meal plans, grocery lists, the week's schedule, chores, and a budget check, from a family profile that stays on your machine.

[Download](https://github.com/twinturbosystems/family-ops-harness/archive/refs/heads/main.zip) · [Repo](https://github.com/twinturbosystems/family-ops-harness) · [One-prompt setup](https://github.com/twinturbosystems/family-ops-harness/blob/main/ONE-PROMPT.md)

### Security Starter Kit

New to security. Phishing checks, account lock-down, home network and small-business basics, in plain English. Defensive only.

[Download](https://github.com/twinturbosystems/security-starter-harness/archive/refs/heads/main.zip) · [Repo](https://github.com/twinturbosystems/security-starter-harness) · [One-prompt setup](https://github.com/twinturbosystems/security-starter-harness/blob/main/ONE-PROMPT.md)

## What I actually do

Most agent demos are shown working once. That is the easy run. The interesting part is the tenth run, the run with bad input, and the run where somebody is actively trying to break it.

So I put agents and AI products through real test builds, a whole job from start to finish rather than a prompt and a screenshot. Then I check the things that decide whether it was worth using: is the output accurate, does the thing it built actually work when you run it, and where does it fail quietly instead of loudly. Quiet failure is the expensive kind, because nobody notices until it is already in production.

The security side is the same question with sharper edges. I test prompt injection defenses, tool use and sandbox escape, and the trust boundaries between the operator, the agent, its tools, and whatever text arrives from the outside world. I look at capability scoping and default-deny permissions, at per-tenant isolation, and at whether there is a kill switch a human can actually reach while the agent is mid-run.

## What I am building

- [Zoro](https://getzoro.ai): open agent-security assurance platform. It proves whether an AI agent's controls actually held, with independent evidence from a Tetragon-based evaluator, rather than the agent's own account of what it did. In active build.
- [CapitalTech](https://capitaltech.ai): government contract capture agent for small businesses. SAM.gov opportunity matching and proposal drafting. A private tool, launched and running with users, access by request.
- Multi-agent orchestration system: the orchestrator I use every day. A primary agent dispatches Codex, Claude, and Gemini subagents in isolated git worktrees with scoped tool allowlists, quality gates, and persistent memory. No public repo yet.

## Background

14 years in security: detection engineering, incident response, network and cloud defense, and offensive work. At Microsoft I am the only AI agent builder on a security engineering team. I built and run the internal agent development platform on Microsoft Foundry, security-first from the start with default-on guardrails, sandboxed tool execution, model provider abstraction, and multi-agent orchestration. I also built the AI Model Security Scanner and lead a small team building AI pentesting agents that validate internal applications on their own. Before that I was Head of Security at Swish Analytics, a hands-on CISO role where I owned every security function and took the company through SOC 2 readiness. Earlier I led security operations and incident response on contract at the U.S. Nuclear Regulatory Commission in an air-gapped facility, did digital forensics for the U.S. Department of Energy, and ran red team engagements at Coalfire for federal and commercial clients.

From December 2023 to March 2024 I taught a live introductory cloud and cybersecurity class, weekly on Sunday mornings, for a cohort of career changers. Teaching beginners is where I learned to explain this work without jargon, and it is why the kits above are free and written for someone who has never opened a terminal.

The full career history, the roles, and the education are on [LinkedIn](https://www.linkedin.com/in/ibrahim--/).

## Stack

Claude, Codex, and Gemini orchestration · Bash, PowerShell, and Terraform written by hand · Python, TypeScript, and Rust delivered through agents · Azure, AWS, GCP, Kubernetes · Sentinel, Splunk, KQL, MITRE ATT&CK

## Find me

- [ibrahim.build](https://ibrahim.build)
- [beitsystems.com](https://beitsystems.com)
- [LinkedIn](https://www.linkedin.com/in/ibrahim--/)
- [X](https://x.com/Twinturbosys)
- Instagram, coming soon

Ibrahim Builds is a creator brand from [Beit Systems LLC](https://beitsystems.com).
