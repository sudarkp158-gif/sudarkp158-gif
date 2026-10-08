## Hi there 👋 I am Sudarsan

### Cross-Functional TPM | SAAS | AI / ML / LLM | Cloud | Data | Software Delivery | IT / Cyber Security | ERP / CRM

Seasoned Technical Program Manager (TPM) with experience in leading large-scale, cross-functional engineering and digital transformation initiatives. I specialize in bridging the gap between complex technical architecture, managing dependencies and risks and strategic business execution. With a strong foundational background in software development and system architecture, I excel at driving high-impact technology programs from concept to successful global implementation.

Below is a collection of my recent repositories focusing on AI-driven workflows, AI agents, modern technical architectures and deployments, system integrations and smart automation tools for real world scenarios.

---

## 🤖 1. AI + Technical Program Management


**[AI TPM Risk Agent](https://github.com/sudarkp158-gif/ai-tpm-risk-agent)**

An AI-assisted program management workflow that analyzes project updates and generates:

- Program health assessment
- Top risks and impacts
- Mitigation actions
- Dependencies
- Issues requiring attention
- Recommended actions
- Executive summary

**Technologies:** Python · OpenAI API · LLMs

The project is intentionally designed around a **human-in-the-loop AI TPM workflow**, rather than simply using an LLM as a chatbot.

---

## 🔄 2. Modern Software Delivery

**[Deployment Using CI/CD Pipeline](https://github.com/sudarkp158-gif/Deployment-using-CI-CD-Pipeline)**

# Deployment using CI/CD Pipeline

A hands-on demonstration of a modern CI/CD pipeline for deploying a containerized Python application from source code to a cloud environment.

This project demonstrates practical understanding of software delivery, automation, containerization, cloud deployment, testing, secrets management, and production runtime concepts.

---

## Project Objective

Build and demonstrate an end-to-end software delivery pipeline where a code change automatically moves through:

```text
Developer
   ↓
GitHub Repository
   ↓
GitHub Actions
   ↓
Automated Tests
   ↓
Docker Build
   ↓
GitHub Container Registry
   ↓
Render Deployment
   ↓
Gunicorn
   ↓
Flask Application
   ↓
Health Check

```
## ⚙️ 3. Ai-program-alignment-agent

**[AI Program Alignment Agent](https://github.com/sudarkp158-gif/Ai-program-alignment-agent)**

This Ai Agent showcases AI-powered Technical Program Management that aligns cross-functional organizations around a common North Star Metric and evaluates competing program resolutions using the RICE prioritization framework.

# High Level Architecture

```text
                  User Input
                      │
                      ▼
              ┌───────────────┐
              │ LLM Analysis  │
              └───────┬───────┘
                      │
          ┌───────────┴───────────┐
          │                       │
          ▼                       ▼
    Metric Analysis         Resolution Analysis
          │                       │
          ▼                       ▼
  Candidate Metrics          RICE Inputs
          │                       │
          ▼                       ▼
     AI Reasoning          Python Calculation
          │                       │
          └───────────┬───────────┘
                      ▼
              ┌───────────────┐
              │ Final Report  │
              └───────────────┘
```

# 🤖 4. AI Program Dependency & Risk Prediction Agent

**[AI Program Dependency & Risk Prediction Agent](https://github.com/sudarkp158-gif/Ai-program-dependency-risk-agent)**

## Objective
I started building an AI-powered program dependency and risk assessment workflow
because dependency management is one of the highest manual-toil areas for a TPM
managing complex programs. The workflow first calculates objective signals such
as ETA variance, downstream impact and critical-path exposure using deterministic
Python logic. An AI layer then interprets those signals to explain risk,
potential impact and recommended actions. I intentionally separated deterministic
calculations from probabilistic AI so the LLM is not responsible for date
arithmetic or business-rule calculations. The TPM validates the AI output and
owns the decision. The next stage is predictive risk using historical ETA
slippage, dependency age and downstream impact to identify emerging risks.

## Design principle
**AI predicts/explains; deterministic code calculates.**

Python calculates ETA variance, downstream impact and deterministic risk signals.
AI interprets those signals and can generate risk explanations, impact analysis,
recommended actions and escalation recommendations.
The TPM validates the AI output and owns the decision.

## Run
```bash
python app.py
pytest
```

## Architecture

Step 1 - Deterministic risk
Step 2 - Emerging-risk scoring
Step 3 - AI-powered TPM recommendation

Python calculates ETA variance, downstream impact and deterministic risk signals.
AI interprets those signals and can generate risk explanations, impact analysis,
recommended actions and escalation recommendations.
The TPM validates the AI output and owns the decision.

Deterministic facts → AI reasoning → Human decision

```
Dependency Data
      ↓
Deterministic Analysis
      ↓
Current Risk
      ↓
Emerging Risk
      ↓
AI Reasoning
      ↓
TPM Action
Dependency Data
      ↓
Deterministic Analysis
      ↓
Current Risk
      ↓
Emerging Risk
      ↓
AI Reasoning
      ↓
TPM Action
```


**Working on the below:**
## 🔄 AI Agent for Project Analysis and Planning
## 🔄 AI workflow to create a live dashboard based on the jira / confluence updates
## 🔄 AI agent for Cloud Cost Optimization that identifies the idle/stale Cloud Resources
## 🔄 AI agent for System Design, BoilerPlate templates and Automation

