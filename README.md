# GENAI_Support
# Agentic AI Support Assistant – POC Presentation

---

## Slide 1: Title Slide

**Agentic AI-Powered Support Assistant**  
**POC Demo & Evolution**  
Presented to: Product Implementation Team  
Date: [Add Date]  
Presented by: [Your Name]

---

## Slide 2: Why This Matters

- Support engineers spend hours analyzing logs, configs, and release docs.
- Manual RCA is slow, error-prone, and inconsistent.
- Our goal: Automate and accelerate RCA using AI — intelligently and version-aware.

---

## Slide 3: Key Objectives

1. Handle multiple versions/releases of the same product
2. Enable version-specific RCA
3. Build an agent that evolves from static QA → semi-agentic → autonomous

---

## Slide 4: Problem Statement

**Pain Points:**
- Time-consuming log analysis
- Human error in RCA
- Difficulty comparing across releases

---

## Slide 5: How Version-aware RCA Works

- Document Ingestion with version metadata:
  - Product: HPE TAS
  - Version: v22.3 / v22.4 / v23.0
- Vector DB (e.g., Qdrant) stores embeddings with metadata
- Query-time filtering for precision

---

## Slide 6: Architecture Overview

[Insert version-aware RCA architecture diagram]  
**Components:**
- Upload & tagging
- Vector search with version filter
- RCA agent reasoning engine

---

## Slide 7: Demo Workflow

1. Upload logs tagged with version
2. Ask a question
3. Filter search by version or compare across
4. RCA agent identifies config or log issues
5. Suggests likely root cause

---

## Slide 8: Evolution of the Agent

### Stage 1: Basic Retrieval
- Query + vector search

### Stage 2: Semi-Agentic
- Adds RCA prediction, config diffing

### Stage 3: Autonomous Agent
- Multi-step reasoning
- Suggests RCA

---

## Slide 9: Future State – Multi-Agent Ecosystem

- Log Analyzer Agent
- Config Diff Agent
- KB Search Agent
- Planner Agent (central reasoning)

---

## Slide 10: Live Demo (Streamlit)

- Walkthrough of upload + version-aware RCA
- 3 Stages in action
- Agentic reasoning with causal trace

---

## Slide 11: Summary

- Version-aware RCA is real, working, and extensible
- Evolving agent improves MTTD and MTTR
- Future-ready for alerts, auto-triage, integrations

---

## Slide 12: Q&A

**Thank you!**  
Let's open up for questions and feedback.
