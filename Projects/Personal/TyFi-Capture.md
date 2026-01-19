# TyFi Capture System

> **Status**: Operational with 9 active workflows
> **Server**: TyFi (188.245.209.158)
> **Last Updated**: 2026-01-19

## Overview

Personal "Second Brain" capture and categorization system for inspiration, research, and life improvements.

## Features

| Feature | Status |
|---------|--------|
| iOS Screenshot Capture | ✅ Working |
| Telegram Bot Interface | ✅ Working |
| Instagram Link Capture | ✅ Working |
| GPT-4o Vision Analysis | ✅ Working |
| Academic Article Detection | ✅ Working |
| Web Review Dashboard | ✅ Working |
| Grafana Dashboards | ✅ Working |
| Daily/Weekly Digest | ✅ Working |
| Learning Engine | ✅ Working |

## Active Workflows

1. Capture Inbox - Simple iOS (3b9kdG3Y9xyUTHcO)
2. Captures - Telegram Callback Handler
3. Captures - Instagram Ingestion
4. Capture Inbox - Digest Notifications
5. Capture Inbox - Learning Engine
6. Captures Review Interface
7. ROS Email Capture
8. Capture Inbox - Secure Ingestion
9. Capture Inbox - Telegram Feedback Handler

## Access Points

| Interface | URL |
|-----------|-----|
| Web Review | https://n8n.tyfi.fyi/webhook/captures-review |
| Grafana Inbox | https://h.tyfi.fyi/d/822811cb-ee21-4f8e-9663-be33a58dda5f |
| iOS Capture | Shortcut → /webhook/capture-simple |

## Database

- **Host**: postgres (Docker container)
- **Database**: tyfi
- **Tables**: captures, capture_learnings

## Roadmap

- [ ] Category Learning Loop
- [ ] Fact-Checking Pipeline
- [ ] Vector Embeddings
- [ ] Zotero Integration

## Links

- [[Checkpoints/TyFi-Capture/]]
- [Full Spec](/mnt/project/tyfi-capture-system-spec.md)
- [Roadmap](/mnt/project/tyfi-capture-roadmap.md)
