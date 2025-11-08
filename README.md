# Awesome Agent Memory
A curated list of projects on **memory systems of AI agents**.

## Comparing Different Designs

* **[AI Agent Memory Playground](https://github.com/AIAnytime/Agent-Memory-Playground)** – An interactive **evaluation suite** for 9 memory strategies (sequential, retrieval, hierarchical, decay-based, etc.). Includes simulation environment and plots for **token–recall trade-offs** and **forgetting dynamics**. 

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

* **[Nemori](https://github.com/nemori-ai/nemori)** – Self-organising long-term memory substrate for agentic LLM workflows. Nemori segments multi-turn conversations into topic-consistent episodes, distils durable semantic knowledge, and exposes a unified search surface for downstream reasoning. The system uses insights from Event Segmentation Theory and predictive processing and provides production-ready concurrency, caching and pluggable storage options.

* **[ReMe (Agentscope)](https://github.com/agentscope-ai/ReMe)** – *Remember Me, Refine Me.* A modular **memory management kit** that unifies personal, task, and tool memories for agents. Features **refinement cycles**, **temporal prioritization**, and **Pydantic-backed schemas** to ensure memory coherence and relevance. 

* **[Memori (GibsonAI)](https://github.com/GibsonAI/memori)** – **Open-source memory engine** for LLMs and agents with *entity extraction, auto-categorization, memory promotion, and multi-agent sync.* Supports **temporal retention policies**, **retrieval tuning**, and **cross-agent context exchange**. 

* **[OpenMemory Engine](https://github.com/CaviraOSS/OpenMemory)** – Self-hosted, **sectorized semantic memory engine** with hierarchical storage, **auto decay**, and **explainable recall graphs**; integrates with LangGraph, Mem0, and MCP tools.

* **[Task Memory Engine (TME)](https://github.com/biubiutomato/TME-Agent)** – Structured **task-level memory engine** combining **hierarchical trees** and **rollback-aware buffers** to track multi-step reasoning; enables **state reconstruction and planning** with minimal context tokens. 

## Reinforcement-Learning Training for Agent Memory

* **[MemAgent](https://github.com/BytedTsinghua-SIA/MemAgent)** – RL-trained long-context agent with a **memory mechanism** that enables arbitrarily long inputs within fixed windows; **RLVR-based** training and **linear-time** scaling, shown to extrapolate to **multi-million-token** tasks with minimal loss.

* **[MEM1](https://github.com/MIT-MI/MEM1)** – End-to-end RL that learns a **compact internal state** for **constant-memory** long-horizon agents; integrates new observations while discarding redundancy to improve efficiency.

* **[Memento](https://github.com/Agent-on-the-Fly/Memento)** – **Memory-based online RL** over a **memory-augmented MDP** with a **neural case-selection** policy; planner–executor loop reuses past trajectories so agents **learn without fine-tuning** the base LLM.

* **[Memory-R1](https://arxiv.org/abs/2508.19828)** – the paper (*code not yet publicly available*) proposes an RL framework where a Memory Manager learns to add, update or delete memory entries and an Answer Agent learns to select relevant entries. Both agents are trained with PPO and GRPO to actively manage and utilise an external memory bank.

* **[Mem-α](https://arxiv.org/abs/2509.25911)** – RL framework that teaches agents how to build and manage complex memory systems through interaction and feedback. Agents process sequential information, learn to extract and store relevant content, and update core/episodic/semantic memory components; rewards derive from downstream question-answering accuracy.

## MCP-Centric Memory Servers & Tools

* **[Basic Memory](https://github.com/basicmachines-co/basic-memory)** – **Local-first Markdown** knowledge base exposed via MCP; bi-directional human/LLM editing with simple, file-backed persistence.

* **[OpenMemory MCP](https://mem0.dev/openmemory)** – Mem0’s **local-only** MCP server that centralizes cross-tool memory with a unified dashboard.

* **[Memory MCP Server (Swift)](https://github.com/okooo5km/memory-mcp-server)** – Lightweight MCP server for **entity/relation** memory graphs with JSON storage and a simple CLI.

* **[memory (HamzaFarhan)](https://github.com/HamzaFarhan/memory)** – Minimal **knowledge-graph** MCP server (entities/relations/observations) with JSON persistence and flexible search modes.

* **[mcp-memory (Puliczek)](https://github.com/Puliczek/mcp-memory)** – Cloudflare-backed MCP memory with **D1 + vector search**, namespaces, and rate-limited, TLS-secured endpoints.

* **[memory-mcp (JamesANZ)](https://github.com/JamesANZ/memory-mcp)** – MCP memory for **conversation logging**, **context-window caching**, relevance scoring, and MongoDB storage.

* **[MCP Memory Service (doobidoo)](https://github.com/doobidoo/mcp-memory-service)** – **Universal MCP** memory with **semantic search**, natural-language time filters, and storage options (SQLite-vec/Chroma/Cloudflare).

* **[Supermemory MCP](https://supermemory.ai/blog/how-to-make-your-mcp-clients-share-context-with-supermemory-mcp/)** – **Graph memory service** implementing **MCP context sharing**, **cross-app recall**, and **relationship graphs** for multi-agent sessions.

* **[MCP-Titan](https://github.com/henryhawke/mcp-titan)** – Experimental **neural memory engine** integrating **online vector processing** and **TensorFlow.js learning loops**, enabling live memory update and auto-retention control. 


* **[Redis Agent Memory Server](https://github.com/redis/agent-memory-server)** – Redis-powered memory with **REST + MCP**, **two-tier memory** (session/long-term), configurable extraction, and pluggable vector backends.

## Memory Modules in Existing Agent Frameworks

* **[LangMem (LangChain/LangGraph)](https://github.com/langchain-ai/langmem)** – SDK that gives agents **long-term, semantic memory** with tools to **store/search** memories in LangGraph stores, plus a managed service and templates.

* **[LangGraph + MongoDB Store](https://www.mongodb.com/company/blog/product-release-announcements/powering-long-term-memory-for-agents-langgraph)** – Introduces a **persistent document memory layer** for LangGraph, combining **vector and document stores** for scalable long-term retention.

* **[LlamaIndex – Agent Memory](https://docs.llamaindex.ai/en/stable/module_guides/deploying/agents/memory/)** – Unified APIs for **short- and long-term memory**, including **composable memory** so agents can combine multiple sources. Recent updates improve long/short-term blocks.

* **[Microsoft Semantic Kernel – Memory Plugin](https://www.nuget.org/packages/Microsoft.SemanticKernel.Plugins.Memory)** – Embeddings-based **memory plugin** (e.g., `TextMemoryPlugin`) to **save/recall** short/long-term info across agents in .NET/JS/py SK apps.

* **[Microsoft AutoGen – Memory](https://microsoft.github.io/autogen/stable//user-guide/agentchat-user-guide/memory.html)** – Provides a **Memory protocol** (e.g., `ListMemory`) and official notebooks showing **long-term memory with Zep** and **Mem0** in conversational agents.

* **[Hugging Face smolagents – Memory](https://huggingface.co/docs/smolagents/en/tutorials/memory)** – Exposes a first-class **agent memory** you can **inspect/replay/modify**; supports step callbacks for dynamic memory policies.

* **[CrewAI – Memory](https://docs.crewai.com/concepts/memory)** – Adds **short-term (RAG)** and **long-term** stores (e.g., SQLite backed) so crews **retain insights across executions** and reuse them later.

## Contributing

Contributions are welcome! If a project belongs here, open an issue or PR with:

* Name + link
* One-to-two sentence description
* A unique feature or highlight (e.g., storage model, retrieval strategy, tooling, compliance)
* License and ecosystem (LangGraph, SK, AutoGen, MCP, etc.)
