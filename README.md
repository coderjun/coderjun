## Jun Heider

Engineering leader and systems builder. I have led streaming and video engineering organizations of 20 to 30 at Dolby and RealEyes, and I still design and build AI-enabled and media-workflow-focused systems myself.

Currently: consulting through Ajnunna Systems, Subject Matter Expert and committee co-chair at the Streaming Video Technology Alliance (SVTA). Previously: Director of Media Streaming Solutions at Dolby Laboratories, CTO at RealEyes Media.

### Selected work

**Streaming and AI systems**

- **[live-ad-decisioning-poc](https://github.com/coderjun/live-ad-decisioning-poc)**
  Proof of concept for live streaming ad breaks under a hard time limit. Deterministic code handles cue timing and eligibility, a typed-decision model judges brand safety and contextual fit with calibrated confidence, and video generation runs only when those judgments clear and the break has time. Every decision is logged.
- **[shaka-packager-mcp-server](https://github.com/coderjun/shaka-packager-mcp-server)**
  Model Context Protocol server exposing Shaka Packager to AI agents, so media packaging becomes something an agent can drive directly.
- **[vse-cmcd-monitor](https://github.com/coderjun/vse-cmcd-monitor)**
  Streaming anomaly detection over Common Media Client Data, built in the open with the AI pair-programming session logs committed alongside the code.

**Agentic development tooling**

- **[ts-bumpers](https://github.com/coderjun/ts-bumpers)**
  TypeScript starter for AI-agent development whose guardrails block rather than advise. Claude Code hooks, pre-commit checks, and CI enforce formatting, lint, types, tests, diagrams, and secret scanning, so neither an agent nor a person can skip them.
- **[copilot-assigner-worker](https://github.com/coderjun/copilot-assigner-worker)**
  Cloudflare Worker that assigns GitHub issues to the GitHub Copilot coding agent over OAuth, so GitHub Actions workflows can hand work to the agent. Personal access tokens and GitHub Apps cannot see the agent as an assignable actor; this closes that gap.


### What I write and teach

- Working on a seven-module course on applying AI across the software development lifecycle, covering agentic workflows, spec-driven development, AI in continuous integration, and production monitoring.
- Co-author, *Professional Adobe Flex 3* (Wrox/Wiley).
- Apache Flex Project Management Committee member through the donation of the Adobe Flex SDK to the Apache Software Foundation.
- Speaker at Demuxed, NAB Streaming Summit, Streaming Media, and Streaming Tech Sweden.

### How I work

I use AI agents, agentic tooling, and Model Context Protocol servers to build software and solutions in the most efficient way I can, most of it in OTT and streaming. Node and TypeScript are the deeper stack. Python and AWS carry the agent work.

Day to day: Claude Code, ChatGPT, Perplexity, and NotebookLM, plus authored Claude Skills, MCP servers for domain tooling, GitHub Copilot automation, and scaffolding that drives four agent command-line tools from one specification.

The judgment matters as much as the tooling. I weigh whether AI belongs in a given task rather than assuming it does, and I work trust but verify, because these systems can mislead and hallucinate. Agent-written code gets held to the same bar as anything else.

[junheider.com](https://junheider.com) · [LinkedIn](https://linkedin.com/in/junheider)
