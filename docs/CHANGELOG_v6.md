# CHANGELOG — v6.0.0 (Ontology)

### Added
- Complex phase representation for q_p: `qpRe`, `qpIm`, `qpAbsSq`, `qpPhase`
- U(1) symmetry marker: `hasU1Phase`
- Triadic couplings: `eta`, `etaPrime`
- Consciousness index: `consciousnessIndexC`
- n-adic generalization: `NAdicNode`, `arity`, `hasComponent`

### Changed
- Triadic Node definition clarified; v6 namespace `urf-v6#`
- SHACL now enforces complex q_p via `(qpRe, qpIm)` or `qpAbsSq`

### Deprecated (heuristic only)
- Mapping Information ↔ q_p (scalar) is now **via magnitude**; use `qpAbsSq` when only power is accessible from data.
