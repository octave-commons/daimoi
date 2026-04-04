# daimoi

Design notes for **Daimoi** field physics, static-observer measurement, and signal-to-noise metrics.

## Reading order

1. `docs/INDEX.md` — repo map and navigation
2. `docs/snr-metrics.md` — non-arbitrary SNR metrics for daimoi populations and field-following behavior
3. `docs/FORK_TALES_SOURCE_MAP.md` — the upstream `fork_tales` files and notes behind the concept
4. `docs/OPENCODE_SESSION_PROVENANCE.md` — later session artifacts that kept the decomposition alive
5. `specs/field-model.md` — minimal operational model for daimoi state and movement
6. `specs/ownership-collision-and-observer.md` — explicit ownership, collision, and governance rules
7. `specs/extraction-roadmap.md` — path from dense Part64 subsystem to standalone package

## Status

Exploratory design repo extracted from the devel workspace, with explicit provenance back to the original `fork_tales` runtime and the later recovery sessions.

## Adjacent repos

- `octave-commons/graph-runtime` — graph/topology/resource substrate
- `octave-commons/simulacron` — layered entities served by casts of presences
