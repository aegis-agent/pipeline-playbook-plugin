---
name: intent
description: Find hand-raisers with explicit buying intent
---

# /intent - Buying Intent Detection

Find literal hand-raisers asking for solutions in public.

## Philosophy

> "These are literal hand-raisers asking for solutions. In public. For free."

**Key stat:** Intent posts have 2.7% bookmark rate - the highest engagement.

## Usage

```
/intent <category|competitor|problem>
```

### Examples

```bash
/intent "changelog tool"
/intent "Notion alternative"
/intent "documentation problem"
```

## Intent Signal Patterns

- "looking for recommendations" {category}
- "anyone use" {competitor}
- "alternative to" {competitor}
- "which {category} should I buy"

## Urgency Scoring

| Signal | Weight |
|--------|--------|
| Posted <7 days | +0.20 |
| Urgency words | +0.15 |
| Decision words | +0.15 |
| Budget mention | +0.10 |
