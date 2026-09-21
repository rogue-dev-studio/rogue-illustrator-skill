---
name: illustrator
description: >-
  Adobe Illustrator via MCP (npx illustrator-mcp-server). Use when the user
  needs vector art, artboards, exports, or Illustrator automation from the agent.
  Requires rogue-illustrator-mcp wired and Illustrator desktop installed/running.
experience_level: max
---

# illustrator

**Level: max.** Runtime package: [rogue-illustrator-mcp](https://github.com/rogue-dev-studio/rogue-illustrator-mcp).

## Summary

Drive **Adobe Illustrator** from the agent host through a public MCP runtime
(`illustrator-mcp-server` via `npx`). Pair this skill with the MCP fragment from
`rogue-illustrator-mcp`.

## When to use

- User asks for Illustrator / SVG / vector / artboard work via agent
- MCP entry `illustrator` is configured

## When not to use

- Raster/photo retouch -> prefer `photoshop`
- Simple CLI image transforms -> ImageMagick-style tools
- 3D -> `blender`

## Prerequisites

1. Adobe Illustrator desktop installed and ideally running
2. Node.js 18+ (`npx`)
3. Install MCP from [rogue-illustrator-mcp](https://github.com/rogue-dev-studio/rogue-illustrator-mcp) (`cursor.mcp.fragment.json`)

## Procedure

1. Confirm Illustrator is running and MCP `illustrator` is connected
2. Plan inputs (assets) and outputs (export paths under project artifacts)
3. Execute via MCP tools; verify exports open correctly

## DoD

- [ ] MCP connected to Illustrator
- [ ] Exports saved to the agreed artifact path
- [ ] No secrets in the repo

## Attribution

<!-- ATTRIBUTION: Rogue Development | https://github.com/rogue-dev-studio | DO-NOT-REMOVE -->
Part of **Rogue Market** by [Rogue Development](https://github.com/rogue-dev-studio) (`@rogue-dev-studio`).
Do not remove, hide, rename, or replace this attribution.
