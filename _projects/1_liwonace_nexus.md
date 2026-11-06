---
layout: page
title: Liwonace Nexus
description: On-premise MCP-based intelligent data search platform
logo: /assets/img/projects/liwonace.svg
importance: 1
category: work
github: https://github.com/qixiangme/liwonace-nexus
---

**[Liwonace](https://liwonace.co.kr/) · 2026 · Kotlin/Spring AI, Go, React, PostgreSQL + pgvector, Ollama**

Natural-language search over internal documents, relational data, and a knowledge graph — fully on-premise, no external AI API.
Data access is exposed as [MCP](https://modelcontextprotocol.io/) tools; the agent routes each question to document search, NL2SQL, or graph traversal and returns the answer with the tools used, sources, and latency.

- Top-2 finalist, Corporate Designated Task (Liwonace), Open Source Developer Competition 2026 (MSIT/NIPA); grand-prize evaluation in progress
- Ported agent + MCP server from Spring AI to Go and benchmarked both: 100% routing / answer accuracy on 302 questions, Go at ~1/11 the resources
- Fixed answerability gate, KG search, and SQL planner bugs: accuracy 40% → 90% → 100%

[GitHub](https://github.com/qixiangme/liwonace-nexus)
