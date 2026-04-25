# OpenAutonomyX

OpenAutonomyX builds autonomous intelligence systems that decide, explain, and act with governance, observability, and human review where it matters.

## Organization focus

OpenAutonomyX repositories are organized around:

- Autonomous agents and agent platforms
- Governed decision systems
- Identity, policy, and access-aware automation
- Data, taxonomy, and entity-resolution workflows
- Documentation, review, and reusable instruction assets

## Shared instruction layer

Shared execution guidance lives in `openautonomyx/common-instructions`.

Use that repository for:

- Shared prompt and agent-role guidance
- Engineering execution standards
- Review, audit, and documentation prompts
- Context, guardrail, testing, and air-gapped operation policies
- Reusable instruction boilerplates

Do not duplicate shared instruction policies across product repositories. Product repositories should reference the shared layer and add only repo-specific guidance.

## Documentation boundaries

- `common-instructions`: reusable prompts, standards, validators, policies, and execution guidance
- `org-docs`: organization-level vision, strategy, architecture, and ADRs
- `shared-assets`: reusable non-code assets
- `shared-repos`: reusable code, configuration, tooling, and packages

## Operating principles

- Keep repository purpose explicit.
- Preserve current, next, and future state in docs.
- Prefer reviewable, minimal changes over broad undocumented rewrites.
- Require reviewer approval and HITL sign-off for production-facing changes.
- Keep GitHub as the system of record for approved prompts, docs, reviews, and releases.
