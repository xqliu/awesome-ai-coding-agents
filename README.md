# Awesome AI Coding Agents [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of AI coding agents: terminal agents, editor agents, background agents, code review agents, harnesses, benchmarks and guides.

Every entry links to the official site or the canonical repository. This space moves fast, so check the linked page before you adopt a tool.

## Contents

- [CLI Agents](#cli-agents)
- [IDE and Editor Agents](#ide-and-editor-agents)
- [Background and Autonomous Agents](#background-and-autonomous-agents)
- [Code Review Agents](#code-review-agents)
- [Open Source Agents](#open-source-agents)
- [Agent Harnesses and SDKs](#agent-harnesses-and-sdks)
- [Tooling and Sandboxes](#tooling-and-sandboxes)
- [Benchmarks and Leaderboards](#benchmarks-and-leaderboards)
- [Guides](#guides)
<!-- toc-end -->

## CLI Agents

- [Aider](https://aider.chat) - Terminal pair programmer that edits files in a local Git repository and commits each change.
- [Amazon Q Developer CLI](https://aws.amazon.com/q/developer/) - Agentic chat in the terminal from AWS, with MCP support and AWS account context.
- [Amp](https://ampcode.com) - Agentic coding tool from Sourcegraph that runs in the terminal and in editor extensions.
- [Claude Code](https://github.com/anthropics/claude-code) - Anthropic's terminal agent that reads a codebase, edits files, runs commands and opens pull requests.
- [Codex CLI](https://github.com/openai/codex) - OpenAI's local coding agent for the terminal, written in Rust.
- [Crush](https://github.com/charmbracelet/crush) - Terminal coding agent from Charm with a full-screen TUI and support for many model providers.
- [Cursor CLI](https://cursor.com/cli) - Terminal version of the Cursor agent, usable in scripts and CI.
- [Gemini CLI](https://github.com/google-gemini/gemini-cli) - Google's open source terminal agent for Gemini models, with built-in tools and MCP support.
- [GitHub Copilot CLI](https://github.com/features/copilot/cli) - Copilot agent for the terminal, with access to GitHub issues and pull requests.
- [Goose](https://goose-docs.ai/) - Open source extensible agent from Block that installs, executes, edits and tests with any model.
- [OpenCode](https://opencode.ai) - Open source terminal agent with a client-server design and a shareable session model.
- [Pi](https://github.com/earendil-works/pi) - Agent toolkit with a unified model API, an agent loop, a TUI and a coding agent CLI.
- [Qwen Code](https://github.com/QwenLM/qwen-code) - Command-line agent adapted for the Qwen3-Coder models.
- [Warp](https://www.warp.dev/code) - Terminal and code editor with agentic workflows across several models.

## IDE and Editor Agents

- [Antigravity](https://antigravity.google) - Google's agent-first development environment built around Gemini.
- [Augment Code](https://www.augmentcode.com) - Editor agent with a context engine aimed at large codebases.
- [avante.nvim](https://github.com/avante-corp/avante.nvim) - Neovim plugin that brings a Cursor-style AI editing flow to the editor.
- [claudecode.nvim](https://github.com/coder/claudecode.nvim) - Neovim integration that talks to Claude Code over its editor protocol.
- [Cline](https://cline.bot) - Open source autonomous coding agent for VS Code and JetBrains that plans, edits and runs commands with approval.
- [CodeCompanion.nvim](https://github.com/olimorris/codecompanion.nvim) - Neovim plugin with chat, inline editing and agent workflows.
- [Continue](https://continue.dev) - Open source IDE extension for building and running custom coding assistants and agents.
- [Cursor](https://cursor.com) - AI-first code editor with an agent mode that edits across files and runs commands.
- [GitHub Copilot](https://github.com/features/copilot) - Completions, chat and agent mode in the editor and across GitHub.
- [JetBrains Junie](https://junie.jetbrains.com/) - Coding agent built into JetBrains IDEs that plans and executes multi-step tasks.
- [Kilo](https://kilo.ai) - Open source agent that runs as a VS Code extension, a CLI and a cloud agent.
- [Kiro](https://kiro.dev) - Agentic IDE from AWS built around specs, hooks and steering files.
- [Trae](https://www.trae.ai) - AI development environment with a coding agent and a separate agent for general work.
- [Windsurf](https://devin.ai/desktop) - Agentic editor from Cognition, now shipped as the Devin desktop app.
- [Zed](https://zed.dev/ai) - High-performance editor with native agent panels and support for external agents.

## Background and Autonomous Agents

- [Claude Code GitHub Action](https://github.com/anthropics/claude-code-action) - Runs Claude Code inside GitHub Actions to answer issues and open pull requests.
- [Codex Action](https://github.com/openai/codex-action) - Official GitHub Action for running Codex in a workflow.
- [Codex Cloud](https://learn.chatgpt.com/docs/cloud) - Hosted environment where Codex works on tasks in parallel and returns pull requests.
- [Copilot Coding Agent](https://docs.github.com/en/copilot/concepts/agents/cloud-agent/about-cloud-agent) - Assign a GitHub issue to Copilot and it works in a hosted environment and opens a pull request.
- [Devin](https://devin.ai) - Hosted autonomous software engineer from Cognition that works on tasks in its own environment.
- [Factory](https://factory.com) - Platform of Droid agents that run in the terminal, the browser and CI.
- [Jules](https://jules.google) - Google's asynchronous agent that clones a repository into a cloud VM and proposes changes.
- [Open SWE](https://github.com/langchain-ai/open-swe) - Open source asynchronous coding agent from LangChain that plans and executes tasks on a repository.
- [OpenHands Cloud](https://www.openhands.dev/) - Hosted version of OpenHands that runs agents against your repositories.
- [Orbi](https://github.com/orbi-build/orbi) - Self-hosted runner that takes a labeled GitHub issue to a pull request, gates the merge on a separate review session, and publishes the tagged release.
- [Tembo](https://www.tembo.io) - Cloud platform for running third-party coding agents in shareable, isolated environments.

## Code Review Agents

- [Claude Code Security Review](https://github.com/anthropics/claude-code-security-review) - GitHub Action that uses Claude to look for security problems in a diff.
- [CodeAnt AI](https://codeant.ai/) - Code review and code quality platform covering security, dead code and infrastructure checks.
- [CodeRabbit](https://www.coderabbit.ai) - Review agent for pull requests, the IDE and the CLI, with line-by-line comments and summaries.
- [cubic](https://www.cubic.dev) - Review agent that aims for a low false-positive rate by filtering its own findings.
- [Ellipsis](https://www.ellipsis.dev) - Reviews pull requests, answers questions and can push fixes as commits.
- [Entelligence](https://entelligence.ai/) - Review and routing layer that keeps shared memory of a codebase, its pull requests and its incidents.
- [Graphite](https://graphite.com/features/ai-reviews) - Automated review inside the Graphite stacked pull request workflow.
- [Greptile](https://www.greptile.com) - Review agent that builds a graph of a codebase and comments on pull requests.
- [PR-Agent](https://github.com/The-PR-Agent/pr-agent) - Open source tool that describes, reviews and improves pull requests from a set of commands.
- [Qodo](https://www.qodo.ai) - Multi-agent review platform with Git integration, IDE plugins and a CLI toolbox.
- [Sourcery](https://www.sourcery.ai) - Reviews pull requests and suggests refactorings in Python and other languages.

## Open Source Agents

- [bolt.diy](https://github.com/stackblitz-labs/bolt.diy) - Community fork of Bolt that builds and runs full-stack apps in the browser with any model.
- [MetaGPT](https://github.com/FoundationAgents/MetaGPT) - Multi-agent framework that assigns product, architecture and engineering roles to agents.
- [mini-swe-agent](https://github.com/SWE-agent/mini-swe-agent) - Minimal agent in about 100 lines of Python that still scores well on SWE-bench.
- [opcode](https://github.com/winfunc/opcode) - Desktop app and toolkit for running Claude Code sessions, custom agents and sandboxes.
- [OpenEvolve](https://github.com/algorithmicsuperintelligence/openevolve) - Evolutionary coding agent that improves programs against a scoring function.
- [OpenHands](https://github.com/OpenHands/OpenHands) - Open platform for agents that write code, run commands and browse the web.
- [Plandex](https://github.com/plandex-ai/plandex) - Terminal agent built for large multi-file tasks, with a diff sandbox and version control.
- [SWE-agent](https://github.com/SWE-agent/SWE-agent) - Research agent from Princeton that fixes GitHub issues through an agent-computer interface.
- [Tabby](https://github.com/TabbyML/tabby) - Self-hosted coding assistant with completions, chat and repository context.

## Agent Harnesses and SDKs

- [Agent Client Protocol](https://github.com/agentclientprotocol/agent-client-protocol) - Open protocol that lets any editor talk to any coding agent.
- [Claude Agent SDK for Python](https://github.com/anthropics/claude-agent-sdk-python) - Python library for building agents on the Claude Code harness.
- [Claude Agent SDK for TypeScript](https://github.com/anthropics/claude-agent-sdk-typescript) - TypeScript library for building agents on the Claude Code harness.
- [Deep Agents](https://github.com/langchain-ai/deepagents) - LangChain library for long-running agents with planning, subagents and a file system.
- [Google ADK](https://github.com/google/adk-python) - Agent Development Kit for building, evaluating and deploying agents in Python.
- [LangGraph](https://github.com/langchain-ai/langgraph) - Low-level library for building stateful, graph-shaped agent workflows.
- [Mastra](https://github.com/mastra-ai/mastra) - TypeScript agent framework with workflows, memory, evals and tool calling.
- [Microsoft Agent Framework](https://github.com/microsoft/agent-framework) - Framework for building and running agents and multi-agent workflows in .NET and Python.
- [Model Context Protocol](https://modelcontextprotocol.io) - Open protocol for connecting agents to tools, data sources and prompts.
- [OpenAI Agents SDK for JavaScript](https://github.com/openai/openai-agents-js) - JavaScript and TypeScript framework for multi-agent workflows with handoffs and guardrails.
- [OpenAI Agents SDK for Python](https://github.com/openai/openai-agents-python) - Python framework for multi-agent workflows with tracing, handoffs and guardrails.
- [OpenHands Software Agent SDK](https://github.com/OpenHands/software-agent-sdk) - Modular SDK for building software agents on the OpenHands runtime.
- [Pydantic AI](https://github.com/pydantic/pydantic-ai) - Python agent framework with typed outputs and validation from the Pydantic team.
- [smolagents](https://github.com/huggingface/smolagents) - Small Hugging Face library for agents that act by writing and running Python code.
- [Strands Agents](https://github.com/strands-agents/harness-sdk) - Open source SDK from AWS for building an agent harness and controlling it end to end.
- [Vercel AI SDK](https://github.com/vercel/ai) - TypeScript toolkit for building agents and AI interfaces across many model providers.

## Tooling and Sandboxes

- [ccmanager](https://github.com/kbwo/ccmanager) - Session manager for running several coding agents across Git worktrees.
- [Claude Code UI](https://github.com/siteboon/claudecodeui) - Web and mobile interface for driving Claude Code, Codex, Cursor CLI and OpenCode.
- [Claude Squad](https://github.com/smtg-ai/claude-squad) - Terminal manager for running multiple agents in parallel on isolated Git worktrees.
- [Container Use](https://github.com/dagger/container-use) - Dagger tool that gives each agent its own container and Git branch.
- [Context7](https://github.com/upstash/context7) - MCP server that feeds up-to-date library documentation to coding agents.
- [Daytona](https://github.com/daytonaio/daytona) - Infrastructure for running AI-generated code in secure elastic sandboxes.
- [E2B](https://github.com/e2b-dev/E2B) - Cloud sandboxes for running code produced by agents.
- [GitMCP](https://github.com/idosal/git-mcp) - Remote MCP server that turns any GitHub repository into a documentation source.
- [HumanLayer](https://github.com/humanlayer/humanlayer) - Approval and human-in-the-loop layer for agents working on real codebases.
- [Serena](https://github.com/oraios/serena) - MCP toolkit that gives agents semantic code retrieval and symbol-level editing.
- [Spec Kit](https://github.com/github/spec-kit) - GitHub toolkit for spec-driven development with coding agents.
- [Vibe Kanban](https://github.com/BloopAI/vibe-kanban) - Kanban board for queuing, reviewing and orchestrating coding agent tasks.

## Benchmarks and Leaderboards

- [Aider Polyglot Leaderboard](https://aider.chat/docs/leaderboards/) - Ranks models on multi-language editing tasks run through the Aider harness.
- [Code Arena](https://arena.ai/code) - Human preference voting on code and web development outputs from LMArena.
- [EvalPlus Leaderboard](https://evalplus.github.io/leaderboard.html) - HumanEval+ and MBPP+ results with stricter test suites.
- [LiveBench](https://livebench.ai) - Contamination-resistant benchmark with a coding category refreshed over time.
- [LiveCodeBench](https://livecodebench.github.io/) - Contest-style coding benchmark with problems collected continuously.
- [Multi-SWE-bench](https://github.com/multi-swe-bench/multi-swe-bench) - SWE-bench extended beyond Python to seven more languages.
- [SWE-bench](https://www.swebench.com) - Benchmark of real GitHub issues and the leaderboards built on it.
- [SWE-bench Multimodal](https://www.swebench.com/multimodal.html) - Variant with issues that include images and visual bug reports.
- [SWE-bench repository](https://github.com/SWE-bench/SWE-bench) - Code and harness for running the SWE-bench evaluation.
- [Terminal-Bench](https://www.tbench.ai/) - Benchmark for agents that work in a terminal, with a public leaderboard.
- [Terminal-Bench repository](https://github.com/harbor-framework/terminal-bench-1) - Task set and harness behind Terminal-Bench.

## Guides

- [AGENTS.md](https://agents.md) - Open format for the instruction file that many coding agents read from a repository.
- [Agentic Coding Recommendations](https://lucumr.pocoo.org/2025/6/12/agentic-coding/) - Armin Ronacher on the setup and habits that make agents useful day to day.
- [Building Effective Agents](https://www.anthropic.com/engineering/building-effective-agents) - Anthropic on simple patterns that work better than complex frameworks.
- [Claude Code Best Practices](https://code.claude.com/docs/en/best-practices) - Anthropic's guidance on context files, permissions and workflows.
- [Codex Documentation](https://learn.chatgpt.com/docs) - Official docs for the Codex CLI, IDE extension and cloud agent.
- [Effective Context Engineering for AI Agents](https://www.anthropic.com/engineering/effective-context-engineering-for-ai-agents) - How to choose what goes into an agent's context window and what stays out.
- [Exploring Generative AI](https://martinfowler.com/articles/exploring-gen-ai.html) - Long-running memo series from Thoughtworks on using AI in real engineering work.
- [Gemini CLI Documentation](https://google-gemini.github.io/gemini-cli/docs/) - Configuration, tools, extensions and MCP setup for Gemini CLI.
- [GitHub Copilot Coding Agent Best Practices](https://docs.github.com/en/copilot/tutorials/cloud-agent/get-the-best-results) - How to scope issues and set up a repository so the hosted Copilot agent succeeds.
- [How to Build an Agent](https://ampcode.com/notes/how-to-build-an-agent) - Walkthrough of writing a working code-editing agent in a few hundred lines.
- [My AI Skeptic Friends Are All Nuts](https://fly.io/blog/youre-all-nuts/) - Thomas Ptacek's argument for agentic coding, and a useful map of the objections.
- [Programming with Agents](https://crawshaw.io/blog/programming-with-agents) - David Crawshaw on what changes in practice once agents write most of the code.
- [Ralph Wiggum as a Software Engineer](https://ghuntley.com/ralph/) - Geoffrey Huntley on running an agent in a loop until the task is finished.
- [Simon Willison on AI-Assisted Programming](https://simonwillison.net/tags/ai-assisted-programming/) - Running collection of hands-on notes and experiments with coding agents.
- [Writing Effective Tools for Agents](https://www.anthropic.com/engineering/writing-tools-for-agents) - Designing tool definitions that agents actually use correctly.

## Related Lists

- [awesome-agent-skills](https://github.com/alihesari/awesome-agent-skills) - Agent Skills (SKILL.md) for Claude Code, Codex, Cursor and other agents.
- [awesome-ai-agents](https://github.com/e2b-dev/awesome-ai-agents) - Broad list of AI agents and agent frameworks across every domain.
- [awesome-ai-devtools](https://github.com/jamesmurdza/awesome-ai-devtools) - AI-powered developer tools, including editors, assistants and infrastructure.
- [awesome-claude-code](https://github.com/hesreallyhim/awesome-claude-code) - Commands, hooks, skills and workflows for Claude Code.
- [awesome-cli-coding-agents](https://github.com/bradAGI/awesome-cli-coding-agents) - Directory focused on terminal-native agents and the harnesses around them.
- [awesome-copilot](https://github.com/github/awesome-copilot) - Community instructions, prompts, agents and skills for GitHub Copilot.
- [awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) - MCP servers that give agents access to tools and data.

## Contributing

Contributions are welcome. Read the [contribution guidelines](CONTRIBUTING.md) first.

---

Maintained by [Ali Hesari](https://alihesari.com). Follow on [GitHub](https://github.com/alihesari) and [X](https://x.com/alihesari) for updates.
