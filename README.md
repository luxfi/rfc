# luxfi/rfc

Cross-cutting RFCs for the Lux ecosystem. Protocol specs go in
[`luxfi/lps`](https://github.com/luxfi/lps); this repo hosts proposals
that span multiple LRIs (process, governance, org-wide standards).

## RFC vs LP

- **LP** ([`luxfi/lps`](https://github.com/luxfi/lps)) — protocol-level
  spec (consensus, crypto, chain topology, network upgrades). One
  protocol, one LP. **Primary process.**
- **RFC** (this repo) — cross-cutting / process / multi-LRI proposals.
  Use only when a proposal does not fit a single LP.

If unsure, file an LP.

## Lifecycle

`Draft → Review → Final / Withdrawn`

A merge into `main` makes the discussion permanent; status lives in
the RFC's own front-matter.

## Submitting

1. Copy [`RFC00.md`](./RFC00.md) as a template.
2. PR titled `RFC <NN>: <one-line summary>`.
3. Cite prior art. Keep scope narrow.

## Index

| RFC | Title | Status |
|-----|-------|--------|
| [00](./RFC00.md) | RFC Process | Final |
