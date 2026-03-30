# 📘 POLARIS — Evaluation Materials & Agent Prompts

## 🔷 Overview

This repository contains the **evaluation materials and prompts** used in the study:
> **POLARIS: Towards Pedagogically-Aware Large Language Models for Smart Learning in Hybrid Settings**

The goal of this repository is to support **transparency and reproducibility** by providing access to the materials used to evaluate the three LLM-based agents proposed in the POLARIS framework:
- **Learning Design Agent**
- **Analyse Agent**
- **React Agent**

The materials correspond to an empirical evaluation conducted through **two iterative rounds with educators across two instructional contexts**.

---

## 🔷 Repository Contents

### 📁 `evaluation_forms/`

Contains the questionnaires used during the evaluation.
- **Round 1**
  - Learning Design Agent 
  - Analyse & React Agents

- **Round 2**
  - Learning Design Agent
  - Analyse & React Agents

All questionnaires use a **six-point Likert scale**:
- **1 = Strongly Disagree**  
- **6 = Strongly Agree**


### 📁 `interview_questions/`

Contains the semi-structured interview questions used in both rounds.

- **14 questions per round**
- Cover:
  - Learning Design (**KCs, alignment, mapping**)
  - Learner modelling (**SOLO interpretation**)
  - Reactions (**usefulness, feasibility**)

These questions are aligned with the three research questions (**RQ1–RQ3**) defined in the paper.

---

### 📁 `agent_prompts/`

Contains the prompts used to configure and guide the three agents:
- `learning_design_agent_prompt.txt`
- `analyse_agent_prompt.txt`
- `react_agent_prompt.txt`

These prompts define:
- Expected inputs  
- Structured outputs (e.g., **KCs, SOLO classifications, reactions**)  
- Constraints aligned with **pedagogical intentions**
