# Anthropic resources for building agents

Anthropic has been publishing unusually useful material on how to build agents: engineering essays that explain their own decisions, free courses, working code, and detailed docs. Most of it is written by the people who built the systems, and it's concrete about what works and what doesn't. I got tired of finding it scattered across tabs, so I collected the resources I found most useful in one place, with a short note on what each one is for.

This is not an official Anthropic project. Anthropic owns the linked material, and it's covered by Anthropic's own terms. Links were checked in October 2026.

## Resources

Sorted roughly by topic, from prompting and tools through to evals and multi-agent systems, with code and the engineering index at the end.

| Resource | What it's for | Link |
|---|---|---|
| Prompt engineering overview | When prompt engineering is the right fix, plus technique guides | [Read](https://platform.claude.com/docs/en/build-with-claude/prompt-engineering/overview) |
| Prompting best practices | Model-specific prompting guidance for current Claude models | [Read](https://platform.claude.com/docs/en/build-with-claude/prompt-engineering/claude-prompting-best-practices) |
| Tool use | How the API handles tool calls | [Read](https://platform.claude.com/docs/build-with-claude/tool-use) |
| Building effective agents | When to use a workflow vs. an agent, and the basic patterns | [Read](https://www.anthropic.com/engineering/building-effective-agents) |
| Writing effective tools for agents | Designing tools and their descriptions so agents use them correctly | [Read](https://www.anthropic.com/engineering/writing-tools-for-agents) |
| Model Context Protocol | The open standard for connecting models to tools and data | [Read](https://modelcontextprotocol.io/introduction) |
| Code execution with MCP | Cutting token use when an agent has many tools | [Read](https://www.anthropic.com/engineering/code-execution-with-mcp) |
| Effective context engineering for AI agents | Managing what the model sees over long, multi-turn tasks | [Read](https://www.anthropic.com/engineering/effective-context-engineering-for-ai-agents) |
| Agent SDK overview | Reference for building agents with the SDK | [Read](https://platform.claude.com/docs/en/agent-sdk/overview) |
| Building agents with the Claude Agent SDK | The agent loop and how the SDK is structured | [Read](https://www.anthropic.com/engineering/building-agents-with-the-claude-agent-sdk) |
| Equipping agents with Agent Skills | Packaging repeatable procedures as reusable skills | [Read](https://www.anthropic.com/engineering/equipping-agents-for-the-real-world-with-agent-skills) |
| Effective harnesses for long-running agents | Making agents work across many sessions | [Read](https://www.anthropic.com/engineering/effective-harnesses-for-long-running-agents) |
| Managed Agents overview | Anthropic's hosted agent runtime | [Read](https://platform.claude.com/docs/en/managed-agents/overview) |
| Scaling Managed Agents | Why the model, its tools, and its session state are kept separate | [Read](https://www.anthropic.com/engineering/managed-agents) |
| Managed Agents permission policies | Controlling which agent and MCP tools run automatically | [Read](https://platform.claude.com/docs/en/managed-agents/permission-policies) |
| Loop engineering: Getting started with loops | Turn, goal, time-based, and proactive loops in Claude Code | [Read](https://claude.com/blog/getting-started-with-loops) |
| Demystifying evals for AI agents | How to test agents: graders, pass rates, and a practical roadmap | [Read](https://anthropic.com/engineering/demystifying-evals-for-ai-agents) |
| How we built our multi-agent research system | A production multi-agent system, its benefits, and its costs | [Read](https://www.anthropic.com/engineering/multi-agent-research-system) |
| Anthropic Cookbook | Working notebooks for common patterns | [GitHub](https://github.com/anthropics/anthropic-cookbook) |
| Claude Cookbook | A larger set of guides and examples, including tool use and evals | [Browse](https://platform.claude.com/cookbook/) |
| anthropics/courses | Notebook courses on API basics, prompting, evals, and tool use | [GitHub](https://github.com/anthropics/courses) |
| Managed Agents quickstart | A sample app built on Managed Agents | [GitHub](https://github.com/anthropics/claude-quickstarts/tree/main/managed-agents/assistant-ui) |
| Engineering blog index | Every engineering post, including newer ones on harness design, auto mode, and evals | [Browse](https://www.anthropic.com/engineering) |
