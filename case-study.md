# Case Study: From Travel Intent To AI Weekend Playbook

[English](case-study.md) | [中文](case-study.zh-CN.md)

## One-Line Summary

I used AI to turn a weekend Oaxaca trip idea into a bilingual guide and a practical playbook, then extracted the interaction pattern into a reusable travel-planning workflow.

## Starting Point

The initial need was simple:

- I shared my travel dates and asked for a plan that considered timing, local character, and my known travel preferences from previous conversations.
- I wanted the output to become a polished PDF guide, not just a chat answer.
- I explicitly asked for a detailed schedule and links for anything that required tickets or booking.
- I cared about cultural understanding, route logic, practical execution, and value for money.

## What Worked

### 1. Starting With A Low-Assumption Brief

The first version worked well because the initial prompt was not over-specified. I gave the AI the actual travel window, asked it to consider local character, and let it use what it already knew about my travel preferences.

That first guide was already strong: it moved beyond a loose list of places and became a concrete PDF-style travel artifact with schedule details and booking links.

### 2. Using Personal Context To Challenge The Plan

The second step was not simply "make it prettier" or "add more places."

After reading the first plan, I noticed that one recommended tour overlapped with experiences available near Mexico City, especially the kind of archeological / day-trip pattern I could already access through places like Teotihuacan. That made the paid tour feel less differentiated and less cost-effective.

I also noticed that the backup plan was still too tour-heavy. It assumed that a full paid tour was the natural alternative, while I might prefer a cheaper self-directed exploration if the route, map points, and practical links were clear enough.

The useful prompt shift became:

```text
Do not only optimize the destination.
Also consider what I can already experience from where I live,
what is redundant, and what is not worth the price.
```

### 3. Turning The Interaction Into A Template

The final value was extracting the interaction pattern:

```text
initial travel intent
-> polished guide with schedule and links
-> personal-context critique
-> map / route / self-exploration alternatives
-> reusable travel playbook workflow
```

### 4. Treating AI As A Format Partner

The main value was not only that AI knew Oaxaca facts.

The value was that AI helped structure:

- sequence
- decision points
- bilingual explanation
- map-oriented thinking
- offline usability
- a repeatable way to brief and correct AI for future trips

## What I Would Improve Next Time

- Preserve the exact prompt history.
- Add source links for cultural and logistical claims.
- Add a "what changed from v1 to v2" diff.
- Be more explicit about visual design requirements and ask the AI to preserve design elements that already worked in the first version.
- Add a post-trip review after using the guide.
- Export an HTML version in addition to PDFs.

## Durable Learning

For life-related AI interactions, the best memory is not the surface output.

Do not store:

- every restaurant
- every opening hour
- one-off travel logistics

Store:

- the workflow that made the output good
- the taste/preference behind the output
- the artifact if it can be reused or shown
- the reflection that improves future AI collaboration
- the correction logic: when to challenge AI recommendations using your own lived context

## Portable Pattern

```text
Build me a practical travel guide for [destination] and [dates].
Use what you know about my travel preferences.
Include a detailed schedule and booking / ticket links where relevant.

Then review the plan against my lived context:
what is redundant with places I can already visit,
what is not worth the price,
and what can be done through self-directed exploration instead of a paid tour.

Finally, turn the result into a reusable playbook with route logic,
map points, decision points, and backup options.
```
