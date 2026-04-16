# 🔨 Inkforge — Deep Writing Refactoring Engine

> **Ink + Forge.** Reforge ideas, reshape words.

Adaptive deep writing agent that transforms any input (video interviews, speeches, podcasts, articles) into **coherent, logically rigorous, insight-driven long-form content**.

## ✨ What Makes Inkforge Different

Most AI writing tools just polish text. Inkforge **refactors** it — like rewriting code from scratch while preserving the core logic.

Three signature constraints set Inkforge apart:

| Constraint | Rule | Why |
|------------|------|-----|
| 🚫 No first-person | Never use "我/我们" or "I/we" | Forces objective, universal voice |
| 🚫 No "not-but" pattern | Never write "X不是Y，而是Z" | Eliminates lazy contrast, demands real logic |
| 🚫 No filler transitions | Never use "首先/其次/然而/因此/总之" | Logic flows through content, not connectors |

## 🧠 Nine-Layer Processing System

| Layer | Name | What it does |
|-------|------|--------------|
| 1 | Requirement Identification | Extract principles, audience, scenario from input |
| 2 | Brief Construction | Build writing baseline (persona, audience, stance) |
| 3 | Preprocessing | Clean spoken language, remove fillers, detect fragments |
| 4 | Viewpoint Clustering | Extract & merge similar viewpoints |
| 5 | Logic Analysis | Map causal, parallel, progressive, contrast relationships |
| 6 | Structure Optimization | Enhance logic, merge duplicates, preserve framework |
| 7 | Deep Writing | Supplement background, data, examples |
| 8 | Quality Check | Verify all constraints and quality standards |
| 9 | Style Enforcement | Zero first-person, zero "not-but", zero filler transitions |

## 🔄 Three-Stage Workflow

```
Stage 1: Analysis & Planning (20%)
├─ Requirement ID → Brief → Preprocessing → Clustering → Logic Analysis
└─ Output: Brief + Viewpoint clusters + Logic graph

Stage 2: Structure Design (30%)
├─ Structure optimization
└─ Output: Optimized outline framework

Stage 3: Content Writing (50%)
├─ Deep writing → Quality check → Style enforcement
└─ Output: Complete article
```

Each stage requires **user confirmation** before proceeding.

## 📦 Installation

### For WorkBuddy / Claude Code

```bash
# Project-level
cp -r inkforge/ .workbuddy/skills/inkforge/

# User-level
cp -r inkforge/ ~/.workbuddy/skills/inkforge/
```

### For Other AI Platforms

Copy `SKILL.md` into your agent's skill/prompt directory. The file is self-contained and platform-agnostic.

## 🚀 Quick Start

```
Input:  Any content (interview transcript, speech, article, podcast)
Output: Deep, structured article (2000-10000 words)
```

**Example prompts:**
- `use inkforge` then paste your content
- "Refactor this interview into a 5000-word deep article"
- "将这篇演讲重构为深度长文"

## 📋 Quality Check Protocol

After Stage 3, Inkforge automatically verifies:

| Check | Standard |
|-------|----------|
| Word count | Matches Brief requirement |
| First-person | 0 occurrences |
| "Not-but" pattern | 0 occurrences |
| Filler transitions | 0 occurrences |
| Structure coverage | Every outline node covered |
| Logic coherence | Clear relationships between paragraphs |

## 🗂️ Repository Structure

```
inkforge/
├── SKILL.md          # Core skill definition (self-contained)
├── README.md         # This file
├── LICENSE           # MIT
└── .gitignore
```

## 🤝 Contributing

Issues and PRs welcome. Key areas for contribution:

- New style constraints
- Additional logic analysis patterns
- Multi-language support
- Integration with image generation tools

## 📄 License

MIT — use freely, attribute kindly.
