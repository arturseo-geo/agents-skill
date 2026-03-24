# agents-skill

> Built by **[Artur Ferreira](https://github.com/arturseo-geo)** @ **[The GEO Lab](https://thegeolab.net)** · [𝕏 @TheGEO_Lab](https://x.com/TheGEO_Lab) · [LinkedIn](https://linkedin.com/in/arturgeo) · [Reddit](https://www.reddit.com/user/Alternative_Teach_74/)

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![Licence](https://img.shields.io/badge/licence-MIT-green)
![Architectures](https://img.shields.io/badge/architectures-6-orange)
![Claude Code](https://img.shields.io/badge/Claude_Code-skill-blueviolet)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen)](https://github.com/arturseo-geo/agents-skill/blob/main/CONTRIBUTING.md)

AI agent systems skill for [Claude Code](https://docs.anthropic.com/en/docs/claude-code) — ReAct, Plan-and-Execute, reflection loops, Tree of Thoughts, LATS, MCP integration, multi-agent orchestration with LangChain/LangGraph/CrewAI/AutoGen/Claude Agent SDK, evaluation and observability.

## Who This Is For

- **Developers building AI agents** who want proven architecture patterns, not tutorials
- **Teams evaluating frameworks** (LangGraph vs CrewAI vs AutoGen vs Claude Agent SDK)
- **Claude Code users** who want to design multi-agent workflows inside their CLI
- **Anyone doing tool use** who needs structured patterns for reliable agent loops

## What Makes This Different

Agent tutorials show "hello world" demos. This skill covers production patterns and failure modes:

- ✅ **6 architecture patterns** — ReAct, Plan-and-Execute, Reflection, Tree of Thoughts, LATS, with selection guide
- ✅ **MCP integration** — Model Context Protocol tool patterns, function calling best practices
- ✅ **Multi-agent orchestration** — handoff patterns, shared memory, framework comparison
- ✅ **Framework comparison** — Claude Agent SDK vs LangGraph vs CrewAI vs AutoGen, honest tradeoffs
- ✅ **Tool use patterns** — composition, structured outputs, security considerations
- ✅ **Evaluation & observability** — LLM-as-judge, testing patterns, cost tracking, alerting
- ✅ **Error recovery** — retry strategies, graceful degradation, circuit breakers

## Install

```bash
# Clone
git clone https://github.com/arturseo-geo/agents-skill.git ~/.claude/skills/agents

# Or install all 12 skills at once
git clone https://github.com/arturseo-geo/claude-code-skills.git
cp -r claude-code-skills/skills/agents ~/.claude/skills/
```

## File Structure

```
agents-skill/
├── SKILL.md                  — Core skill: architectures, patterns, tool use, memory, orchestration
├── references/
│   ├── patterns.md           — ReAct, Plan-and-Execute, Reflection, ToT, LATS, selection guide
│   ├── tools.md              — MCP integration, function calling, tool composition, security
│   ├── multi-agent.md        — Handoff patterns, shared memory, framework comparison
│   └── evaluation.md         — Testing, LLM-as-judge, observability, cost tracking, alerting
└── .github/                  — Issue templates and PR template
```

## Related Repos

- [claude-code-skills](https://github.com/arturseo-geo/claude-code-skills) — Full collection of 12 skills
- [content-pipeline-skill](https://github.com/arturseo-geo/content-pipeline-skill) — Real-world 6-agent pipeline using these patterns

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines. PRs welcome.

---

Built and maintained by **[Artur Ferreira](https://github.com/arturseo-geo)** @ **[The GEO Lab](https://thegeolab.net)** · [MIT License](LICENSE)
