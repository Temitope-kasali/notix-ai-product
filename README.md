# Notix

### AI Product Manager | Product Strategy | AI-Native Messaging Infrastructure

**[Visit Notix →](https://usenotix.dev/)**

**Notix** is a developer-first messaging platform for payments, commerce and SaaS teams, bringing transactional email, marketing email, SMS/OTP, deliverability, campaigns and messaging operations into one system.

As the **AI Product Manager**, I worked on the product strategy, AI experience and MCP direction for transforming Notix from a messaging platform into an intelligent, evidence-driven operating layer for messaging infrastructure.

---

## The Product Challenge

Messaging infrastructure is often fragmented across transactional providers, marketing platforms, custom OTP systems, suppression lists and disconnected delivery logs.

Notix brings these workflows into one system, giving teams a unified way to:

- Send transactional and marketing messages
- Manage email and SMS verification
- Control domains and deliverability
- Track message events and delivery outcomes
- Manage contacts, campaigns and journeys
- Prevent duplicate and unsafe sends
- Understand what happened to every message

The product principle was simple:

> **The value is not just sending a message. It is being able to understand what happened, prevent failures and operate messaging safely.**

---

## My Role

**AI Product Manager**

I focused on:

- AI product strategy and discovery
- Product requirements and feature definition
- AI-native user experiences
- Developer experience
- MCP product strategy
- AI workflow design
- AI safety and governance
- Human-in-the-loop decision-making
- Product metrics and phased roadmap definition

---

## AI Product Strategy

I defined a staged AI experience around three levels of increasing autonomy:

### 01 — Assist

AI helps users complete existing workflows:

- Draft email and SMS content
- Generate template variables
- Explain API errors
- Translate and adapt messaging
- Generate integration guidance

### 02 — Diagnose & Optimise

AI uses Notix product evidence to help users understand and improve messaging performance:

- Diagnose delivery failures
- Identify bounce and complaint patterns
- Explain DNS and deliverability issues
- Recommend fixes
- Analyse delivery patterns

### 03 — Operate

AI can support controlled operational workflows:

- Create template drafts
- Run deliverability checks
- Send test messages
- Schedule approved sends
- Pause journeys
- Replay failed webhook deliveries

Higher-risk actions remain subject to permissions, confirmation, idempotency and auditability.

---

## MCP Strategy

A key part of my product work was defining how **Model Context Protocol (MCP)** could expose Notix capabilities to AI clients.

The proposed architecture connects:

**AI Client → Notix MCP → Notix Application Services**

The MCP layer provides:

- **Resources** — structured messaging and delivery context
- **Tools** — controlled product actions
- **Prompts** — repeatable workflows

Initial AI workflows included:

- `/diagnose-delivery`
- `/review-campaign`
- `/integrate-notix`
- `/weekly-delivery-brief`

The product direction prioritises read-only diagnosis and low-risk creation before introducing higher-risk production actions.

---

## Product Thinking

One of the key product decisions was to **separate AI assistance from AI authority**.

The model should not determine:

- Authorisation
- Consent eligibility
- Suppression enforcement
- Spend limits
- Risk thresholds
- Final delivery state

These remain server-side product controls.

This creates an AI experience that is useful without making the model the source of truth.

---

## Product Outcome

The resulting product direction positions Notix as more than a messaging API:

> **A developer-owned system of record and control for outbound product messages, with AI providing a permissioned interface for understanding and operating that system.**

The work combines **AI product management, developer experience, agentic workflows, MCP, product strategy and responsible AI design**.

---

### Product Focus

`AI Product Management` · `Product Strategy` · `AI-Native Products` · `MCP` · `AI Agents` · `Developer Experience` · `AI Governance` · `Human-in-the-Loop` · `Messaging Infrastructure`
