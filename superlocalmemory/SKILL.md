---
name: superlocalmemory
description: Local-first AI memory system that gives Claude persistent memory across sessions via MCP with knowledge graphs and hybrid search.
---

# SuperLocalMemory V2

Universal, local-first AI memory system that provides persistent memory across sessions for Claude and 17+ other AI tools. All data stays on your machine in a single SQLite file.

## When to Use This Skill

- When you need Claude to remember context, decisions, or patterns across sessions
- - When working on long-running projects where continuity matters
  - - When you want shared memory between multiple AI tools (Claude Code, Cursor, VS Code, etc.)
   
    - ## How to Use
   
    - npm install -g superlocalmemory
   
    - Add to your MCP configuration and Claude gains access to slm_remember, slm_recall, slm_search, and more.
   
    - ## Example
   
    - "Remember that our API uses the CQRS pattern with event sourcing for the order service"
    - Then in a new session: "What patterns does our project use?"
