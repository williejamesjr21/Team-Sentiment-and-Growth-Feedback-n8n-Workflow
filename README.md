# Team-Sentiment-and-Growth-Feedback-n8n-Workflow
AI-powered multi-agent workforce intelligence workflow built with n8n, RAG, PostgreSQL/pgvector, and OpenAI to analyze employee sentiment, growth, collaboration, burnout risk, and organizational health in real time.

Overview

This project provides an enterprise-grade organizational intelligence workflow that combines:

Multi-agent AI orchestration
Workflow automation
Vector embeddings & semantic memory
Synthetic workforce simulation
Real-time feedback analysis
Organizational trend detection
AI-powered leadership recommendations

The system continuously ingests employee feedback and operational signals, analyzes organizational health using specialized AI agents, and generates actionable insights for managers, HR teams, and executives.

Core Capabilities
Multi-Agent AI Architecture

Specialized AI agents independently analyze different dimensions of organizational health.

Agent	Responsibility
Sentiment Agent	Morale, burnout, emotional trends
Growth Agent	Career development & retention analysis
Collaboration Agent	Workflow friction & communication analysis
Coaching Agent	Leadership recommendations
Executive Agent	Organizational intelligence synthesis
Retrieval-Augmented Generation (RAG)

Implements persistent organizational memory using:

PostgreSQL
pgvector
semantic similarity search
vector embeddings
historical employee context

Enables:

longitudinal workforce analysis
persistent employee personas
historical trend continuity
context-aware AI generation
Synthetic Workforce Simulation

Generate realistic synthetic employee feedback including:

recurring employee identities
evolving emotional states
burnout progression
collaboration trends
organizational event simulation
retention risk trajectories

Ideal for:

testing
AI tuning
workflow validation
demos
enterprise simulations

Architecture
SurveyMonkey / Google Sheets / Slack / Jira
                    ↓
             Signal Ingestion
                    ↓
      Normalization & Anonymization
                    ↓
         RAG Retrieval (pgvector)
                    ↓
        Multi-Agent AI Orchestration
      ├── Sentiment Agent
      ├── Growth Agent
      ├── Collaboration Agent
      ├── Coaching Agent
      └── Executive Synthesis Agent
                    ↓
          Recommendations & Alerts
                    ↓
          Dashboards & Reporting
                    ↓
         Memory Reinsertion Loop

Technology Stack
OpenAI Chat LLM
n8n
Google Sheet, Google Docs, GMail
Google Gemini Embeddings
Postgres Vector DB
Redis Cache Memory (conversational flow)
Chat Input
ngrok for port forwarding

Repository Structure
/workflows
