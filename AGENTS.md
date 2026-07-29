# Agent Guidance

This repository is the canonical development source for the Nonprofit AI Capability Framework. Work here should protect the framework's accuracy, scope, and usefulness while Framework v0.1 is used, tested, and implemented.

## Guiding Principles

- Prefer incomplete but accurate documentation over complete but speculative documentation.
- Preserve confirmed product decisions unless the user explicitly changes them.
- Mark uncertainty clearly as a working hypothesis or open question.
- Keep documentation small, navigable, and source-of-truth oriented.
- Avoid turning product thinking into unvalidated claims.

## Current Product Direction

Framework v0.1 is the stable methodological baseline for the open repository. It includes the product charter, eleven-domain decision model, Decision Conversation protocol, facilitator worksheet, decision brief template, beta test plan, and synthetic examples.

The next implementation layer is a separate runnable hosted application that expresses the same methodology through a guided user experience and AI-assisted delivery. Methodology changes require deliberate review. UX, implementation, testing, and application code may iterate more rapidly when they preserve the approved reasoning model and do not imply validation that has not happened.

## Do Not Add Without Explicit Approval

- Unsupported claims about field validation, commercial validation, client deployment, or implementation results.
- Numerical maturity scoring, weighted maturity rubrics, or organization-wide grades.
- Vendor rankings, procurement recommendations, or generic AI tool rankings.
- Live sensitive organizational data, participant-identifiable beta materials, recordings, transcripts, or completed client briefs.
- High-consequence workflows such as eligibility, employment, health or safety screening, legal advice, or high-consequence profiling.
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

Before changing the repository, inspect the existing documentation. Keep changes scoped to the requested work. When product assumptions change, update the product charter rather than scattering durable decisions across planning notes.
