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
| **Languages & Foundations** | Python, TypeScript, JavaScript, SQL, HTML, CSS                                                           |
| **LLM Systems & Orchestration** | Multi-agent design, role isolation, adversarial evaluation, blind scoring, long-context synthesis, structured outputs |
| **Data & Analytics**      | Pandas, NumPy, SQLite, variance analysis, statistical aggregation, scoring systems, auditability          |
| **System & Workflow Architecture** | Process Unity, Jira, NetSuite, Salesforce, Snowflake, Looker, Databricks, n8n, agent pipelines, state management, status tracking, database schema design, persistence, automation workflows |
| **Full-Stack & Infrastructure** | React, Next.js, Vite, Flask, PostgreSQL, REST APIs, polling-based architectures, Docker, Git         |

---

## Selected Projects

### AI-Native Hedge Fund Research System  
**Python · Feb 2026**

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
**React, JavaScript · Feb 2026**

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
