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










Open-source Large Language Model (LLM) driven autonomous agent that can automatically solve various tasks.

![https://arxiv.org/abs/2309.07864](./images/LLM-based-Agents.png)

- [AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) - AutoGPT is the vision of the power of AI accessible to everyone, to use and to build on. ![GitHub Repo stars](https://img.shields.io/github/stars/Significant-Gravitas/AutoGPT?style=social)
- [gpt-engineer](https://github.com/gpt-engineer-org/gpt-engineer) - Specify what you want it to build, the AI asks for clarification, and then builds it. ![GitHub Repo stars](https://img.shields.io/github/stars/gpt-engineer-org/gpt-engineer?style=social)
- [gpt-researcher](https://github.com/assafelovic/gpt-researcher) - GPT based autonomous agent that does online comprehensive research on any given topic ![GitHub Repo stars](https://img.shields.io/github/stars/assafelovic/gpt-researcher?style=social)
- [JARVIS](https://github.com/microsoft/JARVIS) - a system to connect LLMs with ML community. ![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/JARVIS?style=social)
- [babyagi](https://github.com/yoheinakajima/babyagi) - An example of an AI-powered task management system. ![GitHub Repo stars](https://img.shields.io/github/stars/yoheinakajima/babyagi?style=social)
- [AgentGPT](https://github.com/reworkd/AgentGPT) - 🤖 Assemble, configure, and deploy autonomous AI Agents in your browser. ![GitHub Repo stars](https://img.shields.io/github/stars/reworkd/AgentGPT?style=social)
- [OpenDevin](https://github.com/OpenDevin/OpenDevin) - a platform for autonomous software engineers, powered by AI and LLMs.  ![GitHub Repo stars](https://img.shields.io/github/stars/OpenDevin/OpenDevin?style=social)
- [XAgent](https://github.com/OpenBMB/XAgent) - An Autonomous LLM Agent for Complex Task Solving ![GitHub Repo stars](https://img.shields.io/github/stars/OpenBMB/XAgent?style=social)
- [ShortGPT](https://github.com/RayVentura/ShortGPT) - 🚀🎬Experimental AI framework for automated short/video content creation. ![GitHub Repo stars](https://img.shields.io/github/stars/RayVentura/ShortGPT?style=social)
- [KwaiAgents](https://github.com/KwaiKEG/KwaiAgents) - A generalized information-seeking agent system with Large Language Models (LLMs). ![GitHub Repo stars](https://img.shields.io/github/stars/KwaiKEG/KwaiAgents?style=social)
- [ProAgent](https://github.com/OpenBMB/ProAgent) - An LLM-based Agent for the New Automation Paradigm - Agentic Process Automation ![GitHub Repo stars](https://img.shields.io/github/stars/OpenBMB/ProAgent?style=social)
- [Agent-E](https://github.com/EmergenceAI/Agent-E) - Agent-E is an agent based system that aims to automate actions on the user's computer. At the moment it focuses on automation within the browser. The system is based on on AutoGen agent framework. ![GitHub Repo stars](https://img.shields.io/github/stars/EmergenceAI/Agent-E?style=social)
- [Wordware](https://www.wordware.ai) - A web-hosted IDE where non-technical domain experts work with AI Engineers to build task-specific AI agents. It approaches prompting as a new programming language rather than low/no-code blocks.
- [GenAgent](https://github.com/xxyQwQ/GenAgent) - Build Collaborative AI Systems with Automated Workflow Generation - Case Studies on ComfyUI ![GitHub Repo stars](https://img.shields.io/github/stars/xxyQwQ/GenAgent?style=social)
- [MLE-agent](https://github.com/MLSysOps/MLE-agent) - Your intelligent companion for seamless AI engineering and research. 🔍 Integrate with arxiv and paper with code to provide better code/research plans 🧰 OpenAI, Anthropic, Ollama, etc supported. 🎆 Code RAG ![GitHub Repo stars](https://img.shields.io/github/stars/MLSysOps/MLE-agent?style=social)

### Multi-Agent Task Solver Projects

Open-source Large Language Model (LLM) driven Multi-Agent that can automatically solve various tasks.

![](./images/multi-agent.png)

- [MetaGPT](https://github.com/geekan/MetaGPT) - 🌟 The Multi-Agent Framework: Given one line Requirement, return PRD, Design, Tasks, Repo ![GitHub Repo stars](https://img.shields.io/github/stars/geekan/MetaGPT?style=social)
- [ChatDev](https://github.com/OpenBMB/ChatDev) - Create Customized Software using Natural Language Idea (through LLM-powered Multi-Agent Collaboration) ![GitHub Repo stars](https://img.shields.io/github/stars/OpenBMB/ChatDev?style=social)
- [DevOpsGPT](https://github.com/kuafuai/DevOpsGPT) - Multi agent system for AI-driven software development. ![GitHub Repo stars](https://img.shields.io/github/stars/kuafuai/DevOpsGPT?style=social)

### Agent Society Simulation

Exploring endless possibilities with open-source agent social simulation.

![https://arxiv.org/abs/2309.07864](./images/agent-society.png)

- [generative_agents](https://github.com/joonspk-research/generative_agents) - Interactive Simulacra of Human Behavior ![GitHub Repo stars](https://img.shields.io/github/stars/joonspk-research/generative_agents?style=social)
- [camel](https://github.com/camel-ai/camel) - 🐫 Communicative Agents for “Mind” Exploration of Large Language Model Society (NeruIPS'2023) ![GitHub Repo stars](https://img.shields.io/github/stars/camel-ai/camel?style=social)
- [ai-town](https://github.com/a16z-infra/ai-town) - deployable starter kit for building and customizing your own version of AI town - a virtual town where AI characters live, chat and socialize. ![GitHub Repo stars](https://img.shields.io/github/stars/a16z-infra/ai-town?style=social)
- [GPTTeam](https://github.com/101dotxyz/GPTeam) - The main objective of this project is to explore the potential of GPT models in enhancing multi-agent productivity and effective communication. ![GitHub Repo stars](https://img.shields.io/github/stars/101dotxyz/GPTeam?style=social)
- [ChatArena](https://github.com/Farama-Foundation/chatarena) - ChatArena is a library that provides multi-agent language game environments and facilitates research about autonomous LLM agents and their social interactions. ![GitHub Repo stars](https://img.shields.io/github/stars/Farama-Foundation/chatarena?style=social)
- [Camel-AutoGPT](https://github.com/SamurAIGPT/Camel-AutoGPT) - Watch two agents 🤝 collaborate and solve tasks together, unlocking endless possibilities in #ConversationalAI, 🎮 gaming, 📚 education, and more! 🔥 ![GitHub Repo stars](https://img.shields.io/github/stars/SamurAIGPT/Camel-AutoGPT?style=social)

### Advanced Components
- [mem0](https://github.com/mem0ai/mem0) - Mem0 provides a smart, self-improving memory layer for Large Language Models, enabling personalized AI experiences across applications. ![GitHub Repo stars](https://img.shields.io/github/stars/mem0ai/mem0?style=social)
- [composio](https://github.com/ComposioHQ/composio) - Composio equips agents with well-crafted tools empowering them to tackle complex tasks ![GitHub Repo stars](https://img.shields.io/github/stars/ComposioHQ/composio?style=social)

## Frameworks

Quickly build and customize agents.

![https://arxiv.org/abs/2308.08155](images/autogen_agentchat.png)

- [langchain](https://github.com/langchain-ai/langchain) - ⚡ Building applications with LLMs through composability ⚡ ![GitHub Repo stars](https://img.shields.io/github/stars/langchain-ai/langchain?style=social)
    - [awesome-langchain](https://github.com/kyrolabs/awesome-langchain) - 😎 Awesome list of tools and projects with the awesome LangChain framework ![GitHub Repo stars](https://img.shields.io/github/stars/kyrolabs/awesome-langchain?style=social)
- [llama_index](https://github.com/run-llama/llama_index) - LlamaIndex (formerly GPT Index) is a data framework for your LLM applications ![GitHub Repo stars](https://img.shields.io/github/stars/run-llama/llama_index?style=social)
- [crewaAI](https://github.com/joaomdmoura/crewAI) - Framework for orchestrating role-playing, autonomous AI agents. By fostering collaborative intelligence, CrewAI empowers agents to work together seamlessly, tackling complex tasks. ![GitHub Repo stars](https://img.shields.io/github/stars/joaomdmoura/crewAI?style=social)
- [agents](https://github.com/aiwaves-cn/agents) - An Open-source Framework for Autonomous Language Agents ![GitHub Repo stars](https://img.shields.io/github/stars/aiwaves-cn/agents?style=social)
- [AutoGen](https://github.com/microsoft/autogen) - AutoGen is a framework that enables the development of LLM applications using multiple agents that can converse with each other to solve tasks. ![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/autogen?style=social)
- [TaskWeaver](https://github.com/microsoft/TaskWeaver) - A code-first agent framework for seamlessly planning and executing data analytics tasks. ![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/TaskWeaver?style=social)
- [AgentVerse](https://github.com/OpenBMB/AgentVerse) - AgentVerse is designed to facilitate the deployment of multiple LLM-based agents in various applications. AgentVerse primarily provides two frameworks: task-solving and simulation. ![GitHub Repo stars](https://img.shields.io/github/stars/OpenBMB/AgentVerse?style=social)
- [SuperAGI](https://github.com/TransformerOptimus/SuperAGI) - A dev-first open source autonomous AI agent framework. Enabling developers to build, manage & run useful autonomous agents quickly and reliably. ![GitHub Repo stars](https://img.shields.io/github/stars/TransformerOptimus/SuperAGI?style=social)
- [AutoChain](https://github.com/Forethought-Technologies/AutoChain) - Build lightweight, extensible, and testable LLM Agents ![GitHub Repo stars](https://img.shields.io/github/stars/Forethought-Technologies/AutoChain?style=social)
- [modelscope-agent](https://github.com/modelscope/modelscope-agent) - An agent framework connecting models in ModelScope with the world ![GitHub Repo stars](https://img.shields.io/github/stars/modelscope/modelscope-agent?style=social)
- [AppAgent](https://github.com/mnotgod96/AppAgent) - A novel LLM-based multimodal agent framework designed to operate smartphone applications. ![GitHub Repo stars](https://img.shields.io/github/stars/mnotgod96/AppAgent?style=social)
- [superagent](https://github.com/homanp/superagent) - 🥷 The open framework for building AI Assistants ![GitHub Repo stars](https://img.shields.io/github/stars/homanp/superagent?style=social)
- [Voice Lab](https://github.com/saharmor/voice-lab) - A comprehensive testing and evaluation framework for voice agents across language models, prompts, and agent personas. ![GitHub Repo stars](https://img.shields.io/github/stars/saharmor/voice-lab?style=social)
- [AgentSquare](https://github.com/tsinghua-fib-lab/AgentSquare) - Automatic LLM Agent Search In Modular Design Space ![GitHub Repo stars](https://img.shields.io/github/stars/tsinghua-fib-lab/AgentSquare?style=social)

## Benchmark/Evaluator

Benchmarks to evaluate LLM-as-Agent across a variety of environments.

- [AgentBench](https://github.com/THUDM/AgentBench) - A Comprehensive Benchmark to Evaluate LLMs as Agents ![GitHub Repo stars](https://img.shields.io/github/stars/THUDM/AgentBench?style=social)
- [agentops](https://github.com/AgentOps-AI/agentops) - Python SDK for agent monitoring, LLM cost tracking, benchmarking, and more. Integrates with most LLMs and agent frameworks like CrewAI, Langchain, and Autogen ![GitHub Repo stars](https://img.shields.io/github/stars/AgentOps-AI/agentops?style=social)
- [langtrace](https://github.com/Scale3-Labs/langtrace) - Langtrace 🔍 is an open-source, Open Telemetry based end-to-end observability tool for LLM applications, providing real-time tracing, evaluations and metrics for popular LLMs, LLM frameworks, vectorDBs and more.. Integrate using Typescript, Python. ![GitHub Repo stars](https://img.shields.io/github/stars/Scale3-Labs/langtrace?style=social)
- [ToolBench](https://github.com/OpenBMB/ToolBench) - An open platform for training, serving, and evaluating large language model for tool learning. ![GitHub Repo stars](https://img.shields.io/github/stars/OpenBMB/ToolBench?style=social)
- [LLM-Agent-Benchmark-List](https://github.com/zhangxjohn/LLM-Agent-Benchmark-List) - A benchmark list for evaluation of large language models.
- [agbenchmark](https://pypi.org/project/agbenchmark/) - by AutoGPT


## Platforms/API

Able to connect LLM with the real world.

![](./images/system_design.png)

- [OpenAgents](https://github.com/xlang-ai/OpenAgents) - An Open Platform for Language Agents in the Wild ![GitHub Repo stars](https://img.shields.io/github/stars/xlang-ai/OpenAgents?style=social)
- [OpenAGI](https://github.com/agiresearch/OpenAGI) - "May the Force be with LLM and Domain Experts." ![GitHub Repo stars](https://img.shields.io/github/stars/agiresearch/OpenAGI?style=social)
- [RestGPT](https://github.com/Yifan-Song793/RestGPT) - An LLM-based autonomous agent controlling real-world applications via RESTful APIs ![GitHub Repo stars](https://img.shields.io/github/stars/Yifan-Song793/RestGPT?style=social)
- [AGiXT](https://github.com/Josh-XT/AGiXT) - AGiXT is a dynamic AI Agent Automation Platform that seamlessly orchestrates instruction management and complex task execution across diverse AI providers. ![GitHub Repo stars](https://img.shields.io/github/stars/Josh-XT/AGiXT?style=social)
- [agentlego](https://github.com/InternLM/agentlego) - Enhance LLM agents with versatile tool APIs ![GitHub Repo stars](https://img.shields.io/github/stars/InternLM/agentlego?style=social)
- [UFO](https://github.com/microsoft/UFO) - A UI-Focused Agent for Windows OS Interaction. ![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/UFO?style=social)

## Related

### Survey

- [A Survey on Large Language Model based Autonomous Agents](https://github.com/Paitesanshi/LLM-Agent-Survey) <a href='https://arxiv.org/abs/2308.11432'><img src='https://img.shields.io/badge/Paper-PDF-red'></a> 
- [The Rise and Potential of Large Language Model Based Agents: A Survey](https://github.com/WooooDyy/LLM-Agent-Paper-List) <a href='https://arxiv.org/abs/2309.07864'><img src='https://img.shields.io/badge/Paper-PDF-red'></a> 

### Paper-List Repo

- [Awesome-Papers-Autonomous-Agent](https://github.com/lafmdp/Awesome-Papers-Autonomous-Agent) - A collection of recent papers on building autonomous agent. Two topics included: RL-based / LLM-based agents.
- [LLM-Agents-Papers](https://github.com/AGI-Edgerunners/LLM-Agents-Papers) - A repo lists papers related to LLM based agent
- [LLM-Agent-Paper-Digest](https://github.com/XueyangFeng/LLM-Agent-Paper-Digest) - papers related to LLM-agent that published on top conferences
- [awesome-language-agents](https://github.com/ysymyth/awesome-language-agents) - List of language agents based on paper "Cognitive Architectures for Language Agents"
- [LLMAgentPapers](https://github.com/zjunlp/LLMAgentPapers) - Must-read Papers on LLM Agents.

### Blog

- [LLM Powered Autonomous Agents](https://lilianweng.github.io/posts/2023-06-23-agent/) - Amazing blog by Lilian Weng (OpenAI), Jun 23, 2023.
- [从第一性原理看大模型Agent技术](https://mp.weixin.qq.com/s/PL-QjlvVugUfmRD4g0P-qQ)
- [基于大语言模型的AI Agents](https://www.breezedeus.com/article/ai-agent-part3)
- [ICLR'24 上大型语言模型代理的最新研究进展 | 代理评估重点](https://medium.com/@aminerscholar_39923/latest-research-advancements-on-large-language-model-agents-at-iclr24-agent-evaluation-focus-aed420421365)


## Reference Repo

- [awesome-llm-powered-agent](https://github.com/hyp1231/awesome-llm-powered-agent) - Awesome things about LLM-powered agents. Papers / Repos / Blogs / ...
- [awesome-agents](https://github.com/kyrolabs/awesome-agents) - 🤖 Awesome list of AI Agents
- [awesome-ai-agents](https://github.com/e2b-dev/awesome-ai-agents) - A list of AI autonomous agents
- [awesome-ai-agents](https://github.com/slavakurilyak/awesome-ai-agents) - Awesome list of 100+ agentic AI resources
- [Best-AI-Agents](https://github.com/SamurAIGPT/Best-AI-Agents) - A list of top AI agents
- [ai-agent-roadmap](https://github.com/Yuan-ManX/ai-agent-roadmap) - Explore the latest AI Agent Framework!
- [Inspired projects by babyagi](https://github.com/yoheinakajima/babyagi/blob/main/docs/inspired-projects.md)


## 公众号

公众号：「ChaosstuffAI」

<img src="./images/gongzhonghao.png" width="35%">
