# NTH Agent Workforce

An autonomous recruiting organization built around specialized AI agents, human decision gates, organizational memory, dataset intelligence, and closed-loop learning.

Rather than treating recruiting as a sequence of isolated automation tasks, NTH Agent Workforce models recruiting as an organization. Agents collaborate to research candidates, evaluate evidence, rank tradeoffs, request human approval, generate outreach, learn from outcomes, and improve future behavior.

---

## Challenge

This project was built in response to the Nth AI challenge:

> Build a small organization of agents that could actually run a function inside Nth AI and perform meaningful work end-to-end.

Instead of building a single recruiting assistant, this project explores what happens when recruiting becomes an autonomous organization with:

* Specialized agents
* Human governance
* Organizational memory
* Dataset intelligence
* Policy-level learning

---

## Core Idea

Most recruiting tools optimize individual tasks.

NTH Agent Workforce models a complete recruiting organization.

```text
Dataset Intelligence
        |
        v

Research Agent
        |
        v

Evaluation Agent
        |
        v

Ranking Agent
        |
        v

Human Decision Gate
      /     \
     /       \

Approve     Reject
    |          |
    v          v

Outreach    Calibration
     \        /
      \      /

        Memory
           |
           v

      Future Runs
```

Human decisions become learning signals.

The organization adapts over time.

---

# Features

## Mission Control

Executive command center for the organization.

Provides:

* Strongest recommendation
* Organizational state
* Active datasets
* Current decisions
* Recent learning signals
* Workforce activity

The system prioritizes recommendations and evidence rather than raw scores.

---

## Candidate Intelligence

Evidence-first candidate evaluation.

Each candidate includes:

* Confidence level
* Evidence strength
* Decision state
* Strongest proof
* Role alignment
* Evaluation metadata

Scores are intentionally secondary.

The system prioritizes explainability and evidence.

---

## Candidate Dossiers

Every candidate receives a complete dossier.

Each dossier contains:

### Decision Memo

Explains:

* Recommendation
* Best evidence
* Decision logic
* Hiring action
* Risks

### Confidence Model

Includes:

* Confidence level
* Evidence quality
* Confidence factors
* Evaluation metadata

### Evidence Review

Highlights:

* Shipped projects
* Autonomous execution
* Engineering ownership
* Operational maturity

### Reasoning Trace

Candidate-specific reasoning path.

Examples:

```text
Research
→ Evaluation
→ Ranking
→ Human Agreement
→ Learning
```

or

```text
Research
→ Evaluation
→ Human Objection
→ Calibration
→ Learning
```

The reasoning path changes depending on outcomes.

### Outreach Generation

Approved candidates receive outreach drafts.

Rejected candidates do not generate outreach.

---

## Executive Decision Center

Human-in-the-loop governance layer.

Recommendations arrive with:

* Confidence
* Evidence strength
* Best proof
* Expected outcome
* Organizational impact

Available actions:

* Approve
* Reject
* Request More Evidence

Human decisions become organizational learning signals.

---

## Dataset Intelligence

Datasets are first-class organizational assets.

Supported sources:

* CSV
* XLSX
* PDF
* DOCX
* Manual entry

Datasets remain visible after ingestion.

Each dataset tracks:

* Candidate coverage
* Runs influenced
* Generated dossiers
* Approval outcomes

Example:

```text
Engineering Team Q2

43 Profiles

Generated:
43 Dossiers

Used In:
Run #8
Run #9
```

---

## Organizational Memory

The system does not store memory as candidate notes.

Instead, it stores behavioral patterns.

Example:

```text
Observed Pattern

Candidates with evaluation harnesses
outperformed candidates with prompt-only projects.

Impact:
+18 average fit score

Behavior Change:
Increase evaluation weight

Confidence:
High
```

Memory affects future runs.

---

## Self-Improvement Engine

The workforce continuously explains:

* What changed
* Why it changed
* Which signal caused it
* How future behavior will differ

Example:

```text
Human reviewers rejected
high-scoring profiles.

Observed Pattern:
Systems-depth evidence was weaker
than autonomous execution proof.

Policy Update:
Increase deployment ownership weighting.

Expected Impact:
Future confidence reduced when
production evidence is missing.
```

---

## Organizational Graph

Visual representation of the workforce.

Models:

* Research
* Evaluation
* Ranking
* Human Gate
* Outreach
* Memory
* Feedback loops

The system is intentionally designed as a closed-loop organization rather than a linear workflow.

---

# Architecture

## Agents

### Recruiting Director

Defines mission and policy.

### Research Agent

Collects evidence and candidate signals.

### Evaluation Agent

Scores tradeoffs and confidence.

### Ranking Agent

Creates recommendation slates.

### Human Decision Gate

Controls external actions.

### Outreach Agent

Generates candidate outreach.

### Memory Agent

Captures organizational learning.

### Self-Improvement Agent

Creates future behavioral updates.

---

# Human Governance

External actions never occur without approval.

Examples:

* Outreach
* Candidate progression
* High-confidence recommendations

Human decisions become:

* Positive calibration signals
* Negative calibration signals
* Organizational policies

---

# Technology

Backend

* Python
* FastAPI

Frontend

* HTML
* CSS
* JavaScript

Infrastructure

* Docker
* Docker Compose

Testing

* Pytest

---

# Running Locally

## Docker

```bash
docker compose up --build
```

Open:

```text
http://localhost:8000
```

---

## Stop

```bash
docker compose down
```

---

# Demo Data

The project ships with a built-in demo dataset for repeatable testing.

The demo dataset exists to demonstrate:

* Research
* Evaluation
* Ranking
* Human review
* Memory formation
* Self-improvement

Users can:

* Upload datasets
* Create manual candidates
* Reset demo data
* Run new workforce cycles

---

# Project Goals

This project explores a broader question:

What happens when AI systems become organizations instead of tools?

The focus is not on building another recruiting assistant.

The focus is:

* Organizational intelligence
* Human governance
* Explainable decision making
* Dataset-aware reasoning
* Organizational memory
* Continuous learning

---

# Future Improvements

* Real ATS integrations
* Email delivery workflows
* LinkedIn sourcing integrations
* Multi-run organizational analytics
* Adaptive ranking policies
* Cross-dataset memory
* Agent performance benchmarking
* Multi-organization support

---

# Author

**Mohamed Elsaka**

LinkedIn:
https://linkedin.com/in/moelsaka

GitHub:
https://github.com/moelsaka01

---

# License

MIT License
