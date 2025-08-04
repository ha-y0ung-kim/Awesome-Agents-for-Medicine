# 🤖 Awesome Agents for Medicine
<div align="center">

![Awesome](https://awesome.re/badge.svg) [![commit](https://img.shields.io/github/last-commit/LijunRio/Awesome-Agents-for-Medicine?color=blue)](https://github.com/LijunRio/Awesome-Agents-for-Medicine/commits/main) [![PR](https://img.shields.io/badge/PRs-Welcome-red)](https://github.com/LijunRio/Awesome-Agents-for-Medicine/pulls)

</div>

A comprehensive repository of state-of-the-art AI agents and autonomous systems tailored for medical applications. This collection encompasses cutting-edge research papers, advanced tools, and valuable resources, aiming to foster innovation and interdisciplinary collaboration in the field of AI-driven medicine.

## 🩺 Paper lists for AI Agents for Medicine


| Paper | Datasets | Base Models | Key Insights |
|-------|----------|-------------|--------------|
| [The Virtual Lab of AI agents designs new SARS‑CoV‑2 nanobodies](https://www.nature.com/articles/s41586-025-09442-9) <br> _Nature (2025, published July 29th)_ | SARS‑CoV‑2 spike protein variants experimental binding data + computational protein modeling | GPT‑4o (LLM PI & scientist agents) + ESM protein language model, AlphaFold‑Multimer, Rosetta | <details><summary>View Insights</summary>- “Virtual Lab” multi‑agent framework: LLM PI orchestrates specialized scientist agents with specialist domain roles + critic agent <br> - Constructs a computational pipeline integrating ESM → AlphaFold‑Multimer → Rosetta to design 92 novel nanobody candidates <br> - Experimental validation: a subset shows strong binding to recent COVID‑19 variants (e.g. JN.1, KP.3) while retaining ancestral spike binding <br> - Only ~1% human intervention; enables rapid, interdisciplinary scientific discovery with transparent agent reasoning and reproducibility </details> |
| [MDAgents: An Adaptive Collaboration of LLMs for Medical Decision-Making](https://arxiv.org/pdf/2404.15155) <br> _NeurIPS 2024 Oral_ | MedQA, PubMedQA, DDXPlus, SymCat, JAMA, MedBullets, Path-VQA, PMC-VQA, MIMIC-CXR, MedVidQA | GPT-4, Claude, PaLM 2, Med-PaLM 2 | <details><summary>View Insights</summary>- Adaptive multi-agent collaboration  <br> - First autonomous diagnostic system across specialties  <br> - Moderator + RAG boosts average accuracy by **11.8%**  <br> - Achieved **95%+** accuracy on complex medical tasks </details> |
| [MedRAX: Medical Reasoning Agent for Chest X-ray](https://arxiv.org/pdf/2502.02673) <br> _ICML 2025 (PMLR 267)_ | ChestAgentBench (2,500 expert-level CXR queries) | GPT-4, LLaVA-Med, CheXagent, MedSAM | <details><summary>View Insights</summary>- Unified agent framework for chest X-ray interpretation <br> - Combines multiple specialized CXR tools dynamically <br> - Outperforms general-purpose & proprietary models <br> - No extra training required; maintains transparency & accuracy </details> |
| [Multi-Agent Reasoning for Cardiovascular Imaging Phenotype Analysis](https://arxiv.org/pdf/2507.03460) <br> _MICCAI 2025_ | UK Biobank (26,893 training + 38,309 test; cardiac MRI + multimodal phenotypes) | GPT-4o, GPT-3.5 | <details><summary>View Insights</summary>- Proposes MESHAgents: multi-agent LLM framework for phenotype-factor analysis <br> - Specialized agents (cardiac, mechanics, clinical, statistics) collaborate via memory, evidence tools, and sequential consensus <br> - Outperforms single-agent GPT-4o and other multi-agent baselines (MedAgents, RareAgents) in phenotype coverage & reasoning depth <br> - Auto-selected phenotypes match or exceed expert performance in diagnostic tasks (AUC, recall) </details> |
| [An Agentic System for Rare Disease Diagnosis with Traceable Reasoning](https://arxiv.org/pdf/2506.20430) <br> _Preprint (arXiv 2506.20430)_ | Not specified | Not specified | <details><summary>View Insights</summary>- Proposes an agentic system for diagnosing rare diseases with traceable reasoning <br> - Focuses on enhancing transparency and reproducibility in medical AI systems <br> - Demonstrates potential for improving diagnostic accuracy in rare disease cases </details> |
| [MAGDA: Multi-agent guideline-driven diagnostic assistance](https://arxiv.org/pdf/2409.06351) <br> _Preprint (arXiv 2409.06351)_ | CheXpert, ChestX-ray14 | Mixtral 8x7B Instruct, GPT-4, Llama 2 70B Chat, CLIP (BioVil-T version) | <details><summary>View Insights</summary>- Introduces MAGDA: multi-agent LLM system guided by clinical guidelines for zero-shot medical image diagnosis <br> - Combines CLIP (BioVil-T) with three agents for image screening, reasoning, and refinement <br> - Beats CheXzero and Xplainer on CheXpert and ChestX-ray14 Longtail, especially for rare diseases <br> - Uses Mixtral 8x7B Instruct as backbone; shows solid performance vs. GPT-4 and Llama 2 with lower resource cost </details> |
| [Development and validation of an autonomous artificial intelligence agent for clinical decision-making in oncology](https://www.nature.com/articles/s43018-025-00991-6) <br> _Nature Cancer June 2025_ | 20 realistic multimodal patient cases |  |






## 🛠️ Tools and Frameworks
- **[LangChain](https://github.com/hwchase17/langchain)** - A framework for building applications powered by large language models (LLMs). It provides tools for chaining LLMs with other components, such as memory, tools, and agents, to create complex workflows.


## 🤝 Contributing



## 📄 License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.