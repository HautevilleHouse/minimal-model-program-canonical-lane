# Reviewer Map

## Claim Scope

- Canonical-lane claim: inside the `manifold_constrained` routed lattice, if the theorem chain in this repository holds and the guard certificate passes, the repository-level super-lane closure claim is satisfied.
- Standard target claim: carried by the in-repo bridge theorems tying the lane to the target statement.

## Super-Lane Families

1. `klt and lc reduction packages across flips and divisorial contractions`
2. `canonical bundle formula and adjoint/Iitaka-fibration control packages`
3. `abundance and semiampleness endpoint packages for nef canonical classes`
4. `termination, scaling, and nonaccumulation packages for birational transitions`
5. `local-global stitching of the declared birational endpoint package`

## Theorem Dependency Chain

1. `EG1`: coercive response and active control floor.
2. `EG2`: capture and admissible continuation.
3. `EG3`: compactness and no-collapse spacing.
4. `EG4`: rigidity and transfer.
5. Identification bridge: strict coherence on the determining class.
6. Scalar closure: `MMP_G1`, `MMP_G2`, `MMP_G3`, `MMP_G4`, `MMP_G5`, `MMP_G6`, `MMP_GM` all `PASS`.

Primary files:

- `paper/MINIMAL_MODEL_PROGRAM_PREPRINT.md`
- `notes/EG1_public.md`
- `notes/EG2_public.md`
- `notes/EG3_public.md`
- `notes/EG4_public.md`
- `notes/IDENTIFICATION_BRIDGE.md`

## Closure Gates

| Gate | Constant | Description |
|------|----------|-------------|
| `MMP_G1` | `kappa_birational` | projected birational response has a strict positive floor |
| `MMP_G2` | `sigma_mori` | Mori-transition defect stays above capture floor across admissible flip and contraction losses |
| `MMP_G3` | `kappa_compact` | normalized near-failure families are precompact and admissible windows do not collapse |
| `MMP_G4` | `rho_rigidity` | bad birational countermodels are excluded |
| `MMP_G5` | `semiample_transfer` | rigid limit transfers to the minimal-model endpoint package |
| `MMP_G6` | `eps_coh` | strict coherence / identification closure |
| `MMP_GM` | derived | final strict margin |

## Falsification Conditions

- `repro/certificate_runtime.json` has any non-`PASS` gate.
- `lane.active_lane != "manifold_constrained"`.
- `all_pass != true`.
- Any manifest hash mismatch under `repro/repro_manifest.json`.
- A verified counterexample to any EG theorem statement used in the paper.
