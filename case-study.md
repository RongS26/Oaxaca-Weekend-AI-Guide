# Case Study: From Travel Intent To AI Weekend Playbook

[English](case-study.md) | [中文](case-study.zh-CN.md)

## One-Line Summary

I used AI to turn a weekend Oaxaca trip idea into a bilingual self-guided guide and a practical playbook, then extracted the process into a reusable travel-guide workflow.

## Starting Point

The initial need was simple:

- I wanted a weekend guide for Oaxaca.
- I wanted it to be self-guided, not only a list of attractions.
- I wanted bilingual output so it could be read and used more flexibly.
- I cared about cultural understanding, route logic, and practical execution.

## What Worked

### 1. Asking For Context Before Itinerary

The output became more useful when the prompt moved away from:

```text
Give me a Oaxaca itinerary.
```

and toward:

```text
Explain the cultural and neighborhood logic first, then build a self-guided weekend route.
```

This made the guide feel less like a checklist and more like a way to understand the city.

### 2. Iterating Artifact Type

The useful iteration path was:

```text
bilingual guide
-> revised self-guided guide
-> weekend playbook v1
-> weekend playbook v2
```

Each version had a different job:

- Guide: explain what matters.
- Self-guided version: make it usable without a human guide.
- Playbook: make decisions easier during the trip.
- V2: reduce friction and improve practical sequencing.

### 3. Treating AI As A Format Partner

The main value was not that AI knew Oaxaca facts.

The value was that AI helped structure:

- sequence
- decision points
- bilingual explanation
- map-oriented thinking
- offline usability

## What I Would Improve Next Time

- Preserve the exact prompt history.
- Add source links for cultural and logistical claims.
- Add a "what changed from v1 to v2" diff.
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

## Portable Pattern

```text
I do not want generic recommendations.
I want a self-guided artifact that helps me understand the place and make decisions while there.
Start with cultural logic, then route logic, then practical playbook.
```
