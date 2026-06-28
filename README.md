# Hey, I’m Daniel   
**Automations @ Coinbase | Information Systems @ University of Florida**

I design and build AI-powered systems and on-chain protocols for finance,     
  procurement, and executive teams.                                             
  My work focuses on multi-agent architectures, workflow orchestration, DeFi
  protocol engineering, and intelligent automation that replaces manual
  touchpoints and friction with reliable, auditable systems.

  Most recently I have been building **always-on agentic operating systems**: 24/7
  Claude Code runtimes, governed by a tiered authority model and watchdog recovery,
  that run an organization's internal operations end to end, deployed both
  internally and as a productized, one-command client template.

📫 **danielzilper@gmail.com**

---

## Core Focus

- Always-on agent operating systems: 24/7 Claude Code runtimes under systemd, with heartbeat cadences, watchdog recovery, and context handoff for restartability
- Multi-agent systems for research, decision-making, and evaluation
- Slack-native and Google Workspace-native agent integrations, and MCP (Model Context Protocol) server development
- Finance and procurement workflow automation
- On-chain protocol design: structured products, risk-aware pricing, EIP-712 signing flows
- Internal dashboards, alerts, and reconciliation pipelines

---

## Core Skills

| Area | Skills |
|------|--------|
| Languages & Foundations | Python, TypeScript, JavaScript, SQL, Bash / Shell, HTML, CSS, Solidity |
| Agent Operating Systems & Claude Code | Claude Code (hooks, slash commands, subagents, permission matrices, MCP registration), always-on tmux + systemd runtimes, heartbeat and watchdog patterns, context handoff and restartability, tiered authority models, persona and constitution design, cadence/SOP libraries, fail-open inbox pollers, reusable one-command agent templating |
| LLM Systems & Orchestration | Multi-agent design, role isolation, adversarial evaluation, blind scoring, long-context synthesis, structured outputs, Anthropic Claude API, multi-model orchestration (Claude, OpenAI, Gemini, DeepSeek), LangGraph, MCP server development |
| Slack & Workspace Integrations | Slack app/bot development, Socket Mode, Events API, slash commands, always-on per-message dispatchers, workspace administration, Google Workspace MCP, Gmail / Calendar / Sheets / Drive automation, OAuth 2.0 credential flows, Telegram Bot API |
| Blockchain / Web3 | EVM smart contracts, Foundry, Hardhat, ethers.js, viem, wagmi, EIP-712 typed data signing, ERC-20/ERC-721/ERC-4626 standards, on-chain risk controls, wallet integration, testnet deployment workflows |
| Data & Analytics | Pandas, NumPy, SQLite, variance analysis, statistical aggregation, scoring systems, auditability |
| System & Workflow Architecture | Process Unity, Jira, NetSuite, Salesforce, Snowflake, Looker, Databricks, n8n, agent pipelines, state management, status tracking, database schema design, persistence, automation workflows |
| Full-Stack & Infrastructure | React, Next.js, Vite, Astro, Tailwind CSS, Alpine.js, GSAP, Flask, PostgreSQL, REST APIs, polling-based architectures, Docker, systemd, tmux, Linux VM operations, Tailscale, Git |

## Selected Projects

### EA / PM Agent Operating System
**Claude Code, Anthropic API, MCP, systemd, tmux, Bash, Slack API, Telegram Bot API, Google Workspace · 2026**

Designed and built an always-on executive-assistant / project-manager agent operating system: a 24/7 Claude Code runtime that runs an organization's internal operations and business rhythms end to end, and doubles as the working proof of a productized agent-OS offering that installs enterprise structure (cadences, reviews, briefs, research, governance) into a business.

