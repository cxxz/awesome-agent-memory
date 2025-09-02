# Awesome Agent Memory

A curated list of open-source projects building **memory systems for AI agents**. Each entry highlights what makes it stand out.

## Standalone Libraries / Frameworks for Bulding Agent Memory System

* **[Letta (formerly MemGPT)](https://github.com/letta-ai/letta)** – Platform for building **stateful agents** with built-in persistence, “infinite context” orchestration, and an **Agent File (.af)** format to serialize an agent’s memory/behavior for sharing & versioning. 

* **[Mem0](https://github.com/mem0ai/mem0)** – “Universal memory layer” that manages **short-/long-term, semantic, and episodic** memories; ships **OpenMemory MCP** for local-first, cross-app memory with a UI (topics/emotions/timestamps). 

* **[MemU](https://github.com/NevaMind-AI/memU)** – Memory framework for AI companions focused on **high-accuracy retrieval** at **low cost**, with a simple “memory folder” abstraction and active development. 

* **[A-Mem (Agentic Memory)](https://github.com/agiresearch/A-mem)** – Research + code toward **agentic memory operations** (create, link, revise) inspired by note-taking systems; open implementations available. 

* **[MemEngine](https://github.com/nuster1128/MemEngine)** – **Unified, modular library** implementing **many memory models** under one framework; offers local/remote deployment and **automatic selection** of memory configs. 

* **[memonto](https://github.com/shihanwan/memonto)** – **Knowledge-graph memory** that extracts entities/relations into an ontology and exposes **graph queries** (and an MCP server variant) for semantic recall. 

* **[Zep](https://github.com/getzep/zep)** – **Context engineering** platform that builds a **temporal knowledge graph** over chat + business data; HIPAA-capable service with LangChain/LlamaIndex integrations & SDKs. 


## Memory Modules in Existing Agent Frameworks

* **[LangMem (LangChain/LangGraph)](https://github.com/langchain-ai/langmem)** – SDK that gives agents **long-term, semantic memory** with tools to **store/search** memories in LangGraph stores, plus a managed service and templates. 

* **[LlamaIndex – Agent Memory](https://docs.llamaindex.ai/en/stable/module_guides/deploying/agents/memory/)** – Unified APIs for **short- and long-term memory**, including **composable memory** so agents can combine multiple sources. Recent updates improve long/short-term blocks. 

* **[Microsoft Semantic Kernel – Memory Plugin](https://www.nuget.org/packages/Microsoft.SemanticKernel.Plugins.Memory)** – Embeddings-based **memory plugin** (e.g., `TextMemoryPlugin`) to **save/recall** short/long-term info across agents in .NET/JS/py SK apps. 

* **[Microsoft AutoGen – Memory](https://microsoft.github.io/autogen/stable//user-guide/agentchat-user-guide/memory.html)** – Provides a **Memory protocol** (e.g., `ListMemory`) and official notebooks showing **long-term memory with Zep** and **Mem0** in conversational agents. 

* **[Hugging Face smolagents – Memory](https://huggingface.co/docs/smolagents/en/tutorials/memory)** – Exposes a first-class **agent memory** you can **inspect/replay/modify**; supports step callbacks for dynamic memory policies. 

* **[CrewAI – Memory](https://docs.crewai.com/concepts/memory)** – Adds **short-term (RAG)** and **long-term** stores (e.g., SQLite-backed) so crews **retain insights across executions** and reuse them later. 


## Contributing

Contributions are welcome! If a project belongs here, open an issue or PR with:

* Name + link
* One-to-two sentence description
* A unique feature or highlight (e.g., storage model, retrieval strategy, tooling, compliance)
* License and ecosystem (LangGraph, SK, AutoGen, MCP, etc.)

