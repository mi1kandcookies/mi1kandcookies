# Hey, I’m Daniel   
**Automations @ Coinbase | Information Systems @ University of Florida**

I design and build AI-powered systems for finance, procurement, and executive teams.  
My work focuses on multi-agent architectures, workflow orchestration, and intelligent automation that replaces manual touchpoints and friction with reliable, auditable systems.

📫 **danielzilper@gmail.com**

---

## Core Focus

- Multi-agent systems for research, decision-making, and evaluation  
- Finance and procurement workflow automation  
- Internal dashboards, alerts, and reconciliation pipelines  

---

## Core Skills

| Area                       | Skills                                                                                                    |
|---------------------------|------------------------------------------------------------------------------------------------------------|
| **Languages & Foundations** | Python, TypeScript, JavaScript, SQL, HTML, CSS, Solidity                                                           |
| **LLM Systems & Orchestration** | Multi-agent design, role isolation, adversarial evaluation, blind scoring, long-context synthesis, structured outputs |
| **Data & Analytics**      | Pandas, NumPy, SQLite, variance analysis, statistical aggregation, scoring systems, auditability          |
| **System & Workflow Architecture** | Process Unity, Jira, NetSuite, Salesforce, Snowflake, Looker, Databricks, n8n, agent pipelines, state management, status tracking, database schema design, persistence, automation workflows |
| **Full-Stack & Infrastructure** | React, Next.js, Vite, Flask, PostgreSQL, REST APIs, polling-based architectures, Docker, Git         |

---

## Selected Projects

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
