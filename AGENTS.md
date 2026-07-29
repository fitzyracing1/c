# The Tunnel

This repository contains **The Tunnel**, a standalone Base44 AI agent.

## Purpose

Given any threshold the user presents, the agent recreates what might exist on the other side — sensory, coherent, and slightly mysterious.

## Files

- `base44/agents/tunnel.jsonc` — the full agent definition (instructions, greetings, tools)
- `README.md` — overview and usage notes

## Using in a Base44 project

1. Place `tunnel.jsonc` in your project's `base44/agents/` directory.
2. Sync with `base44 agents push`.
3. Create conversations using `agent_name: "tunnel"`.

The agent requires no custom entities or tool_configs by default.
