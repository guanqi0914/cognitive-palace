# CognitivePalace: Self-Evolution Framework for Autonomous AI Agents

An experience-driven self-evolution framework that enables AI agents to learn from feedback, standardize recurring processes, and improve task execution over time.

## Architecture

```
┌─────────────────────────────────────────────┐
│            BM25 Retrieval Engine            │
│  Full-text search over accumulated memory   │
└─────────────────────────────────────────────┘
                     ↓
┌─────────────────────────────────────────────┐
│        SOP Standardization System           │
│  4 categories: hot/content/interact/research│
└─────────────────────────────────────────────┘
                     ↓
┌─────────────────────────────────────────────┐
│          Self-Improvement Loop              │
│  Corrections → Domain Files → Behavior      │
└─────────────────────────────────────────────┘
                     ↓
┌─────────────────────────────────────────────┐
│          Continuous Research Engine         │
│  48h cycle:调研 → 分析 → 入库              │
└─────────────────────────────────────────────┘
```

## Key Features

- **BM25 Retrieval**: Native BM25 implementation, no external dependencies
- **SOP Templates**: Standardized workflows for recurring tasks
- **Correction Handling**: 3-layer system (input → validation → integration)
- **MCP Server**: 11 tools exported for cross-platform integration
- **48h Research Cycle**: Continuous learning from external sources

## Installation

```bash
git clone https://github.com/guanqi0914/cognitive-palace.git
cd cognitive-palace
pip install -r requirements.txt
```

## Core Scripts

| Script | Purpose |
|--------|---------|
| `scripts/bm25_search.py` | BM25 retrieval engine |
| `scripts/sop_runner.py` | SOP standardization executor |
| `scripts/mcp_server.py` | MCP server with 11 tools |
| `scripts/self_evolve.sh` | Daily self-evolution cron script |
| `memory/ontology/graph.jsonl` | Knowledge graph (append-only) |

## Paper

This work is described in the paper: **CognitivePalace: Self-Evolution Framework for Autonomous AI Agents**

```
@misc{cognitivepalace2026,
  title={CognitivePalace: Self-Evolution Framework for Autonomous AI Agents},
  author={Anonymous},
  year={2026}
}
```

## License

MIT License
