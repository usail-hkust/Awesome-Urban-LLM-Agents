# Awesome-Urban-LLM-Agents

<p align="center">

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
![Testing Status](https://img.shields.io/badge/license-MIT-blue)
![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green)
![Stars](https://img.shields.io/github/stars/usail-hkust/Awesome-Urban-LLM-Agents)

</p>

An Awesome Collection of Urban LLM Agents.

<a id="news"></a>

## Outline
- [Awesome-Urban-LLM-Agents](#awesome-urban-llm-agents)
  - [News](#news)
  - [Agent-Centric Perspective](#agent-centric-perspective)
    - [Urban Sensing](#urban-sensing)
      - [Sensing Modalities](#sensing-modalities)
      - [Semantic Unification](#semantic-unification)
    - [Memory Management](#memory-management)
      - [Memory Acquisition](#memory-acquisition)
      - [Memory Retrieval](#memory-retrieval)
      - [Memory Utilization](#memory-utilization)
    - [Reasoning](#reasoning)
      - [Temporal Reasoning](#temporal-reasoning)
      - [Spatial Reasoning](#spatial-reasoning)
      - [Spatio-Temporal Reasoning](#spatio-temporal-reasoning)
    - [Execution](#execution)
      - [Single Agent Execution](#single-agent-execution)
      - [Mutli-Agent Collaboration](#mutli-agent-collaboration)
      - [Human-Agent Collaboration](#human-agent-collaboration)
    - [Learning](#learning)
      - [Learning from Sythetic Data](#learning-from-sythetic-data)
      - [Learning from Environmental Feedback](#learning-from-environmental-feedback)
  - [Application-Centric Perspective](#application-centric-perspective)
    - [LLM Agents for Urban Planning](#llm-agents-for-urban-planning)
      - [Central Planning](#central-planning)
      - [Participatory Planning](#participatory-planning)
    - [LLM Agents for Transportation System](#llm-agents-for-transportation-system)
      - [Infrastructure Optimization](#Infrastructure-Optimization)
      - [Human-centric Services](#Human-centric-Services)
    - [LLM Agents for Environmental Sustainability](#llm-agents-for-environmental-sustainability)
      - [Energy Management](#Energy-Management)
      - [Pollution Control](#Pollution-Control)
      - [Climate Adaptation](#Climate-Adaptation)
    - [LLM Agents for Public Safety](#llm-agents-for-public-safety)
      - [Crime Prevention](#Crime-Prevention)
      - [Emergency Response](#Emergency-Response)
      - [Public Opinion Management](#Public-Opinion-Management)
    - [LLM Agents for Urban Society](#llm-agents-for-urban-society)
      - [Human Mobility](#human-mobility)
      - [Social-Economic Activity](#social-economic-activity)
      - [Public Survey](#public-survey)
  - [Trustworthiness of Urban LLM Agents](#trustworthiness-of-urban-llm-agents)
  - [Performance Evaluation](#performance-evaluation)

## Agent-Centric Perspective

### Urban Sensing

#### Sensing Modalities
- (*arXiv'2024.01*) Towards Urban General Intelligence: A Review and Outlook of Urban Foundation Models [[paper](https://arxiv.org/abs/2402.01749)] [[repo](https://github.com/usail-hkust/Awesome-Urban-Foundation-Models)]
- (*Information Fusion'2025*) Deep Learning for Cross-Domain Data Fusion in Urban Computing: Taxonomy, Advances, and Outlook [[paper](https://arxiv.org/abs/2402.19348)] [[repo](https://github.com/yoshall/Awesome-Multimodal-Urban-Computing)]
- (*TIST'2014*) Urban Computing: Concepts, Methodologies, and Applications [[paper](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/UrbanComputing-zheng-tist2014.pdf)]

#### Semantic Unification
Modality-to-text translation
- (*arXiv'2024.05*) Large Language Models are Zero-Shot Next Location Predictors [[paper](https://arxiv.org/abs/2405.20962v3)]
- (*SIGIR'2024*) Large Language Models for Next Point-of-Interest Recommendation [[paper](https://arxiv.org/abs/2404.17591)] [[code](https://github.com/neolifer/LLM4POI)]
- (*NeurIPS'2023*) Large Language Models Are Zero-Shot Time Series Forecasters [[paper](https://proceedings.neurips.cc/paper_files/paper/2023/hash/3eb7ca52e8207697361b2c0fb3926511-Abstract-Conference.html)] [[code](https://github.com/ngruver/llmtime)]
- (*arXiv'2023.04*) On the Opportunities and Challenges of Foundation Models for Geospatial Artificial Intelligence [[paper](https://arxiv.org/abs/2304.06798)] [[code](https://github.com/neolifer/LLM4POI)]

Cross-modal alignment
- (*arXiv'2025.02*) Time-VLM: Exploring Multimodal Vision-Language Models for Augmented Time Series Forecasting [[paper](https://arxiv.org/abs/2502.04395)]
- (*NSR'2025*) A Survey on Multimodal Large Language Models [[paper](https://arxiv.org/abs/2306.13549)] [[repo](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models)]
- (*AAAI'2025*) UrbanVLP: Multi-Granularity Vision-Language Pretraining for Urban Socioeconomic Indicator Prediction [[paper](https://arxiv.org/abs/2403.16831)] [[code](https://github.com/CityMind-Lab/UrbanVLP)]
- (*KDD'2025*) MM-Path: Multi-modal, Multi-granularity Path Representation Learning [[paper](https://arxiv.org/abs/2411.18428)] [[code](https://github.com/decisionintelligence/MM-Path)]
- (*KDD'2024*) UrbanGPT: Spatio-Temporal Large Language Models [[paper](https://arxiv.org/abs/2403.00813)] [[code](https://github.com/HKUDS/UrbanGPT)]
- (*KDD'2024*) ReFound: Crafting a Foundation Model for Urban Region Understanding upon Language and Visual Foundations [[paper](https://huangjizhou.github.io/papers/ReFound-KDD24.pdf)] [[code](https://github.com/PaddlePaddle/PaddleSpatial/tree/main/research/ReFound)]
- (*WWW'2024*) UrbanCLIP: Learning Text-enhanced Urban Region Profiling with Contrastive Language-Image Pretraining from the Web [[paper](https://arxiv.org/abs/2310.18340)] [[code](https://github.com/StupidBuluchacha/UrbanCLIP)]

Tool-assisted processing
- (*arXiv'2024.11*) GIS Copilot: Towards an Autonomous GIS Agent for Spatial Analysis [[paper](https://arxiv.org/abs/2411.03205)] [[code](https://github.com/Teakinboyewa/SpatialAnalysisAgent)]
- (*Transport Policy'2024*) TrafficGPT: Viewing, Processing and Interacting with Traffic Foundation Models [[paper](https://arxiv.org/abs/2309.06719)] [[code](https://github.com/lijlansg/TrafficGPT)]

### Memory Management
#### Memory Acquisition
Operational state memory
- (*arXiv'2025.03*) CoLLMLight: Cooperative Large Language Model Agents for Network-Wide Traffic Signal Control [[paper](https://arxiv.org/abs/2503.11739v1)] [[code](https://github.com/usail-hkust/CoLLMLight)]
- (*arXiv'2024.10*) TrajAgent: An Agent Framework for Unified Trajectory Modelling [[paper](https://arxiv.org/abs/2410.20445v1)] [[code](https://github.com/tsinghua-fib-lab/TrajAgent)]
- (*NAACL'2025*) AgentMove: A Large Language Model based Agentic Framework for Zero-shot Next Location Prediction [[paper](https://arxiv.org/abs/2408.13986v2)] [[code](https://github.com/tsinghua-fib-lab/AgentMove)]
- (*KDD'2025*) LLMLight: Large Language Models as Traffic Signal Control Agents [[paper](https://arxiv.org/abs/2312.16044v5)] [[code](https://github.com/usail-hkust/LLMTSCS)]

Geospatial map memory
- (*arXiv'2025.02*) Spatial-RAG: Spatial Retrieval Augmented Generation for Real-World Spatial Reasoning Questions [[paper](https://arxiv.org/abs/2502.18470v3)]
- (*arXiv'2024.06*) CityGPT: Empowering Urban Spatial Cognition of Large Language Models [[paper](https://arxiv.org/abs/2406.13948v1)] [[code](https://github.com/tsinghua-fib-lab/CityGPT)]
- (*Transport Policy'2024*) TrafficGPT: Viewing, Processing and Interacting with Traffic Foundation Models [[paper](https://arxiv.org/abs/2309.06719)] [[code](https://github.com/lijlansg/TrafficGPT)]

Vector database memory
- (*arXiv'2024.02*) PlanGPT: Enhancing Urban Planning with Tailored Language Model and Efficient Retrieval [[paper](https://arxiv.org/abs/2402.19273v1)]
- (*EMNLP'2024*) ItiNera: Integrating Spatial Optimization with Large Language Models for Open-domain Urban Itinerary Planning [[paper](https://arxiv.org/abs/2402.07204v5)] [[code](https://github.com/YihongT/ITINERA)]
- (*VLDBJ'2024*) Survey of Vector Database Management Systems [[paper](https://link.springer.com/article/10.1007/s00778-024-00864-x)]

Knowledge graph memory
- (*NeurIPS'2024*) UrbanKGent: A Unified Large Language Model Agent Framework for Urban Knowledge Graph Construction [[paper](https://arxiv.org/abs/2402.06861v2)] [[code](https://github.com/usail-hkust/UrbanKGent)]
- (*NeurIPS'2023*) UUKG: Unified Urban Knowledge Graph Dataset for Urban Spatiotemporal Prediction [[paper](https://proceedings.neurips.cc/paper_files/paper/2023/hash/c4a30a4dd840cfeff30ba4d2661ff097-Abstract-Datasets_and_Benchmarks.html)] [[code](https://github.com/usail-hkust/UUKG/)]
- (*TIST'2023*) UrbanKG: An Urban Knowledge Graph System [[paper]([https://arxiv.org/abs/2402.19273v1](https://dl.acm.org/doi/full/10.1145/3588577?casa_token=1lrHT_ebnMwAAAAA%3A5gO_k_gfKj3yPAlXGjzpqVPG9GCfU0Smog1gvSkBufjRm2axPyMEc3UNu9xY1G2LN0BlGztO9iMWEHY))]

#### Memory Retrieval
Spatio-temporal retrieval
- (*CSUR'2022*) A Survey on Spatio-temporal Data Analytics Systems [[paper](https://dl.acm.org/doi/full/10.1145/3507904?casa_token=4A6lmvFaP3kAAAAA%3ANHA6c-T_JJAarr7epm0UBmH7bPw79yegvzDX0Rv25l7xlkVSIXSfaf-SMOd7hcV3bFKOftMVw9VsFv8)]
- (*ICDE'2020*) JUST: JD Urban Spatio-Temporal Data Engine [[paper](https://ieeexplore.ieee.org/abstract/document/9101507?casa_token=676iqCHflKMAAAAA:hd2T_M3U58r7dVUGbYUuz47IAHD7SVHNXthUjg4paSctJHGaoLGZApixe5NctX69pOSva1jv4K80SQ)]
- (*GeoInformatica'2018*) ST-Hadoop: a MapReduce framework for spatio-temporal data [[paper](https://link.springer.com/article/10.1007/s10707-018-0325-6)]
- (*SIGSPATIAL'2015*) GeoSpark: a cluster computing framework for processing large-scale spatial data [[paper](https://dl.acm.org/doi/abs/10.1145/2820783.2820860?casa_token=5avcBMdPFR4AAAAA:RsF6NhBYEpINo4qDUfsCCP6-RsHEHy3N3-ekzlOGyvdKEG5Y1DN4YodMRnh1pMZpHDt-NwG17-WgNUA)]
- (*VLDB'2016*) LocationSpark: A Distributed In-Memory Data Management System for Big Spatial Data [[paper](https://dl.acm.org/doi/abs/10.14778/3007263.3007310?casa_token=lnem1yFYwrwAAAAA:PnuKAwIXlmS2PSIQ4DD54PzG9jtJbKP1dp_wmbc_MGFuBn31sf3Lkuaib0og1RkTJb6DLj-Thw_gWSQ)] [[code](https://github.com/purduedb/LocationSpark)]
- (*SPIE'2015*) GeoMesa: a distributed architecture for spatio-temporal fusion [[paper](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/9473/1/GeoMesa-a-distributed-architecture-for-spatio-temporal-fusion/10.1117/12.2177233.short)]
- (*TIST'2014*) Urban Computing: Concepts, Methodologies, and Applications [[paper](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/UrbanComputing-zheng-tist2014.pdf)]

Semantic retrieval
- (*arXiv'2024.02*) PlanGPT: Enhancing Urban Planning with Tailored Language Model and Efficient Retrieval [[paper](https://arxiv.org/abs/2402.19273v1)]
- (*EMNLP'2024*) ItiNera: Integrating Spatial Optimization with Large Language Models for Open-domain Urban Itinerary Planning [[paper](https://arxiv.org/abs/2402.07204v5)] [[code](https://github.com/YihongT/ITINERA)]

Hybrid retrieval
- (*arXiv'2025.02*) Spatial-RAG: Spatial Retrieval Augmented Generation for Real-World Spatial Reasoning Questions [[paper](https://arxiv.org/abs/2502.18470v3)]

#### Memory Utilization
- (*arXiv'2024.02*) PlanGPT: Enhancing Urban Planning with Tailored Language Model and Efficient Retrieval [[paper](https://arxiv.org/abs/2402.19273v1)]
- (*NAACL'2025*) AgentMove: A Large Language Model based Agentic Framework for Zero-shot Next Location Prediction [[paper](https://arxiv.org/abs/2408.13986v2)] [[code](https://github.com/tsinghua-fib-lab/AgentMove)]

### Reasoning
#### Temporal Reasoning
General scenarios
- (*ICLR'2025*) Test of Time: A Benchmark for Evaluating LLMs on Temporal Reasoning [[paper](https://arxiv.org/abs/2406.09170v1)] [[code](https://huggingface.co/datasets/baharef/ToT)]
- (*WWW'2024*) Back to the Future: Towards Explainable Temporal Reasoning with Large Language Models [[paper](https://dl.acm.org/doi/abs/10.1145/3589334.3645376?casa_token=hDUZq4GZXO0AAAAA:SccttAHiepJFhz1dzrt34CUyqEMJy3QyVSClLeduxISMEj1QT20WW3SZfobeMd4OU2UPfPSlxzg9hw)] [[code](https://github.com/chenhan97/TimeLlama)]
- (*CoLM'2024*) Timo: Towards Better Temporal Reasoning for Language Models [[paper](https://arxiv.org/abs/2406.14192)] [[code](https://github.com/zhaochen0110/Timo)]
- (*ACL'2024*) Living in the Moment: Can Large Language Models Grasp Co-Temporal Reasoning? [[paper](https://arxiv.org/abs/2406.09072)] [[code](https://github.com/zhaochen0110/Cotempqa)]
- (*ACL'2024*) TimeBench: A Comprehensive Evaluation of Temporal Reasoning Abilities in Large Language Models [[paper](https://arxiv.org/abs/2311.17667)] [[code](https://github.com/zchuz/TimeBench)]
- (*ACL'2024*) TRAM: Benchmarking Temporal Reasoning for Large Language Models [[paper](https://arxiv.org/abs/2310.00835v3)] [[code](https://github.com/EternityYW/TRAM-Benchmark)]
- (*ACL'2023*) Towards Benchmarking and Improving the Temporal Reasoning Capability of Large Language Models [[paper](https://arxiv.org/abs/2306.08952v2)] [[code](https://github.com/DAMO-NLP-SG/TempReason)]

Urban scenarios
- (*AAAI'2025*) ChatTime: A Unified Multimodal Time Series Foundation Model Bridging Numerical and Textual Data [[paper](https://ojs.aaai.org/index.php/AAAI/article/view/33384)] [[code](https://github.com/ForestsKing/ChatTime)]
- (*NeurIPS'2024*) From News to Forecast: Integrating Event Analysis in LLM-Based Time Series Forecasting with Reflection [[paper](https://proceedings.neurips.cc/paper_files/paper/2024/hash/6aef8bffb372096ee73d98da30119f89-Abstract-Conference.html)] [[code](https://github.com/ameliawong1996/From_News_to_Forecast)]
- (*ICLR'2024*) Time-LLM: Time Series Forecasting by Reprogramming Large Language Models [[paper](https://arxiv.org/abs/2310.01728v2)] [[code](https://github.com/KimMeen/Time-LLM)]

#### Spatial Reasoning
General scenarios
- (*arXiv'2024.12*) Thinking in Space: How Multimodal Large Language Models See, Remember, and Recall Spaces [[paper](https://arxiv.org/abs/2412.14171v1)] [[code](https://github.com/vision-x-nyu/thinking-in-space)]
- (*CVPR'2024*) SpatialVLM: Endowing Vision-Language Models with Spatial Reasoning Capabilities [[paper](https://openaccess.thecvf.com/content/CVPR2024/html/Chen_SpatialVLM_Endowing_Vision-Language_Models_with_Spatial_Reasoning_Capabilities_CVPR_2024_paper.html)] [[code](https://spatial-vlm.github.io/)]
- (*NeurIPS'2024*) Mind's Eye of LLMs: Visualization-of-Thought Elicits Spatial Reasoning in Large Language Models [[paper](https://openreview.net/forum?id=CEJ1mYPgWw)] [[code](https://github.com/microsoft/visualization-of-thought/)]
- (*CoLM'2024*) Chain-of-Symbol Prompting For Spatial Reasoning in Large Language Models [[paper](https://openreview.net/forum?id=Hvq9RtSoHG#discussion)] [[code](https://github.com/hanxuhu/chain-of-symbol-planning)]
- (*ACL'2024*) SpaRC and SpaRP: Spatial Reasoning Characterization and Path Generation for Understanding Spatial Reasoning Capability of Large Language Models [[paper](https://arxiv.org/abs/2406.04566v1)] [[code](https://github.com/UKPLab/acl2024-sparc-and-sparp)]
- (*AAAI'2024*) Advancing Spatial Reasoning in Large Language Models: An In-Depth Evaluation and Enhancement Using the StepGame Benchmark [[paper](https://ojs.aaai.org/index.php/AAAI/article/view/29811)] [[code](https://github.com/Fangjun-Li/SpatialLM-StepGame)]

Urban scenarios
- (*arXiv'2025.02*) Spatial-RAG: Spatial Retrieval Augmented Generation for Real-World Spatial Reasoning Questions [[paper](https://arxiv.org/abs/2502.18470v3)]
- (*arXiv'2024.08*) An Autonomous GIS Agent Framework for Geospatial Data Retrieval [[paper](https://arxiv.org/abs/2407.21024v2)] [[code](https://github.com/gladcolor/LLM-Find/)]
- (*arXiv'2024.06*) CityGPT: Empowering Urban Spatial Cognition of Large Language Models [[paper](https://arxiv.org/abs/2406.13948v1)] [[code](https://github.com/tsinghua-fib-lab/CityGPT)]
- (*arXiv'2024.03*) LAMP: A Language Model on the Map [[paper](https://arxiv.org/abs/2403.09059v2)] [[code](https://github.com/PasqualeTurin/LAMP/tree/main)]
- (*KDD'2025*) LLMLight: Large Language Models as Traffic Signal Control Agents [[paper](https://arxiv.org/abs/2312.16044v5)] [[code](https://github.com/usail-hkust/LLMTSCS)]
- (*EMNLP'2024*) ItiNera: Integrating Spatial Optimization with Large Language Models for Open-domain Urban Itinerary Planning [[paper](https://arxiv.org/abs/2402.07204v5)] [[code](https://github.com/YihongT/ITINERA)]


#### Spatio-Temporal Reasoning
- (*arXiv'2025.03*) CoLLMLight: Cooperative Large Language Model Agents for Network-Wide Traffic Signal Control [[paper](https://arxiv.org/abs/2503.11739v1)] [[code](https://github.com/usail-hkust/CoLLMLight)]
- (*arXiv'2024.05*) TravelAgent: An AI Assistant for Personalized Travel Planning [[paper](https://arxiv.org/abs/2409.08069v1)]
- (*arXiv'2024.05*) CityGPT: Towards Urban IoT Learning, Analysis and Interaction with Multi-Agent System [[paper](https://arxiv.org/pdf/2405.14691)]
- (*NAACL'2025*) AgentMove: A Large Language Model based Agentic Framework for Zero-shot Next Location Prediction [[paper](https://arxiv.org/abs/2408.13986v2)] [[code](https://github.com/tsinghua-fib-lab/AgentMove)]
- (*EMNLP'2024*) UrbanLLM: Autonomous Urban Activity Planning and Management with Large Language Models [[paper](https://arxiv.org/abs/2406.12360v1)]
- (*Transport Policy'2024*) TrafficGPT: Viewing, Processing and Interacting with Traffic Foundation Models [[paper](https://arxiv.org/abs/2309.06719)] [[code](https://github.com/lijlansg/TrafficGPT)]

### Execution
#### Single Agent Execution
Software control
- (*arXiv'2024.08*) An Autonomous GIS Agent Framework for Geospatial Data Retrieval [[paper](https://arxiv.org/abs/2407.21024v2)] [[code](https://github.com/gladcolor/LLM-Find/)]
- (*arXiv'2024.05*) TravelAgent: An AI Assistant for Personalized Travel Planning [[paper](https://arxiv.org/abs/2409.08069v1)]
- (*arXiv'2024.03*) LAMP: A Language Model on the Map [[paper](https://arxiv.org/abs/2403.09059v2)] [[code](https://github.com/PasqualeTurin/LAMP/tree/main)]
- (*arXiv'2024.02*) PlanGPT: Enhancing Urban Planning with Tailored Language Model and Efficient Retrieval [[paper](https://arxiv.org/abs/2402.19273v1)]
- (*NeurIPS'2024*) UrbanKGent: A Unified Large Language Model Agent Framework for Urban Knowledge Graph Construction [[paper](https://arxiv.org/abs/2402.06861v2)] [[code](https://github.com/usail-hkust/UrbanKGent)]
- (*EMNLP'2024*) UrbanLLM: Autonomous Urban Activity Planning and Management with Large Language Models [[paper](https://arxiv.org/abs/2406.12360v1)]
- (*EMNLP'2024*) ItiNera: Integrating Spatial Optimization with Large Language Models for Open-domain Urban Itinerary Planning [[paper](https://arxiv.org/abs/2402.07204v5)] [[code](https://github.com/YihongT/ITINERA)]

Hardware control
- (*arXiv‘2025.03*) CoLLMLight: Cooperative Large Language Model Agents for Network-Wide Traffic Signal Control [[paper](https://arxiv.org/pdf/2503.11739)] [[code](https://github.com/usail-hkust/CoLLMLight)]
- (*arXiv'2024.07*) iLLM-TSC: Integration reinforcement learning and large language model for traffic signal control policy improvement [[paper](https://arxiv.org/abs/2407.06025v1)] [[code](https://github.com/Traffic-Alpha/iLLM-TSC)]
- (*KDD'2025*) LLMLight: Large Language Models as Traffic Signal Control Agents [[paper](https://arxiv.org/pdf/2312.16044)] [[code](https://github.com/usail-hkust/LLMTSCS)]
- (*IJMLC'2024*) Open-TI: Open Traffic Intelligence with Augmented Language Model [[paper](https://link.springer.com/article/10.1007/s13042-024-02190-8)]

#### Mutli-Agent Collaboration
Implicit coordination
- (*arXiv‘2025.02*) AgentSociety: Large-Scale Simulation of LLM-Driven Generative Agents Advances Understanding of Human Behaviors and Society [[paper](https://arxiv.org/abs/2502.08691v1)] [[code](https://github.com/tsinghua-fib-lab/agentsociety)]
- (*arXiv‘2024.10*) OpenCity: A Scalable Platform to Simulate Urban Activities with Massive LLM Agents [[paper](https://arxiv.org/abs/2410.21286v1)]
- (*arXiv‘2023.12*) Urban Generative Intelligence (UGI): A Foundational Platform for Agents in Embodied City Environment [[paper](https://arxiv.org/abs/2312.11813v1)]

Explicit coordination
- (*arXiv‘2025.03*) CoLLMLight: Cooperative Large Language Model Agents for Network-Wide Traffic Signal Control [[paper](https://arxiv.org/pdf/2503.11739)] [[code](https://github.com/usail-hkust/CoLLMLight)]
- (*arXiv'2024.05*) CityGPT: Towards Urban IoT Learning, Analysis and Interaction with Multi-Agent System [[paper](https://arxiv.org/pdf/2405.14691)]

#### Human-Agent Collaboration
Process intervention
- (*arXiv'2024.05*) TravelAgent: An AI Assistant for Personalized Travel Planning [[paper](https://arxiv.org/abs/2409.08069v1)]
- (*arXiv'2024.02*) Large Language Model for Participatory Urban Planning [[paper](https://arxiv.org/abs/2402.17161v1)]
- (*Transport Policy'2024*) TrafficGPT: Viewing, Processing and Interacting with Traffic Foundation Models [[paper](https://arxiv.org/abs/2309.06719)] [[code](https://github.com/lijlansg/TrafficGPT)]
- (*CAI'2024*) LLM-Assisted Crisis Management: Building Advanced LLM Platforms for Effective Emergency Response and Public Collaboration [[paper](https://ieeexplore.ieee.org/abstract/document/10605553?casa_token=G8FPvaRzUXoAAAAA:ULrrsBvWI7yJu8A_qcMTywr3mDmoXZ2XLmQ_l79Qf5J_SO-g_bd06MjOzlF4uYHPJ83fgTT1mQgu)]

Post-hoc evaluation
- (*NeurIPS'2024*) UrbanKGent: A Unified Large Language Model Agent Framework for Urban Knowledge Graph Construction [[paper](https://arxiv.org/abs/2402.06861v2)] [[code](https://github.com/usail-hkust/UrbanKGent)]
- (*EMNLP'2024*) UrbanLLM: Autonomous Urban Activity Planning and Management with Large Language Models [[paper](https://arxiv.org/abs/2406.12360v1)]

### Learning
#### Learning from Sythetic Data
Vanilla instruction generation
- (*arXiv'2024.02*) PlanGPT: Enhancing Urban Planning with Tailored Language Model and Efficient Retrieval [[paper](https://arxiv.org/abs/2402.19273v1)]
- (*EMNLP'2024*) UrbanLLM: Autonomous Urban Activity Planning and Management with Large Language Models [[paper](https://arxiv.org/abs/2406.12360v1)]
- (*arXiv'2024.06*) Chain-of-Planned-Behaviour Workflow Elicits Few-Shot Mobility Generation in LLMs [[paper](https://arxiv.org/pdf/2402.09836)]


Advanced reasoning augmentation
- (*NeurIPS'2024*) UrbanKGent: A Unified Large Language Model Agent Framework for Urban Knowledge Graph Construction [[paper](https://arxiv.org/abs/2402.06861v2)] [[code](https://github.com/usail-hkust/UrbanKGent)]
- (*arXiv‘2023.12*) Urban Generative Intelligence (UGI): A Foundational Platform for Agents in Embodied City Environment [[paper](https://arxiv.org/abs/2312.11813v1)]
- (*arXiv'2024.10*) TrajAgent: An Agent Framework for Unified Trajectory Modelling [[paper](https://arxiv.org/abs/2410.20445v1)] [[code](https://github.com/tsinghua-fib-lab/TrajAgent)]

#### Learning from Environmental Feedback
Simulation-based feedback
- (*arXiv'2024.07*) iLLM-TSC: Integration reinforcement learning and large language model for traffic signal control policy improvement [[paper](https://arxiv.org/abs/2407.06025v1)] [[code](https://github.com/Traffic-Alpha/iLLM-TSC)]
- (*KDD'2025*) LLMLight: Large Language Models as Traffic Signal Control Agents [[paper](https://arxiv.org/pdf/2312.16044)] [[code](https://github.com/usail-hkust/LLMTSCS)]
- (*arXiv‘2025.03*) CoLLMLight: Cooperative Large Language Model Agents for Network-Wide Traffic Signal Control [[paper](https://arxiv.org/pdf/2503.11739)] [[code](https://github.com/usail-hkust/CoLLMLight)]
- (*arXiv'202502*) DiMA: An LLM-Powered Ride-Hailing Assistant at DiDi [[paper](https://arxiv.org/abs/2503.04768)]

Real-world feedback
- (*COMPSAC'2024*) WatchOverGPT: A Framework for Real-Time Crime Detection and Response Using Wearable Camera and Large Language Model [[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10633435)]


## Application-Centric Perspective

### LLM Agents for Urban Planning

#### Central Planning
- (*arXiv'202402*) PlanGPT: Enhancing Urban Planning with Tailored Language Model and Efficient Retrieval [[paper](https://arxiv.org/pdf/2402.19273)]
- (*arXiv'202406*) City-LEO: Toward Transparent City Management Using LLM with End-to-End Optimization [[paper](https://arxiv.org/pdf/2406.10958)]
- (*Sustainable Cities and Society'2024*) Large language model as parking planning agent in the context of mixed period of autonomous vehicles and Human-Driven vehicles [[paper](https://www.sciencedirect.com/science/article/pii/S2210670724007649)]
- (*arXiv'202504*) UrbanPlanBench: A Comprehensive Urban Planning Benchmark for Evaluating Large Language Models [[paper](https://arxiv.org/pdf/2504.21027)]
- (*Smart Cities'2025*) LLM Agents for Smart City Management: Enhancing Decision Support Through Multi-Agent AI Systems [[paper](https://www.mdpi.com/2624-6511/8/1/19)] [[code](https://github.com/ITMO-NSS-team/llm-agents-for-smartcities-paper)]

#### Participatory Planning
- (*arXiv'202402*) Large Language Model for Participatory Urban Planning [[paper](https://arxiv.org/pdf/2402.17161)]
- (*arXiv'202412*) Adaptive Urban Planning: A Hybrid Framework for Balanced City Development [[paper](https://arxiv.org/pdf/2412.15349)]
- (*AAAI AI4UP Workshop'2025*) Planning, Living and Judging: A Multi-agent LLM-based Framework for Cyclical Urban Planning [[paper](https://arxiv.org/pdf/2412.20505)]

### LLM Agents for Transportation System

#### Infrastructure Optimization

Traffic analytics
- (*IJMLC'2024*) Open-TI: Open Traffic Intelligence with Augmented Language Model [[paper](https://link.springer.com/article/10.1007/s13042-024-02190-8)]
- (*arXiv'202412*) TransitGPT: A Generative AI-based framework for interacting with GTFS data using Large Language Models [[paper](https://arxiv.org/pdf/2412.06831)] [[code](https://github.com/UTEL-UIUC/TransitGPT)]
- (*Transport Policy'2024*) TrafficGPT: Viewing, Processing and Interacting with Traffic Foundation Models [[paper](https://arxiv.org/abs/2309.06719)] [[code](https://github.com/lijlansg/TrafficGPT)]
- (*arXiv'202405*) CityGPT: Towards Urban IoT Learning, Analysis and Interaction with Multi-Agent System [[paper](https://arxiv.org/pdf/2405.14691)]

Traffic control
- (*arXiv'202407*) iLLM-TSC: Integration reinforcement learning and large language model for traffic signal control policy improvement [[paper]([https://arxiv.org/pdf/2312.16044](https://arxiv.org/pdf/2407.06025?))] [[code](https://github.com/Traffic-Alpha/iLLM-TSC)]
- (*arXiv'202408*) LLM Powered Sim-to-real Transfer for Traffic Signal Control [[paper](https://www.researchgate.net/profile/Longchao-Da/publication/373451211_LLM_Powered_Sim-to-real_Transfer_for_Traffic_Signal_Control/links/65461311b1398a779d5af74d/LLM-Powered-Sim-to-real-Transfer-for-Traffic-Signal-Control.pdf)]
- (*KDD'2025*) LLMLight: Large Language Models as Traffic Signal Control Agents [[paper](https://arxiv.org/pdf/2312.16044)] [[code](https://github.com/usail-hkust/LLMTSCS)]
- (*arXiv‘20503*) CoLLMLight: Cooperative Large Language Model Agents for Network-Wide Traffic Signal Control [[paper](https://arxiv.org/pdf/2503.11739)] [[code](https://github.com/usail-hkust/CoLLMLight)]
- (*arXiv'202406*) LLM-assisted light: Leveraging large language model capabilities for human-mimetic traffic signal control in complex urban environments [[paper](https://arxiv.org/pdf/2403.08337)][[code](https://github.com/Traffic-Alpha/LLM-Assisted-Light)]

#### Human-centric Services

Navigation and routing
- (*arXiv'202407*) TraveLLM: Could you plan my new public transit route in face of a network disruption? [[paper](https://arxiv.org/pdf/2407.14926)]
- (*arXiv'202504*) TP-RAG: Benchmarking Retrieval-Augmented Large Language Model Agents for Spatiotemporal-Aware Travel Planning [[paper](https://arxiv.org/pdf/2504.08694)]
- (*arXiv'202411*) LAMP: A language model on the map [[paper](https://arxiv.org/pdf/2403.09059)][[code](https://github.com/PasqualeTurin/LAMP/)]
- (*IEEE DOCS'24*) Research on Travel Route Planning Optimization based on Large Language Model [[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10704489)]
- (*arXiv'202412*) Generative agents in the streets: Exploring the use of Large Language Models (LLMs) in collecting urban perceptions [[paper](https://arxiv.org/pdf/2312.13126)]
- (*The Innovation*) Can language models be used for real-world urban-delivery route optimization? [[paper](https://www.cell.com/the-innovation/pdfExtended/S2666-6758(23)00148-0)]

On-demand mobility services
- (*arXiv'202412*) GARLIC: GPT-Augmented Reinforcement Learning with Intelligent Control for Vehicle Dispatching [[paper](https://arxiv.org/pdf/2408.10286)]
- (*arXiv'202502*) DiMA: An LLM-Powered Ride-Hailing Assistant at DiDi [[paper](https://arxiv.org/abs/2503.04768)]


### LLM Agents for Environmental Sustainability
#### Energy Management
- (*ACL'2025*) LLM4DistReconfig: A Fine-tuned Large Language Model for Power Distribution Network Reconfiguration [[paper](https://aclanthology.org/2025.naacl-long.208.pdf)]
- (*Scientific Reports'2025*) A large language model for advanced power dispatch [[paper](https://www.nature.com/articles/s41598-025-91940-x)]
- (*ICLR'2024*) Time-LLM: Time Series Forecasting by Reprogramming Large Language Models [[paper](https://arxiv.org/abs/2310.01728v2)] [[code](https://github.com/KimMeen/Time-LLM)]
- (*arXiv'202411*) EF-LLM: Energy Forecasting LLM with AI-assisted Automation, Enhanced Sparse Prediction, Hallucination Detection [[paper](https://arxiv.org/pdf/2411.00852)]

#### Pollution Control
- (*Smart Cities'2025*) LLM Agents for Smart City Management: Enhancing Decision Support Through Multi-Agent AI Systems [[paper](https://www.mdpi.com/2624-6511/8/1/19)]
- (*arXiv'202412*) Generative agents in the streets: Exploring the use of Large Language Models (LLMs) in collecting urban perceptions [[paper](https://arxiv.org/pdf/2312.13126)]
- (*ICPADS'2024*) LLMAir: Adaptive Reprogramming Large Language Model for Air Quality Prediction [[paper](https://ieeexplore.ieee.org/document/10763740)]
- (*arXiv'202503*) Instructor-Worker Large Language Model System for Policy Recommendation: a Case Study on Air Quality Analysis of the January 2025 Los Angeles Wildfires [[paper](https://arxiv.org/pdf/2503.00566)]

#### Climate Adaptation
- (*arXiv'202110*) Climatebert: A pretrained language model for climate-related text [[paper](https://arxiv.org/pdf/2110.12010)] [[code](https://github.com/ClimateBert/language-model)]
- (*arXiv'202401*) ClimateGPT: Towards AI Synthesizing Interdisciplinary Research on Climate Change [[paper](https://arxiv.org/pdf/2401.09646)] [[code](https://huggingface.co/eci-io)]
- (*Communications Earth & Environment'2023*) ChatClimate: Grounding conversational AI in climate science [[paper](https://www.nature.com/articles/s43247-023-01084-x)]
- (*ICLR'2025*) ClimaQA: An Automated Evaluation Framework for Climate Question Answering Models [[paper](https://arxiv.org/pdf/2410.16701)] [[code](https://github.com/Rose-STL-Lab/genie-climaqa)]


### LLM Agents for Public Safety
#### Crime Prevention
- (*FSIDI'2025*) Exploring the potential of large language models for improving digital forensic investigation efficiency [[paper](https://arxiv.org/pdf/2402.19366)]
- (*ICAART'2025*) CriX: Intersection of Crime, Demographics and Explainable AI [[paper](https://www.scitepress.org/Papers/2025/133162/133162.pdf)]
- (*COMPSAC'2024*) WatchOverGPT: A Framework for Real-Time Crime Detection and Response Using Wearable Camera and Large Language Model [[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10633435)]

#### Emergency Response
- (*ICFTIC'2024*) Multi-Agent Enhanced Complex Decision-Making Support Framework: An Urban Emergency Case Study [[paper](https://www.mdpi.com/2073-4441/12/4/1190)]
- (*IEEE CAI'2024*) Llm-assisted crisis management: Building advanced llm platforms for effective emergency response and public collaboration [[paper](https://arxiv.org/pdf/2402.10908)]

#### Public Opinion Management
- (*arXiv'202503*) Invisible Walls in Cities: Leveraging Large Language Models to Predict Urban Segregation Experience with Social Media Content [[paper](https://arxiv.org/pdf/2503.04773)]
- (*International Journal of Disaster Risk Reduction'2024*) Enhanced earthquake impact analysis based on social media texts via large language model [[paper](https://arxiv.org/pdf/2503.04773)]
- (*Geo-Inf'2024*) A question and answering service of typhoon disasters based on the t5 large language model [[paper](https://www.mdpi.com/2220-9964/13/5/165)]
- (*ICAICE'23*) Unleashing the Potential of Large Language Model: Zero-shot VQA for Flood Disaster Scenario [[paper](https://dl.acm.org/doi/10.1145/3652628.3652689)]
- (*IARRC'2024*) The Role of Large Language Models for Decision Support in Fire Safety Planning [[paper](https://www.iaarc.org/publications/2024_proceedings_of_the_41st_isarc_lille_france/the_role_of_large_language_models_for_decision_support_in_fire_safety_planning.html)]

### LLM Agents for Urban Society

#### Human Mobility
- (*NeurIPS'2024*) Large Language Models as Urban Residents: An LLM Agent Framework for Personal Mobility Generation [[paper](https://openreview.net/pdf?id=1iHmhMHNyA)] [[code](https://github.com/Wangjw6/LLMob)]
- (*arXiv'202402*) Chain-of-Planned-Behaviour Workflow Elicits Few-Shot Mobility Generation in LLMs [[paper](https://arxiv.org/pdf/2402.09836)] [[code](https://anonymous.4open.science/r/CoPB/readme.md)]
- (*arXiv'202407*) Be More Real: Travel Diary Generation Using LLM Agents and Individual Profiles [[paper](https://arxiv.org/pdf/2407.18932)]
- (*arXiv'202502*) TrajLLM: A Modular LLM-Enhanced Agent-Based Framework for Realistic Human Trajectory Simulation [[paper](https://arxiv.org/pdf/2502.18712)] [[code](https://github.com/cju0/TrajLLM)]
- (*arXiv'202308*) Where Would I Go Next? Large Language Models as Human Mobility Predictors [[paper](https://arxiv.org/pdf/2308.15197)] [[code](https://github.com/xlwang233/LLM-Mob)]
- (*NAACL'2025*) AgentMove: A Large Language Model based Agentic Framework for Zero-shot Next Location Prediction [[paper](https://aclanthology.org/2025.naacl-long.61.pdf)] [[code](https://github.com/tsinghua-fib-lab/AgentMove)]
- (*arXiv'202410*) TrajAgent: An Agent Framework for Unified Trajectory Modelling [[paper](https://arxiv.org/pdf/2410.20445)]
  
#### Social-Economic Activity
- (*UIST'2023*) Generative Agents: Interactive Simulacra of Human Behavior [[paper](https://arxiv.org/pdf/2304.03442)] [[code](https://github.com/joonspk-research/generative_agents)]
- (*EMNLP'2023*) Humanoid Agents: Platform for Simulating Human-like Generative Agents [[paper](https://aclanthology.org/2023.emnlp-demo.15.pdf)] [[code](https://github.com/HumanoidAgents/HumanoidAgents)]
- (*ICLR'2025*) Simulating Human-like Daily Activities with Desire-driven Autonomy [[paper](https://arxiv.org/pdf/2412.06435)] [[code](https://github.com/zfw1226/D2A)]
- (*ACL'2024*) EconAgent: Large Language Model-Empowered Agents for Simulating Macroeconomic Activities [[paper](https://aclanthology.org/2024.acl-long.829.pdf)] [[code](https://github.com/tsinghua-fib-lab/ACL24-EconAgent)]
- (*arXiv'202307*) Epidemic Modeling with Generative Agents [[paper](https://arxiv.org/pdf/2307.04986)] [[code](https://github.com/bear96/GABM-Epidemic)]
- (*AAMAS'2025*) On the limits of agency in agent-based models [[paper](https://arxiv.org/pdf/2409.10568)] [[code](https://github.com/AgentTorch/AgentTorch)]
- (*arXiv'202410*) OpenCity: A Scalable Platform to Simulate Urban Activities with Massive LLM Agents [[paper](https://arxiv.org/pdf/2410.21286)] [[code](https://github.com/tsinghua-fib-lab/Anonymous-OpenCity)]
- (*arXiv'202502*) AgentSociety: Large-Scale Simulation of LLM-Driven Generative Agents Advances Understanding of Human Behaviors and Society [[paper](https://arxiv.org/pdf/2502.08691)] [[code](https://github.com/tsinghua-fib-lab/agentsociety)]

#### Public Survey
- (*AIES'24*) LLM Voting: Human Choices and AI Collective Decision-Making [[paper](https://dl.acm.org/doi/pdf/10.5555/3716662.3716809)] [[code](https://github.com/ethz-coss/LLM_voting)]
- (*SIGSPATIAL'2024*) Urban Mobility Assessment Using LLMs [[paper](https://dl.acm.org/doi/pdf/10.1145/3678717.3691221)] [[code](https://github.com/gmuggs/Urban-Mobility-LLM)]
- (*arXiv'202411*) Generative Agent Simulations of 1,000 People [[paper](https://arxiv.org/pdf/2411.10109)] [[code](https://github.com/joonspk-research/genagents)]

## Trustworthiness of Urban LLM Agents


### Safety
- (*KDD'2023*) Robust Spatiotemporal Traffic Forecasting with Reinforced Dynamic Adversarial Training [[paper](https://arxiv.org/abs/2306.14126)]
- (*arXiv'202306*) Prompt Injection Attack against LLM-Integrated Applications [[paper](https://arxiv.org/abs/2306.05499)]
- (*arXiv'202406*) Adversarial Tuning: Defending Against Jailbreak Attacks for LLMs [[paper](https://arxiv.org/pdf/2406.06622)]ience/article/pii/S2210670724007649)]
- (*PLOS ONE'2015*) Spatiotemporal Detection of Unusual Human Population Behavior Using Mobile Phone Data [[paper](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0120449)]
- (*Signal Processing'2022*) GLOSS: Tensor-Based Anomaly Detection in Spatiotemporal Urban Traffic Data [[paper](https://doi.org/10.1016/j.sigpro.2021.108370)]

### Fairness
- (*Data-Smart City Solutions'2018*) Algorithmic Fairness: Tackling Bias in City Algorithms [[paper]([https://datasmart.ash.harvard.edu/news/article/algorithmic-fairness-tackling-bias-in-city-algorithms](https://datasmart.hks.harvard.edu/news/article/algorithmic-fairness-tackling-bias-city-algorithms))]
- (*NeurIPS'2017*) Counterfactual Fairness [[paper](https://arxiv.org/abs/1703.06856)]
- (*TOIS'2024*) Dynamic Fairness-Aware Recommendation Through Multi-Agent Social Choice [[paper](https://arxiv.org/abs/2303.00968)]

### Accountability
- (*arXiv'202501*) Towards Preventing Overreliance on Task-Oriented Conversational AI Through Accountability Modeling [[paper](https://arxiv.org/pdf/2501.10316)]
- (*arXiv'202504*) Inherent and Emergent Liability Issues in LLM-Based Agentic Systems: A Principal-Agent Perspective [[paper](https://arxiv.org/abs/2504.03255)]


### Privacy
- (*IEEE Communications Magazine'2017*) Security and Privacy in Smart City Applications: Challenges and Solutions [[paper](https://ieeexplore.ieee.org/document/7823349)]
- (*ACM Transactions on Management of Data'2023*) A Neural Approach to Spatio-Temporal Data Release with User-Level Differential Privacy [[paper](https://dl.acm.org/doi/abs/10.1145/3588701)]
- (*arXiv'202210*) Composition of Differential Privacy & Privacy Amplification by Subsampling [[paper](https://arxiv.org/abs/2210.00597)]
- (*CCS'2013*) Geo-Indistinguishability: Differential Privacy for Location-Based Systems [[paper](https://arxiv.org/abs/1212.1984)]
- (*arXiv'202504*) Urban Computing in the Era of Large Language Models [[paper](https://arxiv.org/abs/2504.02009)]

## Performance Evaluation

- (*arXiv'202406*) CityBench: Evaluating the Capabilities of Large Language Model as World Model [[paper](https://arxiv.org/pdf/2406.13945)]
- (*arXiv'202406*) STBench: Assessing the Ability of Large Language Models in Spatio-Temporal Analysis [[paper](https://arxiv.org/pdf/2406.19065)]
- (*AAAI'2025*) UrBench: A Comprehensive Benchmark for Evaluating Large Multimodal Models in Multi-View Urban Scenarios [[paper](https://ojs.aaai.org/index.php/AAAI/article/view/29397)]
- (*OpenReview'2025*) UrbanPlanBench: A Comprehensive Assessment of Urban Planning Abilities in Large Language Models [[paper](https://openreview.net/forum?id=Dl5JaX7zoN)]

