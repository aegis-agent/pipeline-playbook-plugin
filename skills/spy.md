---
name: spy
description: Monitor competitors for complaints and opportunities
---

# /spy - Competitive Intelligence

Monitor competitors for complaints and warm leads.

## Philosophy

> "Your competitor's support Twitter account is a goldmine. Every complaint is a warm lead."

## Usage

```
/spy <competitor> [--deep] [--continuous]
```

### Examples

```bash
/spy stripe
/spy intercom --deep
/spy zendesk --continuous
```

## Severity Levels

| Severity | Indicators | Action |
|----------|------------|--------|
| CRITICAL | cancel, switching, refund | DM immediately |
| HIGH | furious, terrible, broken | Contact within 24h |
| MEDIUM | frustrated, bug, slow | Add to lead list |
| LOW | wish, would be nice | Product intel |