- Engineered a resilient runtime on a dedicated Linux VM: systemd-driven heartbeat, watchdog health checks with self-recovery, and automatic context handoff so a fresh session resumes cleanly with no dropped obligations
- Built a **tiered authority model** (autonomous / draft-for-approval / human-only) enforced through a Claude Code permission matrix, gating external communications and self-edits behind human review
- Authored an operating constitution and reasoning-framework library plus a uniform cadence/SOP library mapped to scheduled timers
- Operates a file-based task tracker (backlog → ready → in progress → blocked → done) with auto-generated board, blocker, and handoff views across a multi-venture portfolio, routing each item to the correct human or agent owner
- Generates a daily executive digest spanning multiple Google Workspace inboxes and calendars with triaged top actions, delivered over Telegram; maintains an always-open listening window and fail-open inbox poller for real-time inbound
- Wired **Slack and email as first-class channels** via an always-on per-message dispatcher and a dedicated Google Workspace MCP credential path
- Productized the entire spine into a reusable **client template** with a one-command installer that stamps agent identity, company, and config across the repo and provisions its runtime services

**Impact:** A single agent reliably holding the operational rhythm of a multi-venture enterprise, turned into a repeatable, deploy-ready product so each client or venture gets its own always-on operating agent from the same proven runtime.

---

### UF Blockchain Club Agent Operating System
**Claude Code, MCP, Discord API, Google Workspace, social + event platform APIs · 2026**

Designed a multi-MCP operations agent that runs a university blockchain club's recurring operations, so officers set direction and the agent executes the week-to-week.

- Architected a multi-service integration spanning Discord community management, Google Workspace (calendar, email, docs, forms), multi-platform social scheduling, event platforms (Lu.ma / Eventbrite), email marketing, and design automation, all through MCP servers
- Governed by a **tiered approval model** that keeps research, drafting, and internal docs autonomous while gating every external communication, social publish, and expenditure behind human review
- Designed a credential and security model where all tokens flow through MCP configuration and the agent never stores or requests secrets directly
- Authored weekly and semester cadence playbooks (meetings, events, recruitment, hackathon coordination, treasury tracking) on a dispatch model that routes club tasks through a central PM/router agent into a shared task tracker

**Impact:** A repeatable operating agent for a student organization that compresses meeting prep, event logistics, community management, and outreach into a governed, low-cost automation pipeline.

---

### U.S. Government Agent Simulation
**Python, multi-agent LLM · 2026**

Agent-based LLM simulation of the United States federal government, modeling branches, agencies, and actors as interacting agents to explore policy dynamics and emergent institutional behavior.

- Composed many role-isolated LLM agents into a structured institutional model
- Built scenario orchestration and state tracking across simulated actors and decision flows
- Focused on interpretability of multi-agent dynamics and emergent outcomes

---

### Website & Brand Engineering
**Astro, Tailwind CSS, Alpine.js, GSAP, TypeScript · 2025-2026**

Designed and shipped multiple production marketing and brand sites across the venture portfolio.

- **setupaitech.com** and additional brand sites on Astro + Tailwind CSS, with Alpine.js interactivity and GSAP motion
- Personal and venture sites (Daniel Zilper, Laytus Labs, UF Gator Blockchain Club) built for performance, clarity, and fast iteration
- Component-driven layouts, content modeling, and deploy workflows for non-technical handoff

---

### Laytus Protocol (ETHDenver 2026)
**Python Solidity, Python, FastAPI, React, TypeScript, Docker, PostgreSQL, Redis · Feb 2026**

Built and documented a correlation-aware on-chain structured products / combo pricing protocol with a full-stack architecture spanning smart contracts, backend microservices, and frontend execution flows.

- Designed a **risk-aware pricing pipeline** combining multi-layer correlation detection with **Gaussian copula** joint probability modeling and dynamic vig logic
- Implemented and integrated **EIP-712 signed certificates** bridging off-chain pricing to on-chain execution
- Engineered Solidity contract system with vault + escrow custody model, fee controller, position NFTs, and admin guardian controls
- Enforced **10 on-chain risk checks** (caps, solvency, concentration, replay protection, signature validity, expiry) to protect LP capital
- Built and mapped backend service architecture (gateway, quote, correlation, settlement, execution, risk monitor, worker layer) with Dockerized local infra
- Produced an extensive technical documentation suite and whitepaper covering architecture, math, contract logic, deployment state, and migration planning

