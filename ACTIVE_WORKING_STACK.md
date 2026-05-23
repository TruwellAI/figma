# Active Working Stack — Use Whatever Is Working

Neil directive: use the tools that actually work. Do not force a tool just because it is new, paid, or theoretically useful.

Last updated: 2026-05-23

## Working now

| Layer | Tool | Status | Use it for |
|---|---|---|---|
| Design source of truth | Figma | Connected via API | Design systems, screens, components, approval visuals |
| Figma-to-code bridge | Builder.io / Fusion | Public + private API connected | Testing Figma → Next.js/code workflow |
| Code/deploy platform | Vercel / v0 | API connected, team/user IDs stored | Next.js apps, deployments, v0-generated UI |
| Git source control | GitHub `TruwellAI/figma` | Connected | Trial evidence, integration docs, code handoff |

## Operating rule

Use this path first:

```text
Figma → Builder/Fusion → Next.js/Vercel → GitHub evidence
```

If Builder blocks or produces weak code, bypass it:

```text
Figma → v0/Codex → Next.js/Vercel → GitHub evidence
```

If v0 blocks, bypass it:

```text
Figma → Codex/Claude Code → Next.js/Vercel → GitHub evidence
```

## Trial rule

Each tool must prove:

1. Better output quality
2. Faster production
3. Useful integration with Friday/OpenClaw
4. Real deliverables for Novira/TruWell/NZ Agency
5. Worth keeping after 30 days

## Current priority

Use the working stack on Novira first:

- translate the current Novira direction into a proper Figma/Next.js design system
- test Builder/Fusion output quality
- test v0/Vercel output quality
- compare against direct Codex implementation
- keep the tool that produces the best result fastest
