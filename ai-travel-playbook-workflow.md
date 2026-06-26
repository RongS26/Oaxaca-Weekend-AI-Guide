# AI Travel Playbook Workflow

[English](ai-travel-playbook-workflow.md) | [中文](ai-travel-playbook-workflow.zh-CN.md)

## Goal

Use AI to create travel artifacts that increase cultural understanding and reduce decision friction.

The output should be more than an itinerary. It should become a usable self-guided playbook.

## Input Brief

```text
Destination:
Travel dates / duration:
Starting area:
Energy level:
Travel style:
Must-have interests:
Constraints:
Language needs:
Output format:
```

## Workflow

### 1. Context First

Ask for:

- cultural background
- neighborhood logic
- food / market / craft context
- local etiquette and safety basics
- what is overhyped vs worth doing

### 2. Route Logic

Convert the context into:

- anchor stops
- walking sequence
- meal timing
- reservation-sensitive items
- weather / fatigue backups

### 3. Self-Guided Guide

Generate a bilingual self-guided guide with:

- where to go
- why it matters
- what to notice
- what to skip if tired
- map links when useful

### 4. Weekend Playbook

Turn the guide into a playbook:

- time blocks
- decision points
- Plan A / Plan B
- estimated effort
- notes for future self

### 5. Iteration

Ask the AI to compare versions:

```text
What improved from v1 to v2?
What became more practical?
What became more culturally grounded?
What should be removed because it is generic?
```

### 6. Post-Trip Review

After the trip, capture:

- what was accurate
- what was wrong
- what created real cultural understanding
- what should become a reusable prompt pattern

## Reusable Prompt

```text
Help me build a self-guided bilingual travel playbook for [destination].

Do not only list attractions. First explain the cultural and neighborhood logic.
Then build a practical route with timing, decision points, fatigue backups, and map links.
Prioritize things that help me understand the place, not only check it off.
Output in [language preference] and make it usable offline.
```
