# AgenticHypothesis 🤖️

## Overview
This repository consolidates methodologies, case studies, and tools developed for hypothesis generation using Large Language Models (LLMs). The included content spans various domains, including biomedical research, chemistry, social sciences, and computational biology, illustrating the transformative potential of LLMs in augmenting scientific discovery.

## Objectives
- Leverage LLMs for generating novel and testable scientific hypotheses.
- Explore interdisciplinary applications of AI in automating and accelerating research processes.
- Identify challenges and propose future directions for the integration of LLMs in hypothesis-driven studies.

## Methodologies
The repository includes a diverse set of methodologies, frameworks, and tools employed across the reviewed papers:

### 1. Temporal Knowledge Graphs (TKGs)
- **Approach**: Contrasting multi-source temporal knowledge graphs to capture the dynamic evolution of relationships in biomedical datasets.
- **Example**: Temporal Contrastive Learning (TCL) framework for generating high-quality hypotheses by modeling co-evolution across datasets like PubMed and CTD.

### 2. Transformer-Based Models
- **AGATHA Framework**:
  - Utilizes transformer models for biomedical literature mining.
  - Validates hypotheses using temporal holdout datasets.
- **HYVIN Framework**:
  - Combines hypothesis, verification, and induction stages for skill learning in LLM-based agents.

### 3. Graph-Based and Multi-Agent Frameworks
- **MOOSE-CHEM**:
  - A multi-agent system for rediscovering unseen chemistry hypotheses through inspiration-based recombination and ranking mechanisms.

### 4. Statistical and Meta-Analytical Approaches
- **Meta-Analysis Automation**:
  - Utilizing decomposed zero-shot prompting for data extraction.
  - Formulating and solving optimization problems for hypothesis validation.

### 5. Domain-Specific Fine-Tuning
- **FitRepair Framework**:
  - Explores the plastic surgery hypothesis in automated program repair (APR).
  - Employs domain-specific fine-tuning strategies like knowledge-intensive and repair-oriented approaches.

## Applications
The repository covers applications of hypothesis generation in several domains:

### Biomedical Research
- **Temporal Evolution Analysis**: Identifying latent associations in biomedical data using graph-based methods.
- **Gene-Disease Studies**: Linking chemical, gene, and disease data for new discoveries.

### Materials Science
- **Perovskite Solar Cells**:
  - ChatGPT-generated hypotheses suggested novel surface modifiers like polyallylamine.
  - Experimental validation confirmed efficiency improvements.

### Social Sciences
- **Hypothesis Evidencing**:
  - Evaluating LLMs' ability to discern evidence supporting or refuting scientific hypotheses.
  - Developed datasets for benchmarking evidencing capabilities.

### Chemistry
- **Rediscovering Hypotheses**:
  - MOOSE-CHEM framework recreated hypotheses in high-impact publications.
  - Inspired methodologies to address research questions using multi-source inspirations.

## Challenges and Opportunities
### Challenges
- **Bias and Validity**:
  - Addressing biases inherent in LLMs' training datasets.
  - Ensuring hypotheses generated are novel, valid, and actionable.
- **Computational Costs**:
  - High resource demands for fine-tuning and large-scale evaluations.

### Opportunities
- **Interdisciplinary Research**:
  - Integrating LLMs into cross-domain studies to foster innovation.
- **Automation of Research Workflows**:
  - Streamlining data synthesis, hypothesis formulation, and experiment planning.

## Repository Structure
```
├── data/
│   ├── biomedical/       # Datasets for biomedical studies
│   ├── chemistry/        # Datasets and benchmarks for chemistry
│   ├── social_sciences/  # Social science evidencing datasets
│
├── models/
│   ├── pretrained/       # Pretrained LLMs used in studies
│   ├── fine_tuned/       # Domain-specific fine-tuned models
│
├── tools/
│   ├── graph_frameworks/ # Temporal knowledge graph implementations
│   ├── hypothesis_tools/ # Tools for hypothesis generation
│
└── README.md             # Documentation and overview
```

## Contributors
We acknowledge the contributions of researchers and teams across various institutions. Detailed author credits are provided in each included study.

## References
A full list of cited papers and resources is available in the repository under `references/`. Key studies include:
- Temporal knowledge graph frameworks for hypothesis generation [Zhou et al., 2024][116].
- AGATHA and transformer-based methodologies for biomedical literature mining [Sybrandt et al., 2020][95].
- HYVIN: Self-driven grounding frameworks for skill learning [Peng et al., 2024][110].
- Applications of ChatGPT in materials science and solar cell optimization [Chen et al., 2024][114].

For more details, see the provided documentation and study-specific folders.

- [MLE-agent](https://github.com/MLSysOps/MLE-agent) - Your intelligent companion for seamless AI engineering and research. 🔍 Integrate with arxiv and paper with code to provide better code/research plans 🧰 OpenAI, Anthropic, Ollama, etc supported. 🎆 Code RAG ![GitHub Repo stars](https://img.shields.io/github/stars/MLSysOps/MLE-agent?style=social)
