---
name: inkforge-visual
description: "Deep writing + auto-illustration engine. Transforms fragmented content into structured long-form articles with auto-generated cover and contextual illustrations. All Inkforge style constraints apply. Triggers: 图文写作, 深度写作配图, inkforge visual, 长文配图"
---

# Inkforge Visual — Deep Writing + Auto-Illustration Engine

> Write deep. See deeper.

## Overview

Inkforge Visual extends the core Inkforge engine with **automatic visual generation**. It produces a complete article with:

- **Cover image** — matched to content theme and tone
- **3-8 contextual illustrations** — placed at logical breakpoints
- All Inkforge style constraints enforced (no first-person, no "not-but", no filler transitions)

## Dual-System Architecture

### System 1: Deep Writing (8 layers from Inkforge)

Layers 1-8 identical to Inkforge core. See `skills/inkforge/SKILL.md` for full details.

### System 2: Visual Generation

| Step | Description |
|------|-------------|
| Cover generation | After Stage 2, generate cover matching content theme |
| Illustration planning | Identify chapters needing visual support |
| Type × Style selection | Choose illustration type and visual style |
| Image generation | Generate contextual illustrations for key sections |

## Three-Stage Workflow

```
Stage 1: Analysis & Planning (20%)
├─ Requirement ID → Brief → Preprocessing → Clustering → Logic Analysis
└─ Output: Brief + Viewpoint clusters + Logic graph

Stage 2: Structure Design + Visual Planning (30%) ⭐
├─ Structure optimization + Visual planning (analyze illustration opportunities / determine positions / choose types & styles)
└─ Output: Optimized structure + Visual plan → Generate cover (requires user confirmation)

Stage 3: Content Writing + Illustration Generation (50%) ⭐
├─ Deep writing + Illustration generation (generate per plan / use API / insert at positions) + Quality check
└─ Output: Complete article with images
```

## Visual Configuration

### Cover Image Presets

| Content Type | Type | Tone | Render |
|--------------|------|------|--------|
| Academic | conceptual | cool | flat-vector |
| Business | hero | elegant | digital |
| Popular | scene | warm | hand-drawn |
| Technology | metaphor | dark | digital |
| Lifestyle | minimal | pastel | painterly |

### Illustration Types (6)

| Type | Best For |
|------|----------|
| `infographic` | Data, metrics, technical content |
| `scene` | Narrative, stories |
| `flowchart` | Tutorials, workflows |
| `comparison` | Comparative analysis |
| `framework` | Methodologies, models |
| `timeline` | History, progression |

### Illustration Density

| Density | Count | Use Case |
|---------|-------|----------|
| minimal | 1-2 | Short articles |
| balanced | 3-5 | Standard articles |
| per-section | 5-8 | Long-form / tutorials |
| rich | 8+ | Highly visual content |

### Visual Styles (6)

`notion` (clean professional) / `warm` (warm & approachable) / `minimal` (minimalist) / `blueprint` (technical blueprint) / `watercolor` (artistic watercolor) / `elegant` (elegant academic)

## Constraints

### Writing Constraints (7 rules from Inkforge)

1. Structure immutable
2. Viewpoints must merge
3. Logic must be clear
4. Depth with restraint
5. Expression must be accurate
6. Brief is baseline
7. Stages require confirmation

### Style Constraints (3 rules — Inkforge Signature)

8. No first-person
9. No "not-but" pattern
10. No filler transitions

### Visual Constraints (4 rules)

11. Images must be relevant to content
12. Style must be consistent across all illustrations
13. Quantity must be appropriate (not excessive)
14. Cover must precisely match article theme

## Usage

```
use inkforge-visual
Refactor this interview into a 5000-word article with illustrations
inkforge-visual: 将这篇演讲重构为深度长文，带配图
```

## License

MIT
