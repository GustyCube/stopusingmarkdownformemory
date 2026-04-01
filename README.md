# Markdown Is Not Memory

Your agent's `MEMORY.md` is a glorified sticky note. Stop appending to a text file and calling it cognition.

**[stopusingmarkdownformemory.com](https://stopusingmarkdownformemory.com)**

## What is this?

A satirical single-page site about why the entire AI agent industry decided that flat markdown files are an acceptable memory system. Spoiler: they're not.

Every major AI coding tool — Claude Code, Cursor, Copilot, Windsurf, Manus, OpenClaw — independently converged on "just append to a .md file" as their memory architecture. This site explains, with extensive profanity, why that's a terrible idea.

## The problems

- **No retrieval** — grep is not a query engine
- **No decay** — old memories never fade
- **No types** — preferences, facts, and deprecated instructions all look the same
- **No concurrency** — two agents, one file, zero locking
- **Silent staleness** — renamed a directory? MEMORY.md still points to the old one
- **Lost in the middle** — LLMs can't attend to information buried at line 87
- **Security holes** — ~48% poisoned retrieval rate via MemoryGraft attacks
- **Empirically worse** — ETH Zurich proved context files reduce task success while increasing cost

## Alternatives

- [Membrane](https://github.com/GustyCube/membrane) — Typed, revisable, decayable memory in Go
- [Mem0](https://mem0.ai) — Hybrid vector + KV + knowledge graph
- [Letta (MemGPT)](https://letta.com) — LLM-as-OS with virtual memory paging
- [Zep](https://getzep.com) — Temporal knowledge graph
- [Cognee](https://github.com/topoteretes/cognee) — Knowledge graph + vector search
- [Memoria](https://github.com/memoria-ai/memoria) — MCP-native memory with git-for-data snapshots

## Run locally

It's a single HTML file. Open it.

```bash
open index.html
```

## Inspired by

- [justfuckingusehtml.com](https://justfuckingusehtml.com)
- [justfuckingusecloudflare.com](https://justfuckingusecloudflare.com)

## License

MIT
