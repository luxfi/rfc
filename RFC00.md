# RFC 00: RFC Process

**Status:** Final
**Authors:** Lux maintainers
**Affected LRIs:** all (meta)

## Summary

Defines how Lux RFCs are written, reviewed, and accepted. RFCs are the
process for **cross-cutting** proposals; single-protocol changes belong
in [`luxfi/lps`](https://github.com/luxfi/lps).

## Scope

File an RFC when a proposal:

- Spans multiple LRIs (and so cannot be a single LP).
- Defines an org-wide process (governance, contribution flow, security
  disclosure, asset-listing criteria).
- Standardizes a cross-cutting interface that no single LP owns.

Otherwise: file an LP, file a PR, or open a Discussion.

## Lifecycle

| Stage | Meaning |
|-------|---------|
| **Draft** | PR opened with the RFC body. |
| **Review** | Maintainers iterate with the author. |
| **Final** | Accepted; implemented in the affected repos. |
| **Withdrawn** | Closed without acceptance. |

A maintainer may merge to `main` at any stage to preserve the
discussion. Status in the front-matter is authoritative. If maintainer
feedback goes unaddressed for two weeks the RFC is Withdrawn and may
not be re-submitted for 30 days.

## Submitting

1. Copy this file as `RFC<NN>.md` with the next unused integer.
2. Open a PR titled `RFC <NN>: <one-line summary>`.
3. Cite prior art and external sources.
4. Keep scope narrow.

## Template

```markdown
# RFC <NN>: <Title>

**Status:** Draft
**Authors:** <names + handles>
**Affected LRIs:** <list>
**Created:** <YYYY-MM-DD>

## Summary
One paragraph.

## Motivation
What problem does this solve? Why an RFC and not an LP or PR?

## Specification
Concrete description. Diagrams, schemas, pseudocode where useful.

## Rationale and alternatives
Why this design? What was rejected?

## Dependencies
Other RFCs / LPs / implementation work that must land first.

## Security considerations
New attack surface? Threat model? Interaction with Quasar consensus,
Pulsar threshold signing, M-Chain MPC, F-Chain FHE, Z-Chain proofs?

## Backwards compatibility
What breaks? Migration path?

## Reference implementation
Links to draft code.

## References
Prior art, papers, related LPs/RFCs.
```

## License

All RFCs are released under the project license. Submission implies
agreement.
