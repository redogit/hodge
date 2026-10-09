# W114 perturbation surfaces

Hodge-owned runtime adapters for the W114 perturbation experiment.

## Contents

- `android/` — local Android wrapper of the perturbation surface. It has no INTERNET permission and retains the static verification contract from the predecessor repository.
- `rmaos/` — the W114-specific RMAL circuit and field shader. The generic RMAOS MiniGX runtime remains shared infrastructure in `redogit/Other-Projects-`; these files do not transfer ownership of that runtime.

The canonical browser experiment remains at [../hodge-perturbation-game](../hodge-perturbation-game/).

## Boundaries

```text
APK_BUILD_PASS != DEVICE_RUNTIME_PASS
ROBUST_GAME_CANDIDATE != ALGEBRAIC_CYCLE
GAME_SCORE != MATHEMATICAL_EVIDENCE
SOFTWARE_VERIFICATION != MATHEMATICAL_PROOF
METHOD_DEPENDENCY != EVIDENCE_TRANSFER
```
