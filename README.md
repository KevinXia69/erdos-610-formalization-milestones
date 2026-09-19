# Erdős 610 Lean Formalization — Public Milestones

This repository records public milestones, provenance, and reproducibility metadata for an ongoing Lean formalization of Erdős Problem 610.

The complete proof implementation is kept in a private development repository while the core proof work is in progress. This repository therefore does **not** claim that Erdős 610 has been fully formalized, proved, or accepted for a prize.

## What is public here

- the target problem and statement-alignment scope;
- high-level milestone descriptions;
- toolchain and dependency identifiers;
- authorship and provenance records;
- timestamped commitments to private development snapshots.

The repository intentionally omits the private proof core, detailed proof architecture, incomplete-proof diagnostics, and implementation details that would make the unfinished construction directly reusable.

## Current status

As of 2026-09-19, the project has compiled Lean interfaces for statement alignment, graph-to-transversal reductions, lower-bound input boundaries, finite execution infrastructure, and audit scaffolding. The final Erdős 610 theorem is not yet closed.

The public status is therefore:

```text
statement aligned:       yes
substantial interfaces:   yes
final theorem:            no
custom placeholder axiom: no claim of absence for the private core
award eligibility:        not claimed
```

## Priority and verification

The snapshot commitment in `SNAPSHOT_COMMITMENT.json` records the identifier and digest of a development snapshot. It is evidence of project existence at a point in time; it is not a substitute for an independently checkable final Lean proof.

When the final proof is ready, the project will publish the fixed source, build log, axiom-audit output, provenance, and independent rebuild evidence before making any award claim.

## License and attribution

See [`PROVENANCE.md`](PROVENANCE.md) for authorship, AI assistance, external mathematical sources, and the current status of the formalization.
