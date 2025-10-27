# CHESS: A Multi-Agent GraphRAG Framework for Chinese Essay Scoring

This repository accompanies our paper:

> **CHESS: A Multi-Agent GraphRAG Framework for Chinese Essay Scoring**  
> Submitted to *Proceedings of the VLDB Endowment (PVLDB) 2026* as a Regular Research Paper.

---

## 🧠 Abstract

Automated essay scoring (AES) aims to evaluate the quality of student essays in a manner consistent with human raters.  
Existing AES systems are often monolithic and opaque, offering only a single holistic score without interpretable trait-level feedback.  

We propose **CHESS**, a **multi-agent, graph-structured essay evaluation framework** that decomposes the scoring process into four specialized agents—**Grammar**, **Vocabulary**, **Structure**, and **Content**—coordinated by a lightweight orchestrator.  
Each agent leverages **rubric-aligned prompting** on a large language model (DeepSeek v3) and integrates graph-structured contextual retrieval via **GraphRAG**, enabling fine-grained, interpretable evaluation consistent with Chinese writing rubrics (e.g., *Qi–Cheng–Zhuan–He*).  

Experiments on the **HSK-enhanced Chinese essay dataset** demonstrate that CHESS achieves human-level agreement (QWK≈0.82) and significantly improves out-of-distribution robustness compared with state-of-the-art baselines such as Rank-Then-Score and prompt-only LLMs.  
The framework establishes a transparent, reproducible, and extensible paradigm for **AI-driven educational assessment** and interpretable text evaluation.

---

## 📁 Repository Overview

This repository will contain:
- **Implementation code** for CHESS, including:
  - Multi-agent orchestration scripts  
  - GraphRAG configuration files (`settings.yaml`)  
  - Prompt templates for each trait agent
- **Evaluation utilities** for trait-level and holistic scoring metrics (QWK, PCC, MAE)
- **Sample data** and preprocessing scripts for the HSK-enhanced dataset
- **Documentation** for reproducing main experiments and ablation studies

---

## 🔒 Code and Data Availability

Due to copyright and privacy restrictions associated with the **HSK-enhanced Chinese essay dataset**,  
the full dataset cannot be released publicly at this stage.  

👉 **All code, processed data samples, and evaluation scripts will be made publicly available upon paper acceptance**  
through a permanent GitHub/Zenodo repository to ensure reproducibility and transparency.

---

