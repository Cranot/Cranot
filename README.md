# Dimitris Mitsos

I build developer tools and AI infrastructure — code-intelligence engines that let AI coding agents start with the codebase already mapped, and the systems work underneath them. Python and C++. 4,600+ GitHub stars across projects people run daily.

**Available for senior / staff engineering roles in developer tools, AI infrastructure, and code intelligence.** Remote, from Greece (EET — full EU overlap, US mornings). Co-founding conversations welcome as a second track. Reach me on [X](https://x.com/DimitriosMitsos).

## Code intelligence

One engine, two front doors.

**[roam-code](https://roam-code.com)** [![stars](https://img.shields.io/github/stars/Cranot/roam-code?style=flat&label=%E2%98%85&color=555)](https://github.com/Cranot/roam-code) — the engine. Run `roam index` once and an agent starts with the codebase fully mapped: symbols, call graphs, dependencies, architecture and git history in local SQLite. 28 languages, 281 commands, 244 MCP tools, change-safety gates. Fully local, no API keys.
`pip install roam-code` · [roam-code.com](https://roam-code.com) · [docs](https://roam-code.com/docs) · [source](https://github.com/Cranot/roam-code)

**[compile-code](https://github.com/Cranot/compile-code)** [![stars](https://img.shields.io/github/stars/Cranot/compile-code?style=flat&label=%E2%98%85&color=555)](https://github.com/Cranot/compile-code) — the front door. A thin CLI over the same engine: `compile claude` indexes, wires and launches in one step, pre-resolving who-calls-this, what-changed and what-breaks before the agent's first token, then verifying the diff after it edits. Head-to-head on a 300 KLOC Python repo: −83% agent turns, −80% input tokens, −63% cost.

## Most used

- **[claude-code-guide](https://github.com/Cranot/claude-code-guide)** [![stars](https://img.shields.io/github/stars/Cranot/claude-code-guide?style=flat&label=%E2%98%85&color=555)](https://github.com/Cranot/claude-code-guide) — the most-starred community reference for Claude Code. Hooks, MCP, settings, skills, the full CLI surface; auto-updated against the official docs, current through v2.1.220.
- **[super-hermes](https://github.com/Cranot/super-hermes)** [![stars](https://img.shields.io/github/stars/Cranot/super-hermes?style=flat&label=%E2%98%85&color=555)](https://github.com/Cranot/super-hermes) — skills that teach [Hermes Agent](https://github.com/NousResearch/hermes-agent) (221k★) to write its own analytical prompts, then report both what it found and what it could not see.
- **[chatbot-injections-exploits](https://github.com/Cranot/chatbot-injections-exploits)** [![stars](https://img.shields.io/github/stars/Cranot/chatbot-injections-exploits?style=flat&label=%E2%98%85&color=555)](https://github.com/Cranot/chatbot-injections-exploits) — catalog of prompt-injection techniques and exploit patterns. A red-teaming reference since 2023.
- **[deep-research](https://github.com/Cranot/deep-research)** [![stars](https://img.shields.io/github/stars/Cranot/deep-research?style=flat&label=%E2%98%85&color=555)](https://github.com/Cranot/deep-research) — fractal multi-agent research. A question spawns angles, angles recurse until atomic, then everything synthesizes back into one answer.

## Research

**[agi-in-md](https://github.com/Cranot/agi-in-md)** [![stars](https://img.shields.io/github/stars/Cranot/agi-in-md?style=flat&label=%E2%98%85&color=555)](https://github.com/Cranot/agi-in-md) — system prompts are cognitive prisms: they change how a model frames a problem, not how hard it thinks. Haiku 4.5 at minimum reasoning, given the right 332-word prompt, scores 9.8 on depth and finds 28 bugs; Opus without it scores 7.3 and finds 18. 82 prisms, 330+ proven principles, 5,800+ experiments, cross-validated on Claude and Gemini.

**[AgentsKB](https://agentskb.com)** — knowledge layer for AI agents: 39,827 verified answers across 244 technologies, returned in ~40 ms, free with no limits. Runs as an [MCP server](https://github.com/Cranot/agentskb-mcp) so agents stop guessing about APIs and SDK versions they were never trained on.

## Systems

- **[mzip](https://github.com/Cranot/mzip)** [![stars](https://img.shields.io/github/stars/Cranot/mzip?style=flat&label=%E2%98%85&color=555)](https://github.com/Cranot/mzip) — detection-based compression in C++17. Held-out, type-stratified benchmark over 70 real files: 28 wins, 42 ties, **0 losses**. 7.43× overall ratio against brotli-11 at 4.59×, xz-9e at 4.85× and zstd-22 at 4.11×.
- **[grouped-simd-hashtable](https://github.com/Cranot/grouped-simd-hashtable)** [![stars](https://img.shields.io/github/stars/Cranot/grouped-simd-hashtable?style=flat&label=%E2%98%85&color=555)](https://github.com/Cranot/grouped-simd-hashtable) — C++ hash table using grouped SIMD metadata scanning. Beats `ankerl::unordered_dense`, the accepted state of the art, at scale.
- **[tieredsort](https://github.com/Cranot/tieredsort)** [![stars](https://img.shields.io/github/stars/Cranot/tieredsort?style=flat&label=%E2%98%85&color=555)](https://github.com/Cranot/tieredsort) — header-only C++17 numeric sorting. 3.6× faster than `std::sort`, up to 21× on dense data.
- **[chameleon-cache](https://github.com/Cranot/chameleon-cache)** [![stars](https://img.shields.io/github/stars/Cranot/chameleon-cache?style=flat&label=%E2%98%85&color=555)](https://github.com/Cranot/chameleon-cache) — variance-aware cache replacement, +5.09pp hit rate over TinyLFU. Developed with feedback from Ben Manes, author of Caffeine.
