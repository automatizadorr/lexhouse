# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

**METATOK** is an automation platform workspace that integrates four core services:

- **Supabase** — database, authentication, and Row Level Security (RLS)
- **n8n** — workflow automation engine and trigger-based flows
- **Conversational AI** — intelligent messaging and auto-responses
- **Email marketing** — lead capture, reactivation, and follow-up campaigns

This repository is a design and orchestration workspace. There is no runnable application code here — the actual implementations live on the third-party platforms listed above.

## Custom Skills

Three project-specific skills are available via slash commands:

- `/automatizaciones` — Design and implement new automation workflows. Follows a structured process: identify the trigger, define actions/conditions, choose the right tool (n8n for data flows, Supabase for database logic, AI for auto-responses, email for campaigns), then test with example cases.

- `/mejorar` — Analyze and improve existing functions across four dimensions: performance (Supabase query optimization, reducing redundant AI calls, simplifying n8n flows), readability, reliability (data validation, error handling, deduplication), and UX. Always shows original vs. improved code with rationale.

- `/seguridad` — Full security review. Checks for hardcoded credentials, Supabase RLS policy coverage, webhook authentication on n8n flows, input validation before AI calls, rate limiting on email endpoints, and general web vulnerabilities (XSS, SQLi, CSRF). Reports findings by severity (CRÍTICO → BAJO) with file/line references and a 1–10 score.

## Architecture Patterns

### Automation Design Decisions

When a new automation is needed, pick the implementation layer based on what it does:

| Use case | Tool |
|---|---|
| Data flow orchestration | n8n |
| Database logic / computed values | Supabase Functions or triggers |
| Auto-replies to messages | Conversational AI |
| Lead/reactivation campaigns | Email marketing system |

### Common Automation Flows

- Lead capture → store in Supabase → send welcome email
- Detect inactive users in Supabase → n8n flow → personalized email
- Data extraction → AI processing → export report
- Incoming message → AI response → email follow-up

### Security Invariants

- All Supabase tables must have RLS policies active — no public tables without restrictions
- Supabase service keys must never appear in frontend code
- All n8n webhooks must require authentication
- All user inputs must be validated before being passed to the AI
- `.env` files must be listed in `.gitignore`

## Repository Contents

- `.claude/commands/` — The three custom skills above
- Image assets (Unsplash JPGs + PNG) — design assets for marketing/UI mockups
- `csaa` — empty placeholder file
