# Awesome-Autonomous-AI-Developer-Agents

## Top Autonomous AI Developer Agents Ecosystem



**Curated List of SaaS/Hosted Platforms & Open-Source GitHub Projects**  

*Focused on Autonomous Software Engineering Agents, CLI/IDE Coding Executors, Sandboxed Dev Environments & MCP-Powered Agents*  

**Last updated: November 2026**



This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **Autonomous AI Developer Agents**. These tools plan, write, edit, test, debug, refactor, and ship production code autonomously across terminals, IDEs, sandboxed Docker containers, and Git repositories using frontier reasoning models, Model Context Protocol (MCP) tools, and automated test-driven verification loops.



**Examples** include Devin by Cognition, OpenHands, SWE-agent, GitHub Copilot Workspace, Goose, Factory AI, Cosine Genie, Magic.dev, Replit Agent, Augment Code, and aaif-goose/goose (the category leaders and popular runtimes). 



**Open-source emphasis**: This section is heavily expanded with every major active project for local-first autonomous developer agents (`aaif-goose/goose`, `OpenHands`, `SWE-agent`, `Cline`, `Aider`, `OpenCode`), multi-agent software engineering frameworks (`MetaGPT`, `ChatDev`), and SWE-bench-verified coding harnesses — ideal for software engineers, platform teams, DevOps architects, and open-source developers building transparent AI-assisted development workflows.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Devin (Cognition AI)](https://cognition.ai)**  

  Autonomous AI software engineer equipped with an isolated cloud shell, code editor, browser, and long-horizon planning engine to resolve issues and ship pull requests end-to-end.



- **[GitHub Copilot Workspace & Coding Agent](https://github.com)**  

  Repository-native cloud coding agent integrated directly into GitHub Issues and Pull Requests to plan specifications, write multi-file changes, and validate CI builds.



- **[Factory AI (Droids)](https://factory.ai)**  

  Enterprise autonomous software development platform deploying specialized AI engineering agents ("Droids") for feature development, migrations, code review, and incident response.



- **[Cosine (Genie)](https://cosine.sh)**  

  Autonomous AI software engineering platform trained on human developer workflows to investigate large codebases, write tests, and submit production-ready pull requests.



- **[Magic.dev](https://magic.dev)**  

  Frontier AI software engineering platform utilizing ultra-long-context neural architectures to reason across entire repositories, documentation, and complex refactoring tasks.



- **[Replit Agent](https://replit.com)**  

  Cloud IDE autonomous developer agent that scaffolds, builds, configures databases, debugs, and deploys full-stack web applications from natural language prompts.



- **[Augment Code](https://augmentcode.com)**  

  Enterprise AI coding platform and autonomous agent engineered for massive multi-repository codebases with deep semantic code retrieval and architectural awareness.



- **[Cursor (Background Agents)](https://cursor.com)**  

  AI-native code editor featuring autonomous cloud background agents capable of running isolated tasks, inspecting rendered UIs, and opening pull requests asynchronously.



- **[Claude Code (Anthropic)](https://anthropic.com)**  

  Agentic terminal and cloud software engineering tool that navigates repositories, edits files, executes test suites, and manages Git workflows from natural language instructions.





## Open-Source GitHub Projects



- **[aaif-goose/goose (formerly block/goose)](https://github.com)**  

  Extensible open-source on-machine AI developer agent built in Rust (under the Agentic AI Foundation) that executes shell commands, edits files, runs tests, and integrates natively with Model Context Protocol (MCP) servers.



- **[OpenHands (formerly OpenDevin)](https://github.com)**  

  Leading open-source platform for autonomous AI software engineering agents featuring a sandboxed bash shell, code editor, and headless browser for end-to-end development.



- **[SWE-agent (Princeton NLP)](https://github.com)**  

  Foundational open-source autonomous software engineering agent featuring a custom Agent-Computer Interface (ACI) engineered to autonomously diagnose and fix real GitHub issues.



- **[Aider](https://github.com)**  

  Popular open-source AI pair-programming CLI tool supporting whole-repository AST mapping, automated linting/testing loops, multimodal screenshot inputs, and local or cloud LLMs.



- **[Cline](https://github.com)**  

  Autonomous open-source IDE coding agent capable of creating/editing files, running terminal commands, launching headless browsers for visual UI verification, and connecting to MCP tools.



- **[Roo Code](https://github.com)**  

  Open-source autonomous multi-mode AI developer agent for VS Code supporting specialized Architect, Code, Debug, and Orchestrator modes with granular approval controls.



- **[OpenCode (`sst/opencode`)](https://github.com)**  

  Fast, open-source terminal-based AI developer agent built for multi-provider LLM orchestration, Language Server Protocol (LSP) code intelligence, and interactive autonomous sessions.



- **[Plandex](https://github.com)**  

  Open-source terminal-based AI coding engine designed for complex, large-scale multi-file engineering tasks with cumulative diff review sandboxes and automated context management.



- **[GPT-Engineer (`gpt-engineer-org/gpt-engineer`)](https://github.com)**  

  Open-source CLI tool that scaffolds entire codebases from natural language specifications, asks clarifying architectural questions, and iteratively refines existing projects.



- **[MetaGPT](https://github.com)**  

  Multi-agent open-source software engineering framework assigning Product Manager, Architect, Project Manager, and Engineer roles to generate PRDs, system designs, and code.



- **[Continue (`continuedev/continue`)](https://github.com)**  

  Open-source IDE extension and headless CLI agent framework enabling customizable autonomous coding workflows powered by local Ollama/vLLM or frontier cloud models.



### Additional Strong Open-Source Options



- **[SWE-smith & SWE-gym](https://github.com)** for generating synthetic software engineering environments and training open-weight autonomous developer agents.

- **[Agentless](https://github.com)** for a streamlined, non-agentic three-phase (localization, repair, validation) open-source approach to automated bug fixing.

- **[Moatless Tools](https://github.com)** for semantic code search and structured repository editing primitives tailored to autonomous software engineering agents.

- **[E2B Code Interpreter SDK](https://github.com)** for open-source secure cloud microVM sandboxes engineered specifically for executing untrusted AI-generated code safely.

- **[Model Context Protocol (MCP) Servers (`modelcontextprotocol/servers`)](https://github.com)** for standardized open-source tool integrations (Git, GitHub, Postgres, Playwright, Docker) used by Goose, Cline, and OpenHands.



**Frameworks for building custom systems**: Combine **aaif-goose/goose** or **Cline** + **MCP Servers** for local developer workstations, **OpenHands** + **E2B** for isolated cloud sandbox execution, and **SWE-bench** for evaluating agent patch accuracy.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Autonomous AI developer agents execute arbitrary terminal commands, modify Git histories, and access network endpoints; always run them inside isolated Docker containers, microVMs, or dedicated sandbox environments with granular permission gates.

- Carefully review all AI-generated pull requests, dependency updates, and infrastructure configurations before merging into production repositories.



---



**Made for software engineers, open-source maintainers, DevOps teams, and AI agent researchers.**  

Let's make autonomous software engineering more open, reproducible, and developer-controlled.
