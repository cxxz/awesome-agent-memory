# Awesome Agent Memory

A curated list of open-source projects building **memory systems for AI agents**. Each entry highlights what makes it stand out.

## Standalone Libraries / Frameworks for Building Agent Memory Systems

* **[Letta (formerly MemGPT)](https://github.com/letta-ai/letta)** – Memory hierarchy with editable **memory blocks**, agentic context tools, **multi-agent shared memory**, and portable **Agent File (.af)** snapshots.

* **[Mem0](https://github.com/mem0ai/mem0)** – “Universal memory layer” for short/long-term + semantic/episodic memory, with a **local-first dashboard** and broad framework integrations.

* **[MemU](https://github.com/NevaMind-AI/memU)** – Companion-focused memory that **organizes/links/evolves** memories, adds **adaptive forgetting**, and emphasizes accuracy + cost efficiency.

* **[A-Mem (Agentic Memory)](https://github.com/agiresearch/A-mem)** – Zettelkasten-style **create/link/revise** operations with **ChromaDB** indexing and automatic memory evolution.

* **[MemEngine](https://github.com/nuster1128/MemEngine)** – **Unified, modular** library with many pluggable memory models and automatic config selection for local/remote runs.

* **[memonto](https://github.com/shihanwan/memonto)** – **Ontology/knowledge-graph** memory that extracts entities/relations and exposes **graph queries**; can run ephemeral or persist to triple/vector stores.

* **[Zep](https://github.com/getzep/zep)** – **Temporal knowledge graph** memory (Graphiti engine) with **bi-temporal facts** and **hybrid retrieval** (graph + semantic + keyword).

* **[Persistent AI Memory System](https://github.com/Savantskie/persistent-ai-memory)** – Persistent, searchable memory plus **tool-usage logs**, deduping/self-reflection, and cross-conversation sync.

* **[Agno](https://github.com/agno-agi/agno)** – Full-stack multi-agent framework with built-in **Storage/Memory drivers**, small footprint, and fast **stateful** agents.

* **[MemoryOS](https://github.com/BAI-LAB/MemoryOS)** – **OS-like** memory stack with short/mid/long-term layers and plug-and-play storage/retrieval; exportable via tools.

* **[Memary](https://github.com/kingjulio8238/Memary)** – Human-memory-inspired layer with **persona-aware** graphs and **multi-graph** support (FalkorDB/Neo4j; local or hosted LLMs).

* **[Cognee](https://github.com/topoteretes/cognee)** – Extract-Cognify-Load pipeline that turns conversations/files into **graph + vector** memory to **replace/augment RAG** with relationship-aware recall.

## MCP-Centric Memory Servers & Tools

* **[Basic Memory](https://github.com/basicmachines-co/basic-memory)** – **Local-first Markdown** knowledge base exposed via MCP; bi-directional human/LLM editing with simple, file-backed persistence.

* **[OpenMemory MCP](https://mem0.dev/openmemory)** – Mem0’s **local-only** MCP server that centralizes cross-tool memory with a unified dashboard.

* **[Memory MCP Server (Swift)](https://github.com/okooo5km/memory-mcp-server)** – Lightweight MCP server for **entity/relation** memory graphs with JSON storage and a simple CLI.

* **[memory (HamzaFarhan)](https://github.com/HamzaFarhan/memory)** – Minimal **knowledge-graph** MCP server (entities/relations/observations) with JSON persistence and flexible search modes.

* **[mcp-memory (Puliczek)](https://github.com/Puliczek/mcp-memory)** – Cloudflare-backed MCP memory with **D1 + vector search**, namespaces, and rate-limited, TLS-secured endpoints.

* **[memory-mcp (JamesANZ)](https://github.com/JamesANZ/memory-mcp)** – MCP memory for **conversation logging**, **context-window caching**, relevance scoring, and MongoDB storage.

* **[MCP Memory Service (doobidoo)](https://github.com/doobidoo/mcp-memory-service)** – **Universal MCP** memory with **semantic search**, natural-language time filters, and storage options (SQLite-vec/Chroma/Cloudflare).

* **[Redis Agent Memory Server](https://github.com/redis/agent-memory-server)** – Redis-powered memory with **REST + MCP**, **two-tier memory** (session/long-term), configurable extraction, and pluggable vector backends.


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

