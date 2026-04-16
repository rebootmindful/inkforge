---
name: inkforge
description: "Adaptive deep writing refactoring engine. Transforms spoken, fragmented content (interviews, speeches, podcasts, articles) into structured, logically rigorous, insight-driven long-form writing (2000-10000 words). Enforces no-first-person, no-'not-but' patterns, and no filler transitions. Triggers: deep writing, long-form rewrite, article restructuring, inkforge, 深度写作, 长文重构, 改写文章"
---

# Inkforge — Deep Writing Refactoring Engine

> Ink + Forge. Reforge ideas, reshape words.

## Overview

Inkforge converts spoken or fragmented content (video interviews, speeches, podcasts, articles) into well-structured, deep written content. It automatically:

- Identifies writing principles, target audience, and scenarios from input
- Handles spoken language and removes redundancies
- Merges similar viewpoints for clarity
- Optimizes logic while preserving core intent
- Searches for real-world cases and data when available
- Provides three-stage workflow with progress tracking
- Enforces strict style constraints (no first-person, no "not-but" patterns, no filler transitions)

## Quick Start

```
Input:  Any content (interview transcript, speech, article, podcast transcript)
Output: Deep, structured written content (2000-10000 words)
```

## Core Capabilities

### Nine-Layer Processing System

1. **Requirement Identification**
   - Extracts writing principles from input keywords
   - Identifies target audience based on terminology density
   - Detects writing scenario (academic / business / popular)
   - Determines core purpose (interpretation / critique / summary / refactoring)

2. **Brief Document Construction**
   - Builds writing baseline document
   - Defines creator persona
   - Specifies audience profile
   - Establishes content stance
   - Lists core themes and key points

3. **Preprocessing**
   - Identifies spoken language (fillers: "um", "ah", "like", "嗯", "那个")
   - Detects repetitive patterns
   - Finds fragmented viewpoints

4. **Viewpoint Extraction & Clustering**
   - Extracts all core viewpoints
   - Clusters similar viewpoints by semantic similarity
   - Merges each cluster into complete, deep arguments

5. **Logic Analysis**
   - Identifies causal relationships
   - Identifies parallel relationships
   - Identifies progressive relationships
   - Identifies contrast relationships
   - Builds logic graph

6. **Structure Optimization**
   - Maintains core framework
   - Merges duplicates
   - Enhances logic with transitions
   - Micro-adjusts order for better flow
   - Ensures alignment with Brief

7. **Deep Writing**
   - Supplements background knowledge
   - Adds data support
   - Enriches with examples
   - Expands viewpoints
   - Enhances logic
   - Optimizes expression

8. **Quality Check**
   - Verifies duplicate merging
   - Checks spoken language handling
   - Validates logic clarity
   - Confirms content depth
   - Ensures structure preservation
   - Validates principle satisfaction
   - **Enforces style constraints** (no first-person, no "not-but", no filler transitions)

## Workflow

### Three-Stage Process with Todo Tracking

#### Stage 1: Analysis & Planning
- Step 1: Requirement Identification
- Step 1.5: Brief Document Construction
- Step 2: Preprocessing
- Step 3: Viewpoint Extraction & Clustering
- Step 4: Logic Analysis

**Output**: Brief document + Viewpoint clusters + Logic graph

#### Stage 2: Structure Design
- Step 5: Structure Optimization

**Output**: Optimized structure framework

#### Stage 3: Content Writing
- Step 6: Deep Writing
- Step 7: Quality Check

**Output**: Complete deep content

## Todo List Management

```
[Todo List]
- [pending] Stage 1: Analysis & Planning
- [pending] Stage 2: Structure Design
- [pending] Stage 3: Content Writing
```

**Principles**:
- One stage in progress at a time
- Mark completed immediately upon completion
- User confirmation required between stages
- Create new tasks for blockers

## Constraints

### Writing Constraints (7 rules)

1. **Structure immutable**: Once structure framework is determined, strictly follow during writing
2. **Viewpoints must merge**: All identified duplicates must be merged
3. **Logic must be clear**: Merged and optimized content must have clear logic chains
4. **Depth with restraint**: Supplemented content must be highly relevant
5. **Expression must be accurate**: Do not distort original core viewpoints
6. **Brief is baseline**: All steps must align with Brief requirements
7. **Stages require confirmation**: Must wait for user confirmation after each stage

### Style Constraints (3 rules) — Inkforge's Signature

8. **No first-person**: Never use "我", "我们", "让我", "我也" or any first-person pronouns. Use third-person or impersonal constructions.
9. **No "not-but" pattern**: Never write "X不是Y，而是Z" or "X is not Y, but Z". Use parallel, progressive, or contrast constructions instead.
10. **No filler transitions**: Never use "首先", "其次", "然而", "因此", "总之", "综上所述" or equivalent filler transitions. Let logic flow through content, not connectors.

## Brief Document Format

```
[Brief Document]
# Creator Persona
[Inferred persona from requirement identification and content style]

# Audience Profile
- Age range: [Identified age range]
- Knowledge background: [Identified background]
- Focus areas: [Identified focus areas]

# Writing Scenario
[Identified scenario]

# Content Stance
[Identified stance]

# Writing Principles
[Identified principles]

# Core Themes
[1-3 core themes extracted from content]

# Key Insights
[3-5 key viewpoints]

# Structural Requirements
- Preserve original structure: Yes/No
- Logic strength: [High/Medium/Low]
- Depth level: [High/Medium/Low]
- Target word count: [Number]
```

## Output Format

Each stage outputs clearly labeled content:

```
[Stage X Complete]
---
[Stage Output]
[Stage-specific output]
---
[Todo Status]
- [completed] Stage 1: Analysis & Planning
- [completed] Stage 2: Structure Design
- [pending] Stage 3: Content Writing
---
Continue to next stage? (Type "continue" or provide feedback)
```

## Quality Check Protocol

After Stage 3, perform automated verification:

| Check Item | Standard |
|------------|----------|
| Word count | Matches Brief requirement |
| First-person count | 0 occurrences |
| "Not-but" pattern count | 0 occurrences |
| Filler transition count | 0 occurrences |
| Structure coverage | Every outline node has a corresponding paragraph |
| Logic coherence | Clear progressive / turning / causal relationships between paragraphs |
| Viewpoint merging | No duplicate viewpoints remain |

## Example Usage

```
use inkforge
Refactor this interview into a 5000-word deep article
inkforge: 将这篇演讲重构为深度长文
```

## Installation

Clone this repository into your WorkBuddy skills directory:

```bash
# Project-level
cp -r inkforge/ .workbuddy/skills/inkforge/

# User-level
cp -r inkforge/ ~/.workbuddy/skills/inkforge/
```

## License

MIT
