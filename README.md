# Anthropic resources for building agents

Anthropic has been publishing unusually useful material on how to build agents: engineering essays that explain their own decisions, free courses, working code, and detailed docs. Most of it is written by the people who built the systems, and it's concrete about what works and what doesn't. I got tired of finding it scattered across tabs, so I collected the resources I found most useful in one place.

This is not an official Anthropic project. Anthropic owns the linked material, and it's covered by Anthropic's own terms. Links were checked in October 2026.

## Start here

| Resource | What it's for |
|---|---|
| [Building effective agents](https://www.anthropic.com/engineering/building-effective-agents) | When to use a workflow vs. an agent, and the basic patterns |
| [Prompt engineering overview](https://platform.claude.com/docs/en/build-with-claude/prompt-engineering/overview) | When prompt engineering is the right fix, plus technique guides |
| [Prompting best practices](https://platform.claude.com/docs/en/build-with-claude/prompt-engineering/claude-prompting-best-practices) | Model-specific prompting guidance for current Claude models |

## Build

| Resource | What it's for |
|---|---|
| [Tool use](https://platform.claude.com/docs/build-with-claude/tool-use) | How the API handles tool calls |
| [Writing effective tools for agents](https://www.anthropic.com/engineering/writing-tools-for-agents) | Designing tools and their descriptions so agents use them correctly |
| [Model Context Protocol](https://modelcontextprotocol.io/introduction) | The open standard for connecting models to tools and data |
| [Code execution with MCP](https://www.anthropic.com/engineering/code-execution-with-mcp) | Cutting token use when an agent has many tools |
| [Effective context engineering for AI agents](https://www.anthropic.com/engineering/effective-context-engineering-for-ai-agents) | Managing what the model sees over long, multi-turn tasks |
| [Agent SDK overview](https://platform.claude.com/docs/en/agent-sdk/overview) | Reference for building agents with the SDK |
| [Building agents with the Claude Agent SDK](https://www.anthropic.com/engineering/building-agents-with-the-claude-agent-sdk) | The agent loop and how the SDK is structured |
| [Equipping agents with Agent Skills](https://www.anthropic.com/engineering/equipping-agents-for-the-real-world-with-agent-skills) | Packaging repeatable procedures as reusable skills |

## Run longer

| Resource | What it's for |
|---|---|
| [Effective harnesses for long-running agents](https://www.anthropic.com/engineering/effective-harnesses-for-long-running-agents) | Making agents work across many sessions |
| [Managed Agents overview](https://platform.claude.com/docs/en/managed-agents/overview) | Anthropic's hosted agent runtime |
| [Scaling Managed Agents](https://www.anthropic.com/engineering/managed-agents) | Why the model, its tools, and its session state are kept separate |
| [Managed Agents permission policies](https://platform.claude.com/docs/en/managed-agents/permission-policies) | Controlling which agent and MCP tools run automatically |
| [Loop engineering: Getting started with loops](https://claude.com/blog/getting-started-with-loops) | Turn, goal, time-based, and proactive loops in Claude Code |

## Test and scale

| Resource | What it's for |
|---|---|
| [Demystifying evals for AI agents](https://anthropic.com/engineering/demystifying-evals-for-ai-agents) | How to test agents: graders, pass rates, and a practical roadmap |
| [How we built our multi-agent research system](https://www.anthropic.com/engineering/multi-agent-research-system) | A production multi-agent system, its benefits, and its costs |

## Code and examples

| Resource | What it's for |
|---|---|
| [Anthropic Cookbook](https://github.com/anthropics/anthropic-cookbook) | Working notebooks for common patterns |
| [Claude Cookbook](https://platform.claude.com/cookbook/) | A larger set of guides and examples, including tool use and evals |
| [anthropics/courses](https://github.com/anthropics/courses) | Notebook courses on API basics, prompting, evals, and tool use |
| [Managed Agents quickstart](https://github.com/anthropics/claude-quickstarts/tree/main/managed-agents/assistant-ui) | A sample app built on Managed Agents |

## Reference

| Resource | What it's for |
|---|---|
| [Engineering blog index](https://www.anthropic.com/engineering) | Every engineering post, including newer ones on harness design, auto mode, and evals |
