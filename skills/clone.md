---
name: clone
description: SaaS reverse engineering playbook for rapid rebuilding
---

# /clone - SaaS Reverse Engineering

Reverse engineer and rebuild any SaaS product in weeks.

## Philosophy

> "Most SaaS products have years of feature creep. You're building the lean version."

## Usage

```
/clone "<product_url>" [--scope MVP|FULL]
```

### Examples

```bash
/clone "https://example-saas.com"
/clone "https://competitor.io" --scope FULL
```

## Feature Triage

| Category | Priority |
|----------|----------|
| CORE (30%) | Build Week 1 |
| IMPORTANT (40%) | Build Month 1 |
| NICE TO HAVE (20%) | Month 2-3 |
| BLOAT (10%) | Never build |
