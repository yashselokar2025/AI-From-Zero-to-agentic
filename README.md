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
| **2024** | [MegaScale: Scaling Large Language Model Training to More Than 10,000 GPUs]() | NSDI '24 | *Architecture considerations for robust AWS cloud training.* |
| **2024** | [NeMo-Aligner: Scalable Toolkit for Efficient Model Alignment]() | ArXiv | *Insights for fine-tuning open-source models.* |
| **2023** | [ZeRO: Memory Optimizations Toward Training Trillion Parameter Models]() | SC '20 | *Core foundation for understanding distributed memory.* |
| **2023** | [Oobleck: Resilient Distributed Training of Large Models Using Pipeline Templates]() | SOSP '23 | |

### 2. LLM Inference & Serving Systems
*Research on low-latency, high-throughput model serving (vLLM, Continuous Batching, PagedAttention).*

| Year | Title / Link | Venue | My Notes / Project Relevance |
| :--- | :--- | :--- | :--- |
| **2023** | [Efficient Memory Management for LLM Serving with PagedAttention (vLLM)]() | SOSP '23 | *Crucial for reducing latency in real-time apps like MockMentor AI.* |
| **2023** | [Orca: A Distributed Serving System for Transformer-Based Generative Models]() | OSDI '22 | *Continuous batching concepts.* |
| **2024** | [Speculative Decoding: Fast Inference from Large Language Models]() | ICML '23 | |

### 3. Retrieval-Augmented Generation (RAG) & Vector Systems
*Optimizing vector search, context scaling, and retrieval frameworks.*

| Year | Title / Link | Venue | My Notes / Project Relevance |
| :--- | :--- | :--- | :--- |
| **2023** | [Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks]() | NeurIPS | *The foundational RAG paper.* |
| **2024** | [Lost in the Middle: How Language Models Use Long Contexts]() | TACL | *Helped refine chunking strategies for document retrieval.* |
| **2024** | [Self-RAG: Learning to Retrieve, Generate, and Critique through Self-Reflection]() | ICLR '24 | *Exploring this for advanced Agentic RAG loops.* |

### 4. Agentic & Multi-Modal Frameworks
*Research powering autonomous agents, tool use, and multi-modal integrations.*

| Year | Title / Link | Venue | My Notes / Project Relevance |
| :--- | :--- | :--- | :--- |
| **2023** | [ReAct: Synergizing Reasoning and Acting in Language Models]() | ICLR '23 | *Core methodology used in building LangGraph agents.* |
| **2024** | [AutoGen: Enabling Next-Gen LLM Applications via Multi-Agent Conversation]() | ArXiv | *Comparing A2A patterns with MCP.* |
| **2024** | [Video-LLaVA: Learning United Visual Representation by Alignment Before Projection]() | ArXiv | *Concepts directly applicable to the CCTV AI Pipeline.* |

### 5. Industrial LLM Technical Reports
*Major architecture disclosures from leading AI labs.*

| Year | Report Title / Link | Org | My Notes / Project Relevance |
| :--- | :--- | :--- | :--- |
| **2024** | [DeepSeek-V3 Technical Report]() | DeepSeek | *Analyzing Mixture of Experts (MoE) efficiency.* |
| **2024** | [The Llama 3 Herd of Models]() | Meta | |
| **2024** | [Qwen Technical Report]() | Alibaba | |

---

## 🛠️ Tech Stack & Tools
**Languages:** Python, SQL  
**Data & ML:** NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn  
**AI Frameworks:** LangChain, LangGraph  
**MLOps & Backend:** MLflow, FastAPI  
**Infrastructure:** Vector Databases, AWS 

## 💡 How to Use This Repo
Feel free to explore the code, copy the architectures, or read through the curated paper list. If you find a paper or a framework that fits well into these categories, feel free to open a Pull Request!

*This repository combines rigorous academic theory, practical implementation, and system-level thinking to build the next generation of AI.*
