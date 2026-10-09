# Hodge

> **Canonical repository:** https://github.com/redogit/hodge · **Public page:** https://redogit.github.io/hodge/

Correspondences, exact computations, research records, bounded Hodge tooling, and the live Hodge command/event laboratory.

As of **2026-10-08**, this repository is the canonical home for Hodge-specific research that previously lived under `redogit/conscience64` and `redogit/Other-Projects-`. The original repositories and commits remain historical provenance; new Hodge-owned development should land here.

## Start here

- [Current Hodge research spine](research/hodge/README.md)
- [Canonical project state](research/projects/hodge-conjecture.md)
- [Hodge Lab v0.2 conformance suite](research/hodge/conformance/README.md)
- [Hodge Span Lab](research/span-lab/README.md)
- [Hodge Compass API](tools/compass-api/README.md)
- [Hodge perturbation experiment](experiments/hodge-perturbation-game/README.md)

## Canonical layout

```text
research/hodge/                  target-native Hodge research + W114
research/projects/               canonical project state
research/span-lab/               exact span / deformation diagnostics
tools/compass-api/               provenance-first search and proof graph
experiments/hodge-perturbation-game/
evidence/                        retained run evidence and contracts
```

The older `conscience64/` and `Other-Projects-/` trees are retained as **historical export snapshots**. They are not the forward development surface. Compatibility symlinks preserve the former root names for tools that still expect them.

## Authority boundary

```text
SOFTWARE_VERIFICATION != MATHEMATICAL_PROOF
METHOD_TRANSFER != EVIDENCE_TRANSFER
CALIBRATION_RESULT != OPEN_PROBLEM_RESULT
SIMILARITY != SOURCE_IDENTITY
VISUALIZATION != EVIDENCE_PROMOTION
TIMEOUT != NEGATIVE_RESULT
```

The Hodge conjecture is not established by this repository. W114/MOT-1 remains an open research obligation wherever the current target-native state says it is open.

## Validate locally

Python 3 and Node.js are required for the canonical validation suite.

```sh
python validate.py --integrity-only
python validate.py
```

Individual checks can be selected with `--check NAME`; exact commands are in [VALIDATE.json](VALIDATE.json).

## Provenance

- [CANONICAL_MIGRATION_2026-10-08.json](CANONICAL_MIGRATION_2026-10-08.json) records the source revisions and migration scope that established this repository as the canonical Hodge home.
- `EXPORT_PROVENANCE.json`, `EXPORT_DEPENDENCIES.json`, and `EXPORT_EXCLUSIONS.json` remain the historical standalone-export record and are intentionally not rewritten.
- Historical source paths and commit history remain available in their predecessor repositories; migration does not convert cross-project methods into Hodge evidence.
