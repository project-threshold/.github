# Project Threshold

**Carbon-aware CI/CD infrastructure with explicit constraints, transparent tradeoffs, and auditable outcomes.**

Project Threshold is an open-source initiative to rethink CI/CD as a *decision-making system*, not just an execution engine. We treat energy, carbon intensity, cost, and criticality as first-class constraints — alongside correctness and reliability.

This organization hosts the core software, specifications, documentation, and experiments that make up Project Threshold.

---

## Why Project Threshold

Modern CI/CD systems optimize for speed and convenience while ignoring their externalities. Build pipelines run continuously, often redundantly, across carbon-intensive regions and time windows — largely invisible to developers.

Project Threshold asks a different question:

> **When *should* this work run — and why?**

By introducing explicit thresholds (carbon intensity, delay tolerance, criticality), we enable CI/CD systems that are:

* Environmentally aware
* Operationally honest
* Explicitly constrained
* Auditable and explainable

---

## Core Principles

1. **Constraints are a feature**
   Sustainability, cost, and energy limits are not afterthoughts. They shape the system.

2. **Decisions over execution**
   Scheduling logic matters more than how fast a job can run.

3. **Transparency and explainability**
   Every delay, execution, and tradeoff should be explainable to a human.

4. **Open core, open trust**
   The systems that decide *when* work runs must remain open and auditable.

5. **Local-first, bring-your-own-infrastructure**
   Users control where and how their workloads run.

---

## What Lives Here

This GitHub organization is intentionally split into focused repositories with clear license boundaries.

### Core Repositories

* **`threshold-core`** (AGPLv3)
  The control plane: scheduler, policy engine, pipeline compiler, and GitHub App backend.

* **`threshold-runner`** (AGPLv3)
  Stateless job execution agents. Bring your own runners or use managed ones later.

* **`threshold-cli`** (AGPLv3)
  Developer-facing tooling for inspection, debugging, and carbon reporting.

### Specifications & Governance

* **`threshold-specs`** (Apache 2.0)
  Open specifications: runner protocol, job state machine, config schemas, APIs.

* **`threshold-docs`** (CC-BY 4.0)
  Manifesto, design rationale, and long-form documentation.

### Supporting Repos

* **`threshold-examples`** (AGPLv3)
  Reference configurations and example pipelines.

* **`threshold-labs`** (AGPLv3)
  Experiments, prototypes, and research work. APIs here are not stable.

---

## Licensing Philosophy

Project Threshold uses **strong copyleft (AGPLv3)** for its core components.

This ensures:

* Free self-hosting
* Freedom to modify
* A level playing field for hosted services
* Contributions flow back to the community

Specifications are licensed separately under **Apache 2.0** to encourage ecosystem growth.

Documentation is licensed under **CC-BY 4.0**.

Commercial licensing and managed service offerings may be available in the future, without compromising the openness of the core scheduler.

---

## Deployment Model

Project Threshold is designed to support multiple modes:

1. **Fully self-hosted (OSS)**
   You run the control plane and bring your own runners.

2. **Managed control plane (future)**
   We host the scheduler and carbon intelligence; you bring runners or use managed ones.

3. **Fully managed (future)**
   Control plane + runners hosted for you.

The same open protocols and semantics apply in all modes.

---

## Who This Is For

* Engineers who care about sustainability *and* correctness
* Infrastructure teams looking to reduce waste
* Researchers exploring carbon-aware computing
* Organizations that want transparency instead of greenwashing

---

## Status

Project Threshold is in **active early development**.

Expect:

* Rapid iteration
* Explicit design discussions
* Breaking changes
* A strong focus on correctness and clarity over features

---

## Contributing

Contributions are welcome.

Please see individual repositories for:

* Contribution guidelines
* Development setup
* Code of conduct

Design discussions and architectural changes are encouraged to happen in the open.

---

## A Note on Ethos

Project Threshold is not trying to be the fastest CI/CD system.

It is trying to be the *most honest*.

If that resonates with you, you are in the right place.

---

*Project Threshold — making the invisible costs of software visible.*
