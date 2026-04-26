## Summary

<!-- What changed and why? -->

## Standards-first alignment

Every product, schema, registry, metadata model, deployment pattern, and trust/provenance model must adopt mature open standards before introducing custom OpenAutonomyX or AgentNxt fields.

Reference policy:

- https://github.com/openautonomyx/common-instructions/blob/main/policies/openautonomyx-standards-first-policy.md

### Checklist

- [ ] I checked whether Schema.org covers the public semantic metadata.
- [ ] I checked whether an open standard or mature framework covers this concept before adding custom fields.
- [ ] I documented the primary ecosystem alignment, such as CNCF, LF AI & Data, LF Decentralized Trust, OpenSSF, OpenJS, FINOS, LF Edge, LF Energy, W3C, OCI, SPDX, CycloneDX, SLSA, Sigstore, OpenAPI, AsyncAPI, C2PA, or another mature standard.
- [ ] Any new OpenAutonomyX or AgentNxt-specific fields are optional, documented, and justified as true gaps.
- [ ] I did not use local registry slugs as canonical IDs when a publisher-controlled URL, DID, package coordinate, OCI digest, repository URL, or other existing identifier fits.
- [ ] I used `sameAs` only for equivalent identities and `isBasedOn` for forks, wrappers, clones, mirrors, and derivatives.
- [ ] I documented validation steps for any schema, API, package, container, trust, provenance, or deployment changes.

## Custom extensions introduced

<!-- List any new OpenAutonomyX/AgentNxt fields or say "None". -->

## Validation

<!-- Include commands, validators, or review steps used. -->

## Risk / migration notes

<!-- Any compatibility, migration, trust, provenance, or deployment impact. -->
