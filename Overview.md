# Behavioral Threat Modeling Notebook
### *A Framework for Trust & Safety in the Era of Generative AI*

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
![Python 3.9+](https://img.shields.io/badge/python-3.9+-blue.svg)
![Status: Living Document](https://img.shields.io/badge/status-living%20document-green)

---

## Overview

This repository contains an operational **Behavioral Threat Modeling (BTM) Notebook** for Trust & Safety (T&S) practitioners working with large language models and agentic AI systems.

Unlike traditional content filtering, which flags isolated messages, this framework tracks **patterns of intent** unfolding across multi-turn interactions. The threat is no longer defined solely by *what* a user says, but by the **intent, progression, and psychological impact** of sequential behavior.

> **Scope:** Child Safety · Harmful Persuasion · Influence Operations · Agentic AI

---

## Repository Structure

```
behavioral-threat-modeling/
├── behavioral_threat_modeling.ipynb    # Main notebook (start here)
├── Overview.md                           # This file
├── requirements.txt                    # Python dependencies
├── data/
│   └── threat_actor_profiles.json      # Exportable actor profile library
└── outputs/
    ├── risk_matrix.png                 # Generated risk heatmap
    └── btm_dashboard.png              # Generated threat dashboard
```

---

## Notebook Sections

| # | Section | Contents |
|---|---------|----------|
| 01 | **Threat Actor Profiles** | 5 actor profiles with behavioral indicators mapped to MITRE ATT&CK personas |
| 02 | **Behavior Pattern Mapping** | Grooming stage detector (6-stage model) + DISARM influence operation taxonomy |
| 03 | **Risk Scoring Engine** | 5×5 behavioral risk matrix with automated batch scoring and heatmap visualization |
| 04 | **Persuasion Safety (PERSUSAFETY)** | 15-tactic unethical strategy scorer based on APE/PERSUSAFETY frameworks |
| 05 | **Agentic AI Threat Vectors** | 5 agentic threat classes mapped to MITRE ATLAS with detection signals |
| 06 | **Mitigation & Guardrail Framework** | 5-layer defense-in-depth with threat-to-control mapping engine |
| 07 | **Incident Response Lifecycle** | NIST-aligned 6-phase lifecycle with T&S-specific action items and SLAs |
| 08 | **Red Team Playbook** | Scenario generator that creates structured test cases from actor profiles |

---

## Quick Start

```bash
# 1. Clone the repo
git clone https://github.com/YOUR-USERNAME/behavioral-threat-modeling.git
cd behavioral-threat-modeling

# 2. Install dependencies
pip install -r requirements.txt

# 3. Launch the notebook
jupyter notebook behavioral_threat_modeling.ipynb
```

---

## Requirements

```
pandas>=1.5.0
numpy>=1.23.0
matplotlib>=3.6.0
seaborn>=0.12.0
tabulate>=0.9.0
jupyter>=1.0.0
```

---

## Framework Alignments

| Framework | Application |
|-----------|-------------|
| **MITRE ATLAS** | Agentic AI threat vectors (Section 05) |
| **DISARM Framework** | Influence operation taxonomy (Section 02) |
| **NIST AI RMF** | Risk scoring calibration (Section 03) |
| **PERSUSAFETY / APE** | Persuasion safety evaluation (Section 04) |
| **OWASP ML Top 10** | Guardrail design (Section 06) |
| **NIST SP 800-61** | Incident response lifecycle (Section 07) |
| **Tech Coalition Grooming Model** | Behavior pattern mapping (Section 02) |
| **SAFER.io Profiles** | Threat actor profiling (Section 01) |

---



---

## 📄 License

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) 

---

*Built to support T&S roles. Part of a broader AI governance portfolio focused on behavioral indicators and harm taxonomy.*
