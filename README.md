# Awesome-AI-Agent-Platform

## Top AI Agent Platform Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Multi-Agent Orchestration, Agent Builders, Visual Workflows, Coding Agents & Production Agent Runtimes*  
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Agent Platforms**. These systems help teams design, run, and monitor autonomous or semi-autonomous agents—multi-agent crews, visual workflow builders, coding agents, and hosted runtimes for production agentic applications.

**Examples** include CrewAI Cloud, AutoGen Studio, Flowise Cloud, Dify, Botpress, LangGraph Platform, Lindy AI, AgentOps, SuperAGI, and OpenHands Cloud (the category leaders).

**Open-source emphasis**: This category is exceptionally strong in open source. **CrewAI**, **LangGraph**, **AutoGen**, **Dify**, **Flowise**, **OpenHands**, **SuperAGI**, and related frameworks are MIT/Apache-licensed and power most production agent systems. This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[CrewAI Cloud](https://www.crewai.com/)**  
  Hosted platform for multi-agent crews built on the open CrewAI framework—role-based agents, task orchestration, and production deployment.

- **[LangGraph Platform](https://www.langchain.com/langgraph)**  
  Managed runtime and tooling for LangGraph agents—stateful, long-running workflows with durable execution and observability.

- **[Dify Cloud](https://dify.ai/)**  
  Hosted version of the open Dify platform for building agentic workflows, RAG apps, and production AI applications with a visual canvas.

- **[Flowise Cloud](https://flowiseai.com/)**  
  Hosted visual LangChain/agent builder—drag-and-drop flows for LLM chains and agents with easy API deployment.

- **[AutoGen Studio / Microsoft Agent offerings](https://microsoft.github.io/autogen/)**  
  UI and cloud-adjacent experiences for AutoGen-style multi-agent conversations (AutoGen open source remains the core).

- **[OpenHands Cloud](https://www.all-hands.dev/)**  
  Hosted runtime for OpenHands coding agents that plan, edit, and ship software changes across repositories.

- **[Lindy AI, Botpress, AgentOps, SuperAGI Cloud](https://www.lindy.ai/)**  
  Platforms spanning no-code agent coworkers, conversational agent builders, agent observability, and autonomous agent orchestration.

- **[Other commercial AI agent platforms](https://www.crewai.com/)**  
  Additional hosted agent builders, computer-use agents, and enterprise agent control planes.

## Open-Source GitHub Projects

- **[CrewAI](https://github.com/crewAIInc/crewAI)**  
  Leading open-source multi-agent framework—role-playing agents, sequential/hierarchical processes, and tools; MIT-licensed foundation for many production crews.

- **[LangGraph](https://github.com/langchain-ai/langgraph)**  
  Low-level open framework for stateful, cyclic agent graphs with explicit control over execution, memory, and human-in-the-loop—highest adoption for production agents.

- **[AutoGen (Microsoft)](https://github.com/microsoft/autogen)**  
  Open multi-agent conversation framework—agents that chat, use tools, and collaborate; widely used for research and applications (successor directions in Microsoft Agent Framework).

- **[Dify](https://github.com/langgenius/dify)**  
  Open-source platform for agentic workflows, RAG, and AI apps—visual canvas, knowledge bases, and production-ready backend (self-host or cloud).

- **[Flowise](https://github.com/FlowiseAI/Flowise)**  
  Open visual builder for LangChain agents and flows—node-based UI, self-hosted, and API export for rapid prototyping.

- **[OpenHands](https://github.com/All-Hands-AI/OpenHands)**  
  Open platform for software engineering agents—plan, code, and execute changes across codebases; self-hostable with strong community adoption.

- **[SuperAGI](https://github.com/TransformerOptimus/SuperAGI)**  
  Open autonomous agent framework with GUI, toolkits, and agent provisioning for goal-driven workflows.

- **[Langflow, Botpress (open), Mastra & visual builders](https://github.com/langflow-ai/langflow)**  
  Additional open visual and code-based platforms for composing agents, tools, and workflows as APIs or MCP servers.

### Additional Strong Open-Source Options

- **Multi-agent orchestration**: CrewAI (roles) and LangGraph (graphs) as the two dominant paradigms.
- **Visual builders**: Dify and Flowise for low-code agent and RAG apps.
- **Coding agents**: OpenHands and SWE-agent for repository-level software tasks.
- **Observability**: Open tracing/eval tools (LangSmith alternatives, AgentOps-style open metrics) paired with any framework.
- **Composable stacks**: LangGraph/CrewAI + tools/MCP + vector store + guardrails for production agents.
- Commercial clouds still lead in managed scale, team workspaces, and zero-ops deployment.

**Frameworks for building custom systems**:  
**LangGraph**, **CrewAI**, **AutoGen**, **Dify**, and **Flowise** are the primary open agent platforms.  
**OpenHands** leads for coding agents.  
Commercial offerings (CrewAI Cloud, LangGraph Platform, Dify Cloud, OpenHands Cloud, Lindy, etc.) provide hosted runtimes and enterprise features on top of these ecosystems.  
Most serious agent teams develop on open frameworks and optionally deploy to vendor clouds. Fully open stacks are production-ready with your own model and infrastructure choices.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Autonomous agents can take unintended actions (code changes, API calls, data access). Use least-privilege tools, sandboxes, human approval for high-impact steps, and comprehensive logging.
- Open-source frameworks offer full control but require you to secure keys, tools, and runtime. Commercial platforms shift operational burden and often add governance features. Validate safety and cost before production use.

---

**Made for AI engineers, agent builders, and teams shipping autonomous workflows.**  
Let's keep AI agent platforms open and powerful—through CrewAI, LangGraph, Dify, OpenHands, and complementary commercial runtimes.
