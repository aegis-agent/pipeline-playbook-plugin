---
name: prospect
description: Find high-intent leads from new-hire and buying signals
---

# /prospect - New Hire Prospecting

Find high-intent leads using the 90-day new hire window.

## Philosophy

> "New hires are DESPERATE to prove themselves. They're not loyal to existing vendors yet."

## Usage

```
/prospect <target> [role_filter]
```

### Examples

```bash
/prospect fintech
/prospect "stripe OR plaid" "VP OR Director"
/prospect "series b" "Head of Engineering"
```

## Scoring

| Signal | Weight |
|--------|--------|
| New hire <30 days | +0.35 |
| New hire <90 days | +0.30 |
| VP/C-suite title | +0.20-0.30 |
| Director/Head | +0.15 |
| High followers | +0.10 |
