# Agent Guidance

This repository is the canonical development source for the Nonprofit AI Capability Framework. Work here should protect the framework's accuracy, scope, and usefulness while the project is still early-stage.

## Guiding Principles

- Prefer incomplete but accurate documentation over complete but speculative documentation.
- Preserve confirmed product decisions unless the user explicitly changes them.
- Mark uncertainty clearly as a working hypothesis or open question.
- Keep documentation small, navigable, and source-of-truth oriented.
- Avoid turning early product thinking into unvalidated claims.

## Current Phase

The project is in Phase 0: product foundation, repository design, and early validation. The goal is to clarify intent, scope, assumptions, framework logic, and research needs. Bounded prototypes using synthetic data may be created with explicit approval to test comprehension, usability, and commercial interest. Do not treat prototypes as validated products or begin production development during this phase.

## Do Not Add Without Explicit Approval

- Production application code, architecture, authentication, integrations, infrastructure, or live-data handling.
- Prototype UI specifications, wireframes, screens, dashboards, or onboarding flows. When approved, use synthetic data and mark the work as exploratory and unvalidated.
- Maturity stages, scoring systems, weighted rubrics, or organization-wide grades.
- Assessment questions or diagnostic instruments.
- Vendor rankings, tool recommendations, or implementation playbooks.
- Architecture Decision Records under `docs/decisions/`.

## Documentation Norms

Use `docs/product-charter.md` as the source of truth for product intent, governing decisions, hypotheses, open questions, and deferred work. Use `docs/decision-model.md` as the working source for the reasoning domains that connect organizational concerns to responsible recommendations. Preserve the distinction between the conversation model, reasoning model, and delivery model.

Substantive product claims and decisions should be identifiable as one of:

- Confirmed decision.
- Working hypothesis.
- Research finding.
- Open question.

Do not duplicate large sections across files. The README should orient readers, `PLANS.md` should look forward, and this file should guide agents and maintainers.

## Expected Workflow

Before changing the repository, inspect the existing documentation. Keep changes scoped to the requested phase. When product assumptions change, update the product charter rather than scattering durable decisions across planning notes.
