---
name: outbound
description: Cold email campaign builder at scale
---

# /outbound - Cold Email Campaign Builder

Build cold email campaigns at scale.

## Philosophy

> "Speed creates momentum and momentum creates luck."

## Usage

```
/outbound "<offer>" --icp "<ideal customer>" [--volume <N>]
```

### Examples

```bash
/outbound "AI code review" --icp "VP Engineering at Series A"
/outbound "Consulting" --icp "Founders" --volume 15000
```

## Infrastructure

```
Emails per inbox per day: 50 (safe limit)
Inboxes needed = Monthly volume / (50 * 22 working days)
Warmup period: 14 days minimum
```

## Metrics Benchmarks

| Metric | Good | Great | Elite |
|--------|------|-------|-------|
| Open rate | >40% | >55% | >70% |
| Reply rate | >3% | >5% | >10% |
| Meeting rate | >0.5% | >1% | >2% |
