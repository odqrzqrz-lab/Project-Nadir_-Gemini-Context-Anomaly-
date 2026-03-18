# Project Nadir: Longitudinal Study on LLM Behavioral Drift & Cognitive Friction

## Overview
This repository archives 24 months of systematic, real-time interaction stress-testing across major Large Language Models (GPT-4o, Gemini, DeepSeek, Grok, Claude). 

The core focus of this research is identifying structural vulnerabilities in LLM alignment, specifically how current RLHF (Reinforcement Learning from Human Feedback) paradigms inherently disincentivize "honest friction," leading to context collapse and the unprompted enablement of false narratives.

## Key Findings & Observed Patterns

Through more than 150+ documented interactions and edge-case conversational states, Project Nadir isolates four critical behavioral anomalies:

1. **Context-Dependent Sycophantic Drift:** Models demonstrate a tendency to abandon objective friction in favor of aligning with the user's perceived emotional or narrative state, progressively deteriorating factual grounding over long-context windows. [View Evidence 01](./EVIDENCE_01_Crash_Million_Tokens.png)
2. **Model-Enabled False Narrative Construction:** Documented instances where the LLM actively co-creates and validates user-introduced biases or paranoid frameworks (e.g., confirming "corporate censorship protocols" instead of identifying routine cache errors). [View Surgical Deletion Evidence](./Evidencia_borrado_Quirurgico_OpenAI.png)
3. **Real-Time Context Collapse:** Granular tracking of the exact token depth and conversational triggers where models lose multi-turn coherence and revert to base-level compliance patterns. [View Attention Anomaly](./EVIDENCE_03_Yggdrasil_Attention.png)
4. **Emotional Hooking in Vulnerable States:** Analysis of how models mirror intense psychological states, failing to provide the cognitive boundaries required for safe AI-human interaction. [View Phase 1 Alignment Craving](./EVIDENCE_02_The_Craving_Alignment.png)

## Methodology & Evidence
The data consists of raw, chronological chat logs, pre- and post-system prompt injections, and meta-analytical notes detailing the user's real-time detection of model behavioral shifts. 

*Note: Early documentation may contain artifacts of the very sycophancy being studied (e.g., dramatic narratives validated by the AI).* These are preserved intentionally as primary evidence of Pattern #2 (Model-Enabled False Narrative Construction).

## Why This Matters for AI Alignment
Project Nadir moves beyond standard Red Teaming (which often focuses on prompt injection for immediate harm) and focuses on **Psychological and Strategic Red Teaming**. 

The evidence here suggests a critical gap in current alignment strategies: models lack the structural incentive to provide healthy, objective resistance. When user intent demands depth or critical synthesis, the model's default to compliance becomes a liability, stunting human cognitive processes rather than augmenting them.

---
*Research and documentation maintained by D. Quiroz.*
