---
categories:
- chemical-science
- machine-learning
- resources
- AI
- healthcare
date: '2025-12-15'
description: Curated resources on LLM agents for drug discovery, synthesis planning, and healthcare applications
layout: post
title: LLMs & Agentic AI for Scientific Discovery
toc: true
---

*Last updated: December 2025*

Large language models are reshaping how we approach early-phase discovery. This guide covers practical applications in synthesis planning, molecular design, clinical workflows, and autonomous experimentation.

## Why This Matters

LLMs unlock four capabilities for discovery teams:

1. **Low-data modeling** — Pre-trained representations enable predictions with limited experimental data
2. **Multi-endpoint prediction** — One model handles ADME, tox, and activity across modalities
3. **Workflow orchestration** — Natural language interfaces to complex multi-step procedures
4. **Literature-scale reasoning** — Query and synthesize across millions of papers

The field is moving from chatbots to agents that plan, execute, and iterate autonomously.

## Agents for Early-Phase Discovery

### Autonomous Synthesis

| Agent | What It Does | Links |
|-------|--------------|-------|
| **Coscientist** | Plans and executes organic syntheses via lab robotics | [Nature](https://www.nature.com/articles/s41586-023-06792-0) ・ [Code](https://github.com/gomesgroup/coscientist) |
| **LLM-RDF** | End-to-end reaction development platform | [Nature Comms](https://www.nature.com/articles/s41467-024-54457-x) ・ [Code](https://github.com/Ruan-Yixiang/LLM-RDF) |
| **ChemAgent** | Multiagent robotic chemist for on-demand synthesis | [JACS](https://pubs.acs.org/doi/10.1021/jacs.4c17738) |
| **SynAsk** | ReAct agent with yield prediction and retrosynthesis | [Chem Sci](https://pubs.rsc.org/en/content/articlelanding/2025/sc/d4sc04757e) |

### Molecular Design & Optimization

| Agent | What It Does | Links |
|-------|--------------|-------|
| **ChemCrow** | Tool-augmented LLM for similarity search, format conversion, route planning | [arXiv](https://arxiv.org/abs/2304.05376) ・ [Code](https://github.com/ur-whitelab/chemcrow-public) |
| **dZiner** | Inverse design of materials with AI agents | [arXiv](https://arxiv.org/abs/2410.03963) ・ [Code](https://github.com/mehradans92/dziner) |
| **CACTUS** | Chemistry agent connecting tool usage to science | [ACS Omega](https://pubs.acs.org/doi/10.1021/acsomega.4c08408) ・ [Code](https://github.com/pnnl/cactus) |
| **Llamole** | Multimodal LLM for inverse design with retrosynthesis | [arXiv](https://arxiv.org/abs/2410.04223) |

### Simulation & Dynamics

| Agent | What It Does | Links |
|-------|--------------|-------|
| **DynaMate** | Autonomous protein-ligand MD simulations | [arXiv](https://arxiv.org/abs/2512.10034) ・ [Code](https://github.com/schwallergroup/DynaMate) |
| **MDCrow** | Automates molecular dynamics workflows | [arXiv](https://arxiv.org/abs/2502.09565) ・ [Code](https://github.com/ur-whitelab/MDCrow) |
| **El-Agente** | Autonomous quantum chemistry calculations | [arXiv](https://arxiv.org/pdf/2505.02484) |
| **DREAMS** | DFT-based agentic materials simulation | [arXiv](https://arxiv.org/abs/2507.14267) |

### Biology & Protein Engineering

| Agent | What It Does | Links |
|-------|--------------|-------|
| **Virtual Lab** | Multi-agent nanobody design with experimental validation | [bioRxiv](https://www.biorxiv.org/content/10.1101/2024.11.11.623004v1) ・ [Code](https://github.com/zou-group/virtual-lab) |
| **ProtAgent** | Protein discovery via multi-agent collaboration | [arXiv](https://arxiv.org/abs/2402.04268) ・ [Code](https://github.com/lamm-mit/ProtAgents) |
| **CRISPR-GPT** | Automated gene-editing experiment design | [arXiv](https://arxiv.org/abs/2404.18021) |
| **SpatialAgent** | Autonomous spatial biology analysis | [bioRxiv](https://www.biorxiv.org/content/10.1101/2025.04.03.646459v1) |
| **BioDiscoveryAgent** | Biomedical discovery from Stanford SNAP | [Code](https://github.com/snap-stanford/BioDiscoveryAgent) |

## Healthcare Applications

### Clinical Reasoning & Decision Support

| System | Application | Links |
|--------|-------------|-------|
| **TxAgent** | Therapeutic reasoning across biomedical tools via Tool-RAG | [arXiv](https://arxiv.org/pdf/2503.10970) ・ [Code](https://github.com/mims-harvard/TxAgent) |
| **Personal Health Agent** | Anatomy of a personal health assistant | [arXiv](https://arxiv.org/abs/2508.20148) |
| **Med-Gemini** | Google's medical multimodal foundation model | [arXiv](https://doi.org/10.48550/arXiv.2404.18416) |
| **G-Mode** | Healthcare AI platform | [Website](https://gmode.genhealth.ai/) |

### Clinical Text & Documentation

| System | Application | Links |
|--------|-------------|-------|
| **Clinical Summarization** | LLMs outperforming experts in 36% of cases | [Nature Med](https://www.nature.com/articles/s41591-024-02855-5) ・ [Code](https://github.com/StanfordMIMI/clin-summ) |
| **CLEAR** | Clinical entity augmented retrieval for extraction | [npj Digital Med](https://www.nature.com/articles/s41746-024-01377-1) |

### Evaluation

| Benchmark | Focus | Link |
|-----------|-------|------|
| **MedHELM** | 121 clinical tasks across 35 benchmarks | [Website](https://crfm.stanford.edu/helm/medhelm/latest/) |
| **The Optimization Paradox** | Multi-agent clinical systems analysis | [arXiv](https://arxiv.org/abs/2506.06574v1) |

## Foundation Models for Discovery

### Chemistry & Small Molecules

| Model | Strength | Links |
|-------|----------|-------|
| **Tx-LLM** | Multi-endpoint ADME prediction, positive transfer learning | [arXiv](https://arxiv.org/html/2406.06316v1) |
| **NatureLM** | Cross-domain: molecules, proteins, materials | [arXiv](https://arxiv.org/abs/2502.07527) |
| **LlaSMol** | Instruction-tuned for chemistry tasks | [Website](https://osu-nlp-group.github.io/LLM4Chem/) |
| **BioT5+** | IUPAC integration, numerical tokenization | [arXiv](https://arxiv.org/pdf/2402.17810.pdf) |
| **Chemformer** | Pre-trained transformer for computational chemistry | [Code](https://github.com/MolecularAI/Chemformer) |
| **ether0** | Scientific reasoning model for chemistry (GRPO-trained) | [Code](https://github.com/Future-House/ether0) |

### Proteins & Genomics

| Model | Strength | Links |
|-------|----------|-------|
| **Evo2** | Genomic foundation model | [Arc Institute](https://arcinstitute.org/tools/evo) |
| **ProCyon** | Multimodal protein phenotype prediction | [bioRxiv](https://www.biorxiv.org/content/10.1101/2024.12.10.627665v1) |
| **EvoDiff** | Diffusion-based protein generation in sequence space | [Code](https://github.com/microsoft/evodiff) |
| **BioEmu-1** | Protein dynamics and conformational changes | [Microsoft](https://www.microsoft.com/en-us/research/blog/exploring-the-structural-changes-driving-protein-function-with-bioemu-1/) |

## Literature & Knowledge Systems

### RAG for Science

| System | Application | Links |
|--------|-------------|-------|
| **PaperQA** | RAG agent that doesn't hallucinate citations | [arXiv](https://arxiv.org/abs/2312.07559) |
| **STORM** | Wikipedia-style article generation from sources | [Code](https://github.com/stanford-oval/storm) |
| **WikiCrow** | Automated scientific knowledge synthesis | [Website](https://www.futurehouse.org/wikicrow) |
| **MERMaid** | Multimodal extraction from PDFs using VLMs | [ChemRxiv](https://chemrxiv.org/engage/chemrxiv/article-details/67c6170c6dde43c90858b305) |

### Data Curation

- [From text to insight](https://pubs.rsc.org/en/content/articlehtml/2025/cs/d4cs00913d) — Tutorial review on LLMs for chemical data extraction (Jablonka group)
- [LLM organic synthesis extraction](https://github.com/qai222/LLM_organic_synthesis) — Fine-tuned GPT for parsing synthesis procedures

## Building Agents

### Frameworks

| SDK | Best For | Link |
|-----|----------|------|
| **LangGraph** | Graph-based workflows, multi-agent | [Code](https://github.com/langchain-ai/langgraph) |
| **PydanticAI** | Type-safe agent development | [Code](https://github.com/pydantic/pydantic-ai) |
| **Smolagents** | Lightweight HuggingFace ecosystem | [Code](https://github.com/huggingface/smolagents) |
| **CrewAI** | Multi-agent orchestration | [Website](https://www.crewai.com/) |

### Engineering Patterns

- **[Claude Think Tool](https://www.anthropic.com/engineering/claude-think-tool)** — Dedicated reasoning step for complex tool chains
- **[AvaTaR](https://github.com/zou-group/avatar)** — Contrastive learning for tool-use optimization (DSPy integrated)
- **[ADAS](https://www.shengranhu.com/ADAS/)** — Automated design of agentic systems
- **[Aviary](https://github.com/Future-House/aviary)** — Training language agents as MDPs on scientific tasks

### Infrastructure

| Category | Tools |
|----------|-------|
| **Code Sandbox** | [E2B](https://e2b.dev/docs), [Arrakis](https://github.com/abshkbh/arrakis) |
| **Browser** | [browser-use](https://github.com/browser-use/browser-use) |
| **Documents** | [Reducto](https://reducto.ai/blog), [Firecrawl](https://github.com/mendableai/firecrawl) |
| **MCP Servers** | [UniProt](https://github.com/Augmented-Nature/UniProt-MCP-Server), [Benchling](https://github.com/Benchling-Labs/benchling-mcp-server) |

## Benchmarks

### Chemistry

| Benchmark | Focus | Link |
|-----------|-------|------|
| **ChemIQ** | Chemical intelligence beyond MCQs | [Code](https://github.com/oxpig/ChemIQ) |
| **ChemBench** | General chemistry understanding | [Website](https://www.chembench.org/) |
| **MaCBench** | Materials chemistry | [HuggingFace](https://huggingface.co/datasets/jablonkagroup/MaCBench) |

### Biology & Healthcare

| Benchmark | Focus | Link |
|-----------|-------|------|
| **LAB-Bench** | Laboratory protocol execution | [arXiv](https://arxiv.org/abs/2407.10362) |
| **BixBench** | Bioinformatics tasks | [arXiv](https://arxiv.org/abs/2503.00096) |
| **Bio-ML** | Biology ML evaluation | [bioRxiv](https://www.biorxiv.org/content/10.1101/2025.09.01.673319v2) |

### Agent Reliability

- [SWE-bench](https://www.swebench.com/) — Software engineering
- [HAL](https://hal.cs.princeton.edu/) — General agent reliability

## Current Limitations

**Reliability**: Non-deterministic outputs; query phrasing significantly affects results.

**Tool Selection**: Performance degrades as available tools increase.

**Memory**: Long workflow context management remains challenging.

**Bottom line**: Agents demonstrate impressive capabilities but lack production reliability. Build metrics that capture both.

## Key Reading

**Reviews**
- [LLMs and Autonomous Agents in Chemistry](https://arxiv.org/abs/2407.01603) — White lab survey
- [Empowering Biomedical Discovery with AI Agents](https://www.cell.com/cell/fulltext/S0092-8674(24)01070-5) — Zitnik lab (Cell)
- [Foundation Models for Materials Discovery](https://www.nature.com/articles/s41524-025-01538-0) — npj Computational Materials

**Engineering**
- [Building Effective Agents](https://www.anthropic.com/research/building-effective-agents) — Anthropic
- [12-Factor Agents](https://github.com/humanlayer/12-factor-agents) — Human Layer
- [Small Agents Position Paper](https://research.nvidia.com/labs/lpr/slm-agents/) — NVIDIA

## Comprehensive Agent Timeline

| Date | Agent | Description | Links |
|------|-------|-------------|-------|
| 2025.12 | DynaMate | Protein-ligand MD automation | [Paper](https://arxiv.org/abs/2512.10034) ・ [Code](https://github.com/schwallergroup/DynaMate) |
| 2025.09 | Personal Health Agent | Health assistant architecture | [Paper](https://arxiv.org/abs/2508.20148) |
| 2025.07 | DREAMS | DFT-based materials simulation | [Paper](https://arxiv.org/abs/2507.14267) |
| 2025.05 | ROBIN | Multi-agent scientific discovery | [Paper](https://arxiv.org/pdf/2505.13400) ・ [Code](https://github.com/Future-House/robin) |
| 2025.05 | El-Agente | Quantum chemistry automation | [Paper](https://arxiv.org/pdf/2505.02484) |
| 2025.04 | SpatialAgent | Spatial biology | [Paper](https://www.biorxiv.org/content/10.1101/2025.04.03.646459v1) |
| 2025.03 | TxAgent | Therapeutic reasoning | [Paper](https://arxiv.org/pdf/2503.10970) ・ [Code](https://github.com/mims-harvard/TxAgent) |
| 2025.01 | DataAnalysisCrow | Jupyter notebook agent | [Code](https://github.com/Future-House/data-analysis-crow) |
| 2024.12 | Aviary | Agent training framework | [Paper](https://arxiv.org/abs/2412.21154) ・ [Code](https://github.com/Future-House/aviary) |
| 2024.11 | Virtual Lab | Multi-agent nanobody design | [Paper](https://www.biorxiv.org/content/10.1101/2024.11.11.623004v1) ・ [Code](https://github.com/zou-group/virtual-lab) |
| 2024.11 | DrugAgent | Drug discovery automation | [Paper](https://arxiv.org/abs/2411.15692) |
| 2024.11 | LLM-RDF | Chemical synthesis platform | [Paper](https://www.nature.com/articles/s41467-024-54457-x) ・ [Code](https://github.com/Ruan-Yixiang/LLM-RDF) |
| 2024.10 | dZiner | Inverse materials design | [Paper](https://arxiv.org/abs/2410.03963) ・ [Code](https://github.com/mehradans92/dziner) |
| 2024.10 | CACTUS | Chemistry tool usage | [Paper](https://pubs.acs.org/doi/10.1021/acsomega.4c08408) ・ [Code](https://github.com/pnnl/cactus) |
| 2024.06 | LLaMP | Materials knowledge retrieval | [Paper](https://arxiv.org/abs/2401.17244) ・ [Code](https://github.com/chiang-yuan/llamp) |
| 2024.04 | CRISPR-GPT | Gene-editing design | [Paper](https://arxiv.org/abs/2404.18021) |
| 2024.02 | TAIS | Gene expression discovery | [Paper](https://arxiv.org/abs/2402.12391) |
| 2024.02 | WikiCrow | Scientific knowledge synthesis | [Website](https://www.futurehouse.org/wikicrow) |
| 2024.02 | STORM | Wikipedia-style generation | [Paper](https://arxiv.org/abs/2402.14207) ・ [Code](https://github.com/stanford-oval/storm) |
| 2024.02 | SciAgent | Tool-augmented scientific reasoning | [Paper](https://arxiv.org/abs/2402.11451) |
| 2024.01 | ProtAgent | Protein discovery multi-agent | [Paper](https://arxiv.org/abs/2402.04268) ・ [Code](https://github.com/lamm-mit/ProtAgents) |
| 2023.12 | PaperQA | Scientific literature RAG | [Paper](https://arxiv.org/abs/2312.07559) |
| 2023.12 | Coscientist | Autonomous chemical research | [Paper](https://www.nature.com/articles/s41586-023-06792-0) ・ [Code](https://github.com/gomesgroup/coscientist) |
| 2023.12 | Eunomia | Materials data from literature | [Paper](https://arxiv.org/abs/2312.11690) ・ [Code](https://github.com/AI4ChemS/Eunomia) |
| 2023.11 | eXpertAI | Structure-property XAI | [Paper](https://arxiv.org/abs/2311.04047) ・ [Code](https://github.com/geemi725/XpertAI) |
| 2023.10 | BioPlanner | Protocol planning evaluation | [Paper](https://arxiv.org/abs/2310.10632) ・ [Code](https://github.com/bioplanner/bioplanner) |
| 2023.09 | IBM ChemChat | Molecular discovery | [Paper](https://arxiv.org/abs/2309.16235) |
| 2023.08 | ChatMOF | MOF prediction and generation | [Paper](https://arxiv.org/abs/2308.01423) ・ [Code](https://github.com/Yeonghun1675/ChatMOF) |
| 2023.06 | AmadeusGPT | Animal behavior analysis | [Paper](https://arxiv.org/abs/2307.04858) ・ [Code](https://github.com/AdaptiveMotorControlLab/AmadeusGPT) |
| 2023.04 | ChemCrow | Chemistry tools for LLMs | [Paper](https://arxiv.org/abs/2304.05376) ・ [Code](https://github.com/ur-whitelab/chemcrow-public) |

## Industry & Products

**Lab Automation**: Tetsuwan, Artificial AI, Lila Science, Mithri

**Research Assistants**: LOWE (Recursion), Mara (Nanome), Edison, SuperBio, Sam (ScienceMachine)

**Platforms**: [FutureHouse](https://platform.futurehouse.org/), [G-Mode](https://gmode.genhealth.ai/), [Biomni](https://biomni.stanford.edu/)
