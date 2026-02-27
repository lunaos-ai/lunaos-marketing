# Product Hunt Listing — LunaOS

## Tagline (60 chars max)
28 AI agents for your entire software development lifecycle

## Description
LunaOS gives developers 28 specialized AI agents that cover every stage of the SDLC — code review, testing, security audits, deployment, documentation, and more.

**How it works:**

1. Install the CLI: `npm i -g @luna-agents/cli`
2. Run an agent: `luna run code-review`
3. Get expert-level results in seconds

**Key features:**

- **28 Built-in Agents** — Code review, testing, security, deployment, docs, and more
- **RAG-Powered Context** — Connect your GitHub repo and agents understand your codebase
- **Agent Chains** — Combine agents into automated multi-step workflows
- **Visual Studio** — Drag-and-drop workflow builder at studio.lunaos.ai
- **Dashboard** — Run agents from your browser at agents.lunaos.ai
- **API & CLI** — Integrate into CI/CD pipelines with API keys
- **Edge-First** — Runs on Cloudflare Workers for sub-10ms cold starts

**Built for developers who want:**
- Faster code reviews with AI that knows their codebase
- Automated security audits on every PR
- Test generation that covers edge cases
- Deployment checklists that never miss a step

Free tier: 100 agent runs/month. Pro: unlimited runs, custom agents, team workspaces.

## Topics
- Developer Tools
- Artificial Intelligence
- Productivity
- Code Review
- DevOps

## Maker Comment
Hey Product Hunt! I'm the solo developer behind LunaOS.

I built LunaOS because I was tired of context-switching between different AI tools for different parts of my workflow. I wanted ONE platform where I could run a code review, generate tests, audit security, and prepare a deployment — all from the same CLI.

After 4 sprints of building, LunaOS now has 28 agents, a RAG pipeline that actually understands your codebase, a visual workflow builder, and runs entirely on Cloudflare's edge.

The free tier gives you 100 agent runs/month — enough to try every agent. I'd love your feedback!

## First Comment
Thanks for checking out LunaOS! Here's a quick demo:

```bash
# Install
npm i -g @luna-agents/cli

# Initialize in your project
luna init

# Run your first agent
luna run code-review

# Chain multiple agents
luna chain full-review
```

Happy to answer any questions about the architecture, the agents, or how RAG context injection works under the hood.

## Links
- Website: https://lunaos.ai
- Dashboard: https://agents.lunaos.ai
- Studio: https://studio.lunaos.ai
- Docs: https://docs.lunaos.ai
- CLI: https://www.npmjs.com/package/@luna-agents/cli
