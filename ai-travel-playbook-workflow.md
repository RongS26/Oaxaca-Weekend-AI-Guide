# AI Travel Playbook Workflow

[English](ai-travel-playbook-workflow.md) | [中文](ai-travel-playbook-workflow.zh-CN.md)

## Goal

Use AI to create travel artifacts that increase cultural understanding, reduce decision friction, and adapt recommendations to personal context.

The output should be more than an itinerary. It should become a practical guide and playbook that can be used, challenged, and reused.

## Input Brief

```text
Destination:
Travel dates / duration:
Starting area:
Current living context:
Energy level:
Travel style:
Must-have interests:
Constraints:
Language needs:
Output format:
```

## Workflow

### 1. Low-Assumption First Draft

Start with a real travel brief:

- destination and dates
- available time
- known travel preferences
- desired output format
- request for detailed schedule
- request for links for ticketed or reservation-based items

The goal is to get a strong first artifact before over-correcting it.

### 2. Personal-Context Review

Review the first plan against personal context:

- What overlaps with experiences already available where I live?
- What is culturally interesting but not worth the price?
- Which paid tours can become self-directed exploration?
- Which recommendations seem generic rather than preference-aware?

### 3. Route, Map, And Link Requirements

Ask for:

- marked map points
- route sequence
- practical links
- ticket / booking links
- Plan A / Plan B
- clear tradeoffs between paid tour and self-exploration

### 4. Weekend Playbook

Turn the revised guide into a playbook:

- time blocks
- decision points
- Plan A / Plan B
- estimated effort
- notes for future self

### 5. Visual And Format Iteration

When a version already works visually, say so explicitly:

```text
Keep the parts of the first version that worked.
Improve the weak parts without changing the visual direction I already approved.
Use clear hierarchy, route/map evidence, and readable bilingual formatting.
```

### 6. Post-Trip Review

After the trip, capture:

- what was accurate
- what was wrong
- what created real cultural understanding
- what should become a reusable prompt pattern

## Reusable Prompt

```text
Help me build a bilingual travel guide and playbook for [destination].

Use my travel dates, current living context, and known preferences.
Create a detailed schedule and include links for anything that requires tickets, booking, or a paid tour.

Then review the plan against my personal context:
what is redundant with places I can already visit,
what is not worth the price,
and what can be done through self-directed exploration instead.

Finally, turn it into a practical playbook with route logic, map points, decision points, backups, and a readable bilingual format.
```
