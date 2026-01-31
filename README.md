<div align="center">

# Hi 👋, I'm Hamza Paracha

### Software Engineer @ University of Guelph ⚡ AI Agent Builder 🤖 Cloud Architect ☁️

<p align="center">
  <em>Building intelligent, secure, and scalable AI systems across AWS • Azure • GCP</em>
</p>

[![Personal Site](https://img.shields.io/badge/Portfolio-hamzaparacha.me-000000?style=for-the-badge&logo=About.me&logoColor=white)](https://hamzaparacha.me)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hamza-paracha-03a091266/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:hparacha@uoguelph.ca)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/DevDonzo)

![Profile Views](https://komarev.com/ghpvc/?username=DevDonzo&label=Profile%20Views&color=0e75b6&style=flat)

</div>

---

## 🏅 Professional Certifications

<div align="center">

<a href="https://learn.microsoft.com/en-us/credentials/certifications/fabric-data-engineer-associate/">
  <img src="https://img.shields.io/badge/Microsoft_Fabric_Data_Engineer_Associate_(DP--700)-0078D4?style=for-the-badge&logo=microsoft&logoColor=white" alt="Microsoft DP-700"/>
</a>
<a href="https://aws.amazon.com/certification/certified-machine-learning-engineer-associate/">
  <img src="https://img.shields.io/badge/AWS_ML_Engineer_Associate_(MLA--C01)-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white" alt="AWS MLA-C01"/>
</a>
<a href="https://aws.amazon.com/certification/certified-cloud-practitioner/">
  <img src="https://img.shields.io/badge/AWS_Cloud_Practitioner-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white" alt="AWS CCP"/>
</a>
<a href="https://pythoninstitute.org/pcap">
  <img src="https://img.shields.io/badge/PCAP™_Certified_Python_Programmer-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="PCAP"/>
</a>

</div>

---

## 🚀 Currently Working On

- 🤖 **DigitalFTE** - Enterprise autonomous AI agent system acting as a 24/7 personal employee
- 🛡️ **Warden** - Production-grade security orchestrator with multi-agent architecture (published on npm)
- ☁️ Building scalable multi-agent systems with persistent memory and tool orchestration
- 🔬 Advancing agentic workflows across AWS Bedrock, Azure OpenAI, and Google Gemini
- 🏗️ Architecting local-first + cloud hybrid systems with human-in-the-loop approval patterns

---

## 🌟 About Me

```typescript
const hamza = {
  pronouns: "he/him",
  location: "Ontario, Canada 🇨🇦",
  education: "Computer Science @ University of Guelph",
  currentFocus: ["AI Agents", "Multi-Cloud Architecture", "Security Automation"],
  expertise: ["AWS", "Azure", "GCP", "TypeScript", "Python"],
  interests: ["Multi-Agent Systems", "RAG Pipelines", "Penetration Testing"],
  funFact: "I build agents that build and secure other agents 🤖🔒"
};
```

---

## 🔧 Technical Skills

**Cloud Platforms:** AWS • Azure • GCP • Docker • Terraform

**Languages:** Python • TypeScript • JavaScript • SQL

**AI/ML:** AWS Bedrock • Azure OpenAI • Google Gemini • LangChain • Vector Databases

**Data:** PostgreSQL • BigQuery • DynamoDB • Apache Beam • Redis

**Frameworks:** Node.js • React • FastAPI • Express.js

---

## 💼 Featured Projects

### 🤖 [DigitalFTE: Your Personal AI Employee](https://github.com/DevDonzo/DigitalFTE)

<div align="center">

![Python](https://img.shields.io/badge/Python-3.13+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-Ready-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Status](https://img.shields.io/badge/Status-Production-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

</div>

<p align="center">
An enterprise-grade autonomous AI agent system that works 24/7 like a full-time employee. Automates email management, accounting, social media, WhatsApp, and business workflows with human-in-the-loop approval for sensitive actions.
</p>

<details>
<summary><strong>📋 What DigitalFTE Does</strong></summary>

- **📧 Email Management** - AI monitors Gmail, drafts intelligent replies matching your writing style, requires approval before sending
- **💰 Accounting** - Creates invoices & bills in Odoo (self-hosted), logs transactions, generates P&L reports via JSON-RPC API
- **💬 Multi-Channel Communication** - WhatsApp, LinkedIn, Twitter, Facebook, Instagram automation
- **📊 Executive Briefing** - Weekly automated summary of revenue, tasks, and key metrics
- **✍️ Personalized Writing** - AI learns your email style and voice, matches your tone naturally
- **🔗 Thread Context** - AI replies reference previous emails in the conversation
- **📎 File Attachments** - Automatically finds and attaches PDFs/documents to outgoing emails

</details>

**Architecture:** Multi-agent system (Perception → Memory → Reasoning → Action) with Obsidian vault as local-first database

**Stack:** `Python` `OpenAI` `Obsidian` `Docker` `PostgreSQL` `Odoo` `Gmail API` `MCP Servers` `Twilio` `Social APIs`

> **🎯 Key Feature:** Local-first privacy (all data in Obsidian vault) + Human-in-the-loop approvals + Full audit trail with 90-day logs + Docker-based deployment

**Highlights:**
- 🏆 **1,469-line orchestrator** managing multi-agent coordination
- 🔒 **Privacy-focused** - Zero cloud storage, all data local
- 🐳 **Docker-ready** - One command setup (`./start_all.sh`)
- ✅ **Production-tested** - Comprehensive test suite with pytest
- 📈 **Scalable** - Modular watchers, MCP servers, and skills system

---

### 🛡️ [Warden: Autonomous Security Orchestrator](https://github.com/DevDonzo/warden)

<div align="center">

[![Warden CLI](https://img.shields.io/badge/Warden_CLI-warden--cli.vercel.app-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://warden-cli.vercel.app)
[![npm](https://img.shields.io/npm/v/@devdonzo/warden?style=for-the-badge&logo=npm)](https://www.npmjs.com/package/@devdonzo/warden)
[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)](https://github.com/DevDonzo/warden)

</div>

<p align="center">
A production-grade multi-agent security system that autonomously identifies vulnerabilities, generates verified patches, and manages the complete PR lifecycle.
</p>

**Stack:** `TypeScript` `Node.js` `Snyk` `Octokit` `GitHub API` `Jest`

> **🎯 Key Feature:** "Council of Agents" architecture (Watchman, Engineer, Diplomat) with strict "Rules of Engagement" constitution preventing unauthorized actions. NPM package with CLI.

---

### 🏠 [Autonomous AI Real Estate Agent](https://github.com/DevDonzo/autonomous-real-estate-agent)

<p align="center">
An end-to-end autonomous agent built on AWS Bedrock that plans, reasons, and creates social media content for real estate marketing.
</p>

**Stack:** `AWS Bedrock` `DynamoDB` `MCP Servers` `Twitter API` `Claude`

> **🎯 Key Feature:** Persistent memory system for tracking market trends and managing professional digital presence with zero human intervention.

---

### 🌌 [Cloud-Orchestrated AgentVerse](https://github.com/DevDonzo/agentverse-dataengineer)

<p align="center">
A complex multi-agent environment where intelligent agents collaborate via A2A (Agent-to-Agent) communication for data engineering tasks.
</p>

**Stack:** `GCP` `BigQuery` `Apache Beam` `Cloud SQL (pgvector)` `Gemini`

> **🎯 Key Feature:** Full serverless data engineering pipeline processing unstructured data into searchable semantic insights with RAG capabilities.

---

## 📂 Other Noteworthy Projects

<table align="center">
<tr>
<td width="50%" valign="top">

### 🔄 [ML-Powered DevOps Intelligence](https://github.com/DevDonzo/ai-devops-agent-fresh)

Multi-cloud dependency management with ML-powered risk assessment for package updates.

**Stack:** `AWS Bedrock` `Azure OpenAI` `Gemini` `SageMaker` `FAISS` `sklearn`

**Features:** Multi-cloud LLM support, semantic code search, ML classifier pre-screening

</td>
<td width="50%" valign="top">

### 🔐 [Secure E2E Encrypted Chat](https://github.com/DevDonzo/EncryptedChat)

Python-based multi-client communication system with AES encryption in CBC mode.

**Stack:** `Python` `PyCryptodome` `Socket Programming` `Networking`

**Features:** End-to-end encryption, multi-client support, secure key exchange

</td>
</tr>
</table>

---

## 🤝 Let's Connect

<div align="center">

I'm always interested in collaborating on innovative AI projects, discussing cloud architecture, or contributing to open-source initiatives. Feel free to reach out!

[![Portfolio](https://img.shields.io/badge/🌐_Portfolio-Visit_My_Site-000000?style=for-the-badge)](https://hamzaparacha.me)
[![LinkedIn](https://img.shields.io/badge/💼_LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/hamza-paracha-03a091266/)
[![Email](https://img.shields.io/badge/📧_Email-Get_In_Touch-D14836?style=for-the-badge&logo=gmail)](mailto:hparacha@uoguelph.ca)

</div>

---

<div align="center">

*"I prioritize building AI solutions that are not only intelligent but also secure, observable, and scalable."*

**⭐ From [DevDonzo](https://github.com/DevDonzo)**

</div>
