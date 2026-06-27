# 🚀 AI From Zero to Agentic: The Complete Engineering & Research Hub

> **Maintainer:** Yash Gopal Selokar
> **Status:** 🚧 Actively evolving — new notebooks, architectures, experiments, and research papers are added regularly.

Welcome to my learning hub, reference notebook, and research archive. This repository documents an end-to-end journey in Artificial Intelligence, starting from core machine learning concepts and progressing towards advanced LLM systems, RAG architectures, Agentic AI workflows, MLOps, and scalable cloud infrastructure.

It bridges the gap between **academic theory, system-level design, and production-ready implementation.**

### 🔗 Quick Reference Resources
*   [101 Gen AI Cheat Sheets (Medium)](https://medium.com/@anushka.datascoop/101-gen-ai-cheat-sheets-831e17f1e6a7)
*   [MIT Lecture 2: RNNs and Transformers (Notion)](https://dair-ai.notion.site/Lecture-2-Recurrent-Neural-Networks-and-Transformers-71fb3ba2a24f4b6c8cc77281fc19cfab)

---

## 📌 Part 1: Domain Knowledge & Lab Archives
This section contains structured notes, hands-on notebooks, and architectural design patterns.

### 🔹 Core Machine Learning & Deep Learning
*   **Math & Stats:** Linear & Polynomial Regression, Bias–Variance Tradeoff, Evaluation Metrics (MSE, R², ROC, AUC).
*   **Data Processing:** Feature Scaling & Normalization, EDA, Pandas, NumPy, Matplotlib, Seaborn.
*   **Deep Learning:** MIT Deep Learning Lecture Notes, Model Formats, Model Tracing & Deployment.

### 🔹 Large Language Models (LLMs) & MLOps
*   **Training & Tuning:** Fine-tuning LLMs, PEFT, and LoRA.
*   **Evaluation:** LLM Evaluation & Observability (Langfuse, MLflow).
*   **Ops & Cloud:** MLflow Tracking, Model Registry, FastAPI Deployment, AWS Roadmap for AI/ML.
*   **Prompting:** Prompt Management & Lifecycle Versioning.

### 🔹 RAG & Agentic AI Systems
*   **RAG:** Architectures & Design Patterns, Chunking Strategies, Re-rankers, Vector Databases, Query Resolution.
*   **Agents:** Agentic AI Design Patterns, Multi-Agent Systems (LangGraph), Agentic RAG.
*   **Protocols:** Model Context Protocol (MCP) Client–Server implementations, A2A (Agent-to-Agent) vs. MCP.

---

## 🏗️ Part 2: Applied Projects & Implementations
*Theory applied to real-world software engineering:*

*   **MockMentor AI:** An intelligent interview simulation system integrating real-time coding evaluation, voice interaction, and agentic reasoning.
*   **CCTV AI Pipeline:** A highly complex video data ingestion and querying architecture allowing users to interact with physical security feeds via a conversational LLM chatbot.
*   **Smart Admission & DIMS:** Web-based tracking and data management applications optimized for high-throughput institutional use.

---

## 📚 Part 3: Awesome LLM Systems Paper List

> **🌟 Acknowledgments & Original Source:** 
> The comprehensive categorization and structural baseline of this research archive are heavily inspired by and adapted from the phenomenal work by **[AmberLJC/LLMSys-PaperList](https://github.com/AmberLJC/LLMSys-PaperList)**. Please visit and star the original repository for their master list.

This section tracks the bleeding-edge research papers and technical reports that inform the architectures built in this repository. I have added a "My Notes" column to track how these papers apply to my personal projects.

### 1. LLM Training Systems
*Techniques for scaling pre-training, fine-tuning, and alignment across massive GPU clusters.*

| Year | Title / Link | Venue | My Notes / Project Relevance |
| :--- | :--- | :--- | :--- |
| **2024** | [MegaScale: Scaling Large Language Model Training to More Than 10,000 GPUs](https://arxiv.org/abs/2402.15627) | NSDI '24 | *Architecture considerations for robust AWS cloud training.* |
| **2024** | [NeMo-Aligner: Scalable Toolkit for Efficient Model Alignment](https://arxiv.org/abs/2405.01481) | ArXiv | *Insights for fine-tuning open-source models.* |
| **2020** | [ZeRO: Memory Optimizations Toward Training Trillion Parameter Models](https://arxiv.org/abs/1910.02054) | SC '20 | *Core foundation for understanding distributed memory.* |
| **2023** | [Oobleck: Resilient Distributed Training of Large Models Using Pipeline Templates](https://dl.acm.org/doi/10.1145/3600006.3613152) | SOSP '23 | |

### 2. LLM Inference & Serving Systems
*Research on low-latency, high-throughput model serving (vLLM, Continuous Batching, PagedAttention).*

| Year | Title / Link | Venue | My Notes / Project Relevance |
| :--- | :--- | :--- | :--- |
| **2023** | [Efficient Memory Management for LLM Serving with PagedAttention (vLLM)](https://arxiv.org/abs/2309.06180) | SOSP '23 | *Crucial for reducing latency in real-time apps like MockMentor AI.* |
| **2022** | [Orca: A Distributed Serving System for Transformer-Based Generative Models](https://www.usenix.org/conference/osdi22/presentation/yu) | OSDI '22 | *Continuous batching concepts.* |
| **2023** | [Fast Inference from Transformers via Speculative Decoding](https://arxiv.org/abs/2211.17192) | ICML '23 | |

### 3. Retrieval-Augmented Generation (RAG) & Vector Systems
*Optimizing vector search, context scaling, and retrieval frameworks.*

| Year | Title / Link | Venue | My Notes / Project Relevance |
| :--- | :--- | :--- | :--- |
| **2020** | [Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks](https://arxiv.org/abs/2005.11401) | NeurIPS | *The foundational RAG paper.* |
| **2023** | [Lost in the Middle: How Language Models Use Long Contexts](https://arxiv.org/abs/2307.03172) | TACL | *Helped refine chunking strategies for document retrieval.* |
| **2024** | [Self-RAG: Learning to Retrieve, Generate, and Critique through Self-Reflection](https://arxiv.org/abs/2310.11511) | ICLR '24 | *Exploring this for advanced Agentic RAG loops.* |

### 4. Agentic & Multi-Modal Frameworks
*Research powering autonomous agents, tool use, and multi-modal integrations.*

| Year | Title / Link | Venue | My Notes / Project Relevance |
| :--- | :--- | :--- | :--- |
| **2023** | [ReAct: Synergizing Reasoning and Acting in Language Models](https://arxiv.org/abs/2210.03629) | ICLR '23 | *Core methodology used in building LangGraph agents.* |
| **2023** | [AutoGen: Enabling Next-Gen LLM Applications via Multi-Agent Conversation](https://arxiv.org/abs/2308.08155) | ArXiv | *Comparing A2A patterns with MCP.* |
| **2023** | [Video-LLaVA: Learning United Visual Representation by Alignment Before Projection](https://arxiv.org/abs/2311.10122) | ArXiv | *Concepts directly applicable to the CCTV AI Pipeline.* |

### 5. Industrial LLM Technical Reports
*Major architecture disclosures from leading AI labs.*

| Year | Report Title / Link | Org | My Notes / Project Relevance |
| :--- | :--- | :--- | :--- |
| **2024** | [DeepSeek-V3 Technical Report](https://arxiv.org/abs/2412.19437) | DeepSeek | *Analyzing Mixture of Experts (MoE) efficiency.* |
| **2024** | [The Llama 3 Herd of Models](https://arxiv.org/abs/2407.09298) | Meta | |
| **2023** | [Qwen Technical Report](https://arxiv.org/abs/2309.16609) | Alibaba | |

---
# ML Systems
## SOSP 25

* [LithOS: An Operating System for Efficient Machine Learning on GPUs](https://sigops.org/s/conferences/sosp/2025/accepted.html)
* [PhoenixOS: Concurrent OS-level GPU Checkpoint and Restore with Validated Speculation](https://sigops.org/s/conferences/sosp/2025/accepted.html)
* [SAND: A New Programming Abstraction for Video-based Deep Learning](https://sigops.org/s/conferences/sosp/2025/accepted.html)

## OSDI 25

* [KPerfIR: Towards an Open and Compiler‑centric Ecosystem for GPU Kernel Performance Tooling on Modern AI Workloads](https://arxiv.org/abs/2505.21661)
* [Mirage: A Multi‑Level Superoptimizer for Tensor Programs](https://arxiv.org/abs/2405.05751)
* [Neutrino: Fine‑grained GPU Kernel Profiling via Programmable Probing](https://www.usenix.org/conference/osdi25/presentation/songlin‑huang)
* [TrainCheck: Training with Confidence – Catching Silent Errors in Deep Learning Training](https://www.usenix.org/conference/osdi25/presentation/jiang)
* [QiMeng‑Xpiler: Transcompiling Tensor Programs via LLM‑assisted Neural‑Symbolic Synthesis**](https://arxiv.org/abs/2505.02146) 
* [WaferLLM: A Wafer‑Scale LLM Inference System](https://arxiv.org/abs/2502.04563)  
* [BlitzScale: Fast and Live Large Model Autoscaling with O(1) Host Caching](https://arxiv.org/abs/2412.17246)  
* [Bayesian Code Diffusion for Efficient Automatic Deep Learning Program Optimization](https://www.usenix.org/system/files/osdi25-jeong.pdf) 


 


## From Earlier Years
- [INFaaS](https://www.usenix.org/conference/atc21/presentation/romero): Automated Model-less Inference Serving | ATC’ 21
- [Alpa](https://arxiv.org/abs/2201.12023) : Automating Inter- and Intra-Operator Parallelism for Distributed Deep Learning | OSDI' 22
- [Pathways](https://proceedings.mlsys.org/paper/2022/hash/98dce83da57b0395e163467c9dae521b-Abstract.html) : Asynchronous Distributed Dataflow for ML | MLSys' 22
- [AlpaServe](https://arxiv.org/pdf/2302.11665.pdf): Statistical Multiplexing with Model Parallelism for Deep Learning Serving
- [DeepSpeed-MoE](https://arxiv.org/abs/2201.05596): Advancing Mixture-of-Experts Inference and Training to Power Next-Generation AI Scale ICML' 2022.
- [ZeRO-Offload](https://www.usenix.org/conference/atc21/presentation/ren-jie) : Democratizing Billion-Scale Model Training. 
- [ZeRO-Infinity](https://arxiv.org/pdf/2104.07857) : Breaking the GPU Memory Wall for Extreme Scale Deep Learning  
- [ZeRO](https://arxiv.org/abs/1910.02054) : memory optimizations toward training trillion parameter models.  
- [Band](https://dl.acm.org/doi/pdf/10.1145/3498361.3538948): Coordinated Multi-DNN Inference on Heterogeneous Mobile Processors | MobiSys ’22
- [Serving Heterogeneous Machine Learning Models on Multi-GPU Servers with Spatio-Temporal Sharing](https://www.usenix.org/conference/atc22/presentation/choi-seungbeom) | ATC'22
- [Fast and Efficient Model Serving Using Multi-GPUs with Direct-Host-Access](https://dl.acm.org/doi/pdf/10.1145/3552326.3567508) | Eurosys'23
- [Cocktail](https://www.usenix.org/system/files/nsdi22-paper-gunasekaran.pdf): A Multidimensional Optimization for Model Serving in Cloud | NSDI'22
- [Merak](https://arxiv.org/abs/2206.04959): An Efficient Distributed DNN Training Framework with Automated 3D Parallelism for Giant Foundation Models
- [SHEPHERD](https://www.usenix.org/system/files/nsdi23-zhang-hong.pdf) : Serving DNNs in the Wild
- [Efficient GPU Kernels for N:M-Sparse Weights in Deep Learning](https://proceedings.mlsys.org/paper_files/paper/2023/file/4552cedd396a308320209f75f56a5ad5-Paper-mlsys2023.pdf)
- [AutoScratch](https://proceedings.mlsys.org/paper_files/paper/2023/file/627b5f83ffa130fb33cb03dafb47a630-Paper-mlsys2023.pdf): ML-Optimized Cache Management for Inference-Oriented GPUs
- [ZeRO++](https://arxiv.org/abs/2306.10209): Extremely Efficient Collective Communication for Giant Model Training
- [Channel Permutations for N:M Sparsity](https://proceedings.neurips.cc/paper/2021/hash/6e8404c3b93a9527c8db241a1846599a-Abstract.html) | MLSys' 23
- [Welder](https://www.usenix.org/conference/osdi23/presentation/shi) : Scheduling Deep Learning Memory Access via Tile-graph | OSDI' 23
- [Optimizing Dynamic Neural Networks with Brainstorm](https://www.usenix.org/conference/osdi23/presentation/cui) | OSDI'23
- [ModelKeeper](https://www.usenix.org/conference/nsdi23/presentation/lai-fan): Accelerating DNN Training via Automated Training Warmup | NSDI'23
- [Breadth-First Pipeline Parallelism](https://proceedings.mlsys.org/paper_files/paper/2023/file/14bc46029b7ac590f56a203e0a3ef586-Paper-mlsys2023.pdf) | MLSys' 23
- [MGG](https://www.usenix.org/system/files/osdi23-wang-yuke.pdf) : Accelerating Graph Neural Networks with Fine-Grained Intra-Kernel Communication-Computation Pipelining on Multi-GPU Platforms | OSDI' 23
- [Hydro](https://www.usenix.org/system/files/osdi23-hu.pdf): Surrogate-Based Hyperparameter Tuning Service in Datacenters | OSDI' 23
- [Cocktailer](https://www.usenix.org/system/files/osdi23-zhang-chen.pdf): Analyzing and Optimizing Dynamic Control Flow in Deep Learning | OSDI' 23
- [BPipe](https://proceedings.mlr.press/v202/kim23l/kim23l.pdf): Memory-Balanced Pipeline Parallelism for TrainingLarge Language Models
- [Exploring GPU-to-GPU Communication: Insights into Supercomputer Interconnects](https://arxiv.org/abs/2408.14090)
- [Revisiting Reliability in Large-Scale Machine Learning Research Clusters](https://arxiv.org/abs/2410.21680)
- [Orion](https://dl.acm.org/doi/10.1145/3627703.3629578): Interference-aware, Fine-grained GPU Sharing for ML Applications | EuroSys '24
- [Optimus](https://dl.acm.org/doi/10.1145/3627703.3629567): Warming Serverless ML Inference via Inter-Function Model Transformation | EuroSys '24
- [Model Selection for Latency-Critical Inference Serving](https://dl.acm.org/doi/10.1145/3627703.3629565) | EuroSys '24
- [Apparate](https://arxiv.org/abs/2312.05385): Rethinking Early Exits to Tame Latency-Throughput Tensions in ML Serving | SOSP' 24
- [Usher](https://www.usenix.org/system/files/osdi24-shubha.pdf): Holistic Interference Avoidance for Resource Optimized ML Inference | OSDI' 24


## 🛠️ Tech Stack & Tools
**Languages:** Python, SQL  
**Data & ML:** NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn  
**AI Frameworks:** LangChain, LangGraph  
**MLOps & Backend:** MLflow, FastAPI  
**Infrastructure:** Vector Databases, AWS 

## 💡 How to Use This Repo
Feel free to explore the code, copy the architectures, or read through the curated paper list. If you find a paper or a framework that fits well into these categories, feel free to open a Pull Request!

*This repository combines rigorous academic theory, practical implementation, and system-level thinking to build the next generation of AI.*


**Maintained by Yash Selokar**
--
**New Trending Technology Coming Soon**