**Impact:** Delivered a transparent, auditable protocol design that reduces correlated exposure risk through mathematically grounded pricing and contract-level guardrails.

---

### Monad VWAP Execution Engine 
**TypeScript, Solidity, Next.js, ethers.js, Hardhat · Feb 2026**

Built a full-stack algorithmic trading execution system on Monad Testnet that demonstrates parallel EVM throughput using VWAP-style order slicing and automated off-chain execution.

- Designed and implemented `VWAPDemo.sol` for on-chain order creation, time-based slice execution, and O(1) execution tracking via bitmasking
- Built keeper and flow bots (TypeScript + ethers.js) to automate slice execution and simulate realistic market activity
- Developed a real-time Next.js + wagmi frontend for creating VWAP orders, monitoring execution progress, and visualizing live order state
- Applied production-grade contract patterns (ReentrancyGuard, SafeERC20, CEI ordering, custom errors, event-driven architecture)
- Optimized contract storage and execution flow for high-frequency parallelizable order processing on Monad’s low-latency testnet
- Structured documentation and demo workflows for deployment, setup, and judge-ready walkthroughs

**Impact:** Showcased how parallel EVM execution can support multi-order algorithmic trading with higher throughput and lower expected slippage versus sequential execution models.

---

### AI-Native Hedge Fund Research System  
**Python · Jan 2026**

Multi-agent investment research platform built using LangGraph to orchestrate a structured, multi-stage pipeline for generating, evaluating, and adjudicating investment theses.

- Strict role isolation to prevent narrative lock-in  
- Adversarial evaluation using agents with opposing assumptions  
- Blind scoring across evidence quality, assumption clarity, logical coherence, falsifiability, and uncertainty handling  
- Cross-agent aggregation designed to preserve high-conviction minority signals  
- Automated decision gates producing **PROCEED / HOLD / REJECT** outcomes  
- Full persistence to SQLite for auditability and post-analysis  

Different LLMs are used for generation, evaluation, and arbitration roles, including Claude for long-context reasoning, OpenAI models for high-throughput synthesis, and cross-checking via Gemini and DeepSeek.

---

### Agent Monitoring Dashboard  
**React, JavaScript · Dec 2026**

Real-time monitoring dashboard for observing multi-agent research workflows.

- Displays live execution status across pipeline stages  
- Visualizes running, completed, idle, and error states  
- Integrates with backend API to track parallel agent execution  
- Designed to identify bottlenecks and coordination failures during runs  

---

### Finance & Procurement Automation Systems  
**Python, Google Apps Script, n8n · 2025–2026**

Suite of internal automation systems built for finance and procurement operations.

- Due diligence questionnaire follow-up and tracking automation, data ETL to Snowflake + Looker, googlesheet appscript cleans data and pulls latest email thread for open assessments, with status or draft email response ready for review  
- Vendor Risk Management KRIs dynamic dashboard, filtering by inherent risk, mission criticality, legal entity, latest sssessment, business continuity plan, and third party supplier use.  
- Vendor Spend reconciliation appscript with smart column mapping, trim, fuzzy-matching, helpers and filtering, tied to dynamic category spend metrics dashboards for operational and executive visibility  
- Netsuite, ZIP, Process Unity, and Jira reconciliation and reporting pipelines for recurring finance processes  
- Slack, Gmail, Google Sheets, and Calendar integrations to eliminate manual follow-ups  

---

### Executive Assistant & Personal Operating System  
**n8n, LLMs · 2025**

AI-powered executive assistant designed as a persistent personal operating system.

- Maintains goals, task lists, and calendar state  
- Sends daily task summaries and contextual reminders via Telegram  
- Accepts natural language responses to reprioritize tasks dynamically  
- Adjusts schedules and reminders based on real-time user feedback  

---

### Open Aura  
**TypeScript, Next.js · 2025-Present**

Minimalist resource platform for founders, students, and builders.

- Built with Next.js and React  
- Curated collections with filtering and search  
- Community contribution workflows  
- Focused on clarity, simplicity, and high-signal resources
