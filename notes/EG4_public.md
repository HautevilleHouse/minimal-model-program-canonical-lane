# EG4 Public Note (Rigidity and Endpoint Transfer)

Canonical wording: `bad-limit exclusion / endpoint transfer`.

In-paper anchor: `paper/MINIMAL_MODEL_PROGRAM_PREPRINT.md` (`MMP_G4`, `MMP_G5`).

## Goal
Separate the rigidity job from the endpoint-transfer job for `proving existence and persistence of the declared minimal-model and Mori-fiber endpoint packages across admissible birational reductions through a multi-lane birational super-architecture`.
The older wording `rigidity and endpoint-transfer` corresponds to bad-limit exclusion plus the bridge into the intended endpoint object.

## Objects

- bad-limit class: candidates extracted by the compactness gate but incompatible with closure.
- rigidity floor: `rho_rigidity`.
- endpoint-transfer lock: `semiample_transfer`.
- coherence interface: `eps_coh` remains available to the bridge and final margin.

## Closure Criterion

`MMP_G4` closes when `rho_rigidity` excludes bad endpoint alternatives: bad birational countermodels are excluded.
`MMP_G5` closes when `semiample_transfer` transfers the surviving endpoint to the intended target class: rigid limit transfers to the minimal-model endpoint package.
Together they feed the strict margin `M_MMP`.

## Lemma Chain and Proof Payload

### Lemma EG4.1 (bad-limit exclusion)
Every extracted bad limit contradicts a declared rigidity constraint or leaves the admissible class.

Payload: check `rho_rigidity` in the registry and certificate surfaces.

### Lemma EG4.2 (endpoint transfer)
The surviving rigid representative is locked to the standard problem-side endpoint by `semiample_transfer`.

Payload: read this note together with `notes/IDENTIFICATION_BRIDGE.md`.

### Theorem EG4.3 (rigidity/transfer gate closure)
If bad limits are excluded and the endpoint lock is active, then `MMP_G4` and `MMP_G5` deliver the boundary object needed by the final margin.

## Current Instantiation

- rigidity gate: `MMP_G4`
- rigidity artifact key: `rho_rigidity`
- transfer gate: `MMP_G5`
- transfer artifact key: `semiample_transfer`
- canonical equivalent: `bad-limit exclusion / endpoint identification`
- audit surface: `notes/IDENTIFICATION_BRIDGE.md` and `repro/certificate_runtime.json`
