# Awesome-Enterprise-Artificial-Intelligence

# Top Enterprise Artificial Intelligence Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Foundation Models, Agent Orchestration & Enterprise AI Infrastructure*
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Enterprise Artificial Intelligence**. These tools enable organizations to build, deploy, and govern AI applications at scale—from foundation models and agent frameworks to vector databases, RAG pipelines, and enterprise AI governance.

**Examples** include Salesforce Einstein, IBM watsonx, Microsoft Azure AI, Google Cloud Vertex AI, AWS Bedrock, DataRobot, C3 AI, H2O.ai, Palantir AIP, and Dataiku (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom agent orchestration, and open AI infrastructure—ideal for enterprises, ML engineers, and developers seeking transparent, vendor-independent AI solutions.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Salesforce Einstein](https://www.salesforce.com/artificial-intelligence/)**  
  CRM-native AI platform embedded across Sales, Service, Marketing, and Commerce. Features Einstein Prediction Builder for no-code custom AI, Einstein Copilot for conversational assistance, and the Einstein Trust Layer for secure AI governance.

- **[IBM watsonx](https://www.ibm.com/watsonx)**  
  Enterprise AI and data platform with three core components: watsonx.ai (foundation models and studio), watsonx.data (data store), and watsonx.governance (AI governance). Supports both IBM Granite models and open-source models.

- **[Microsoft Azure AI](https://azure.microsoft.com/en-us/products/ai-services/)**  
  Comprehensive AI platform with Azure OpenAI Service, Cognitive Services, and Azure Machine Learning. Features Copilot integration, responsible AI tools, and enterprise-grade security and compliance.

- **[Google Cloud Vertex AI](https://cloud.google.com/vertex-ai)**  
  Unified ML platform for building, deploying, and scaling AI models. Features Vertex AI Studio, Model Garden, and Gemini integration with enterprise-grade MLOps.

- **[AWS Bedrock](https://aws.amazon.com/bedrock/)**  
  Fully managed service for foundation models from leading AI companies. Features model evaluation, guardrails for safe AI, knowledge bases for RAG, and agents for task automation.

- **[DataRobot](https://www.datarobot.com/)**  
  Enterprise AI platform providing a unified experience for developing, delivering, and governing predictive and generative AI. Workbench for experimentation, Registry for model versioning, and Console for deployment monitoring.

- **[C3 AI](https://c3.ai/)**  
  Enterprise AI application platform with pre-built applications for manufacturing, energy, and defense. Features model-driven architecture and AI governance.

- **[H2O.ai](https://h2o.ai/)**  
  Open-source and enterprise AI platform. H2O Python module provides scalable machine learning with AutoML, GLM, Gradient Boosting, and Deep Learning. Enterprise offering adds MLOps and governance.

- **[Palantir AIP](https://www.palantir.com/platforms/aip/)**  
  Enterprise AI platform connecting LLMs to organizational data and operations. Features ontology-driven AI, evaluation tools, and deployment guardrails.

- **[Dataiku](https://www.dataiku.com/)**  
  Enterprise AI platform uniting people, orchestration, and governance. No-code, low-code, and full-code interfaces for analytics, ML, and AI agents. Works across any cloud or infrastructure without vendor lock-in.

## Open-Source GitHub Projects

- **[Open WebUI](https://github.com/open-webui/open-webui)**  
  Enterprise-ready AI interaction interface (license varies) positioning as a zero-code ChatGPT alternative. Features RBAC, encrypted conversation storage, RAG document integration, and Docker one-click deployment with GPU acceleration. Supports Ollama and OpenAI backends .

- **[Dify](https://github.com/langgenius/dify)**  
  Leading open-source LLM app development platform (Apache-2.0 with conditions) with 50k+ GitHub stars. Features drag-and-drop AI workflow builder, hybrid retrieval (BM25 + semantic vector) improving recall by 30%, agentic workflows, RAG pipeline, model management, and observability. Four-layer architecture with Next.js, Flask, Celery, PostgreSQL, and vector store .

- **[RAGFlow](https://github.com/infiniflow/ragflow)**  
  Enterprise-grade knowledge processing engine (Apache-2.0) specializing in complex document parsing. Features DeepDoc engine with OCR, table structure recognition (TSR), and layout analysis to accurately extract merged cells and formulas. Multi-path retrieval combining Elasticsearch keyword search and Infinity vector search with fusion reranking .

- **[n8n](https://github.com/n8n-io/n8n)**  
  Open-source workflow automation platform (Sustainable Use License) with AI capabilities. Features 280+ integrations including Slack, databases, and CRMs. Visual orchestration for approval flows, data sync, and event-driven automation. Can build AI-powered workflows connecting Dify, RAGFlow, and enterprise systems .

- **[Astromesh](https://github.com/monaccode/astromesh)**  
  Multi-model agent runtime and ecosystem (license varies) covering full agent lifecycle. Features six orchestration patterns, Python-first ADK, CLI for node management, cross-platform system installer, visual agent builder (Forge), and cloud-native IaC deployment (Orbit). Docker Compose stack includes Ollama, vLLM, PostgreSQL + pgvector, Redis, Prometheus, and Grafana .

- **[Duxx AI](https://github.com/duxx-ai/duxx-ai)**  
  Enterprise Agentic AI SDK (MIT) unifying agent orchestration, fine-tuning pipelines, enterprise governance, and adaptive model routing. Features graph orchestration (like LangGraph), multi-agent crews (like CrewAI), 14 enterprise agent templates (VirtualCFO, CallCenterAgent, etc.), 40+ tools across 9 domains, and 5-tier memory system .

- **[OpenFoundry](https://github.com/openfoundry/openfoundry)**  
  Multi-agent orchestration framework (MIT) for building and orchestrating AI agents across the full AI lifecycle. Features protocol-based agent interfaces, multi-provider LLM support via LiteLLM, async-first architecture, structured outputs with Pydantic, DAG-based workflow engine, comprehensive guardrails, and full observability with OpenTelemetry and Prometheus .

- **[Agentex (Scale AI)](https://github.com/scaleapi/agentex)**  
  Enterprise-grade framework (license varies) for building, deploying, and managing AI agents at scale. Features long-running asynchronous agents, multi-agent communication, persistent state, and durable workflows via deep Temporal integration. Python SDK, CLI, backend Agent Server, and developer UI. Docker and Kubernetes native .

- **[BeeAI Framework (IBM)](https://github.com/i-am-bee/beeai-framework)**  
  Open-source toolkit (Apache-2.0) for building agents under Linux Foundation governance with 3,000+ GitHub stars. Features multi-agent orchestration, rule-based reasoning, and integrations with leading AI models. Pivoted from end-user focus to developer-first agent construction .

- **[Agent Stack (IBM)](https://github.com/i-am-bee/beeai-platform)**  
  Open infrastructure (Apache-2.0) for fast, framework-agnostic agent deployment built on Agent2Agent (A2A) protocol. Takes agents built anywhere (BeeAI, LangGraph, CrewAI, custom code) and deploys in minutes. Self-hosted server, CLI tools, observability, authorization, and auto-scaling .

- **[Flexible GraphRAG](https://github.com/SemantixRAG/Flexible-GraphRAG)**  
  Open-source AI context platform (license varies) with document processing pipeline, knowledge graph auto-building, ontologies, and hybrid semantic search. Supports 14 data sources, 15 property graph databases, 4 RDF triple stores, 10 vector databases, and OpenSearch/Elasticsearch/BM25. LlamaIndex and LangChain as peer frameworks .

- **[Endee](https://github.com/endee-io/endee)**  
  High-performance open-source vector database (license varies) for semantic search, RAG, and recommendation systems. Focuses on high recall and low latency with significantly reduced memory consumption, enabling deployment on modest hardware. Positions as lightweight alternative to Pinecone, Qdrant, and Milvus .

- **[Khiops](https://github.com/KhiopsML/khiops)**  
  Open-source AutoML suite (BSD 3-Clause-clear) for supervised and unsupervised learning. Features automated feature engineering, model selection, and explainability. Cross-platform wheels for Windows, Linux (x86-64, ARM64), and macOS .

### Additional Strong Open-Source Options

- **[LangGraph](https://github.com/langchain-ai/langgraph)** — Stateful, graph-based agent orchestration (MIT) for multi-step reasoning with human-in-the-loop .
- **[CrewAI](https://github.com/crewAIInc/crewAI)** — Role-based multi-agent collaboration framework (MIT) .
- **[AutoGen (Microsoft)](https://github.com/microsoft/autogen)** — Conversational multi-agent framework (MIT) with code execution .
- **[Prefect](https://github.com/PrefectHQ/prefect)** — Workflow orchestration (Apache-2.0) with native AI task support .
- **[Qdrant](https://github.com/qdrant/qdrant)** — Rust-based vector search engine (Apache-2.0) with filtered ANN and payload filtering .
- **[Milvus](https://github.com/milvus-io/milvus)** — Enterprise-scale vector database (Apache-2.0) for billions of vectors .
- **[Weaviate](https://github.com/weaviate/weaviate)** — Vector database (BSD-3-Clause) with hybrid search and automatic vectorization modules .
- **[Chroma](https://github.com/chroma-core/chroma)** — Developer-favorite embedding database (Apache-2.0) for local development and prototyping .
- **[SemantixRAG](https://github.com/SemantixRAG/SemantixRAG)** — Enterprise RAG platform (license varies) with PII scanning, GraphRAG, observability, and OPA policy engine .
- Community **n8n** workflows for AI orchestration and enterprise automation.

**Frameworks for building custom systems**: Combine **Dify** or **Open WebUI** as the AI application layer with **Astromesh** or **Duxx AI** for agent orchestration, **RAGFlow** or **Flexible GraphRAG** for knowledge retrieval, **Qdrant** or **Endee** for vector storage, and **Agent Stack** for framework-agnostic deployment—creating a fully self-hosted, enterprise-grade AI platform.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Enterprise AI platforms handling sensitive data must comply with data protection regulations (GDPR, CCPA, HIPAA, EU AI Act, etc.).
- Self-hosted open-source solutions require proper security hardening, GPU provisioning, model governance, and ongoing maintenance. The performance gap between open-source and proprietary models has collapsed to 0.3% on key benchmarks, making self-hosting viable for many enterprise use cases .

---

**Made for ML engineers, AI platform teams, enterprise architects, and developers building transparent AI solutions.**
Let's make Enterprise Artificial Intelligence more open, data-driven, and accessible.
