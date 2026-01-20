# Project Threshold

### Project Threshold is an open-source, carbon-aware CI/CD control plane.

It models energy, carbon intensity, and cost as first-class system constraints, and integrates them directly into build, test, and deployment decisions.

Project Threshold is infrastructure software.
It is designed to be quiet, explainable, and deliberate.

# Purpose

Modern CI/CD systems optimize for speed and availability while treating environmental cost as external or informational.

Project Threshold takes a different position:

   Carbon is a property of the system, not a report generated after the fact.

Scheduling, deferral, and execution decisions are made with explicit awareness of:

- carbon intensity

- job dependencies

- criticality

- policy constraints

Every decision can be inspected and explained.

# What the System Is

Project Threshold is:

- A carbon-aware scheduling control plane

- A policy-driven evaluator, not a runner replacement

- A system that can:

   - defer jobs

   - reschedule execution

   - block execution

   - explain why

It integrates with existing developer workflows rather than replacing them.

# What the System Is Not

Project Threshold is not:

- A sustainability dashboard

- A badge or scoring system

- An optimization for “green” outcomes at all costs

It does not attempt to persuade users.
It exposes constraints and lets systems respond accordingly.

# Design Principles
### API-First

Project Threshold is designed API-first.

The API is the canonical interface to the system.
All other interfaces consume it.

- The CLI is an API client

- The Web UI is an API client

- No interface contains privileged logic

This ensures:

- consistent behavior

- predictable outcomes

- explainable decisions

- long-term stability

### Unified Domain Model

All interfaces operate on the same core concepts:

- pipelines

- jobs

- dependencies

- constraints

- carbon windows

- scheduling decisions

If an interaction feels unclear, it is treated as a domain or API issue, not a presentation problem.

### Carbon as a Constraint

Carbon intensity is evaluated alongside other system constraints such as:

- time

- availability

- priority

- policy

It participates directly in scheduling decisions.

# Open Source and Stewardship

Project Threshold is:

- public from day one

- designed to be self-hosted

- built to support bring-your-own runners

Governance favors:

- transparency

- reproducibility

- long-term maintainability

# Intended Audience

Project Threshold is built for:

- infrastructure and platform engineers

- climate-conscious developers who value systems over signals

- researchers exploring carbon-aware computing

- teams that prioritize explainability over automation

# Project Status

Project Threshold is in early development.

Expect:

- evolving APIs

- open design discussions

- incomplete surfaces

Project Threshold exists to make constraints visible —
and to let systems respond deliberately.
