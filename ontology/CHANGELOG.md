# CHANGELOG – Fractality Ontology

## v5.0.0 – August 2025
Alignment with **Unified Resonance Framework v5.0**

### Added
- New namespace: `urf:` (https://fractality.institute/ontology/urf-v5#)
- Class `urf:TriadicNode` with components:
  - `urf:qs` (spatial)
  - `urf:qp` (phase)
  - `urf:qc` (scale)
- Class `urf:PhaseState` with individuals `urf:Subcritical`, `urf:Critical`, `urf:Supercritical`
- Properties for measurable URF quantities:
  - `urf:surfaceVolumeRatio` (Is/v)
  - `urf:multiInformationRate` (∂Imulti/∂t)
  - `urf:phaseLockValueSPC` (PLV_spc)
  - `urf:consciousnessThresholdKappa` (κ_crit)
  - `urf:triadicCouplingEta` (η)
  - `urf:nonMinimalCouplingXi` (ξ)
  - `urf:informationalEquilibrium` (boolean)
- SHACL shapes for validation of TriadicNode instances
- Example file (`examples/triadic-node-example.ttl`) with one annotated node

### Changed
- Ontology header updated with `owl:versionInfo "5.0.0"` and reference to URF v5 textbook
- FTO heuristic categories (Energy, Information, Structure) linked via `skos:closeMatch` to URF node components (qs, qp, qc)

### Deprecated
- Older FTO-only terms overlapping with qs/qp/qc should now be considered **heuristic only**; URF mappings are canonical.

---

For prior changes see earlier versions in repository history.
