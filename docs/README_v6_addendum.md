# URF v6 Addendum — Ontology Alignment

This addendum describes the **v6 updates** to the semantic layer:

## What’s new vs v5
- `q_p` is explicitly **complex (U(1))**. Ontology adds `qpRe`, `qpIm`, and `qpAbsSq`, plus `hasU1Phase`.
- Triadic potential uses **|q_p|^2** (and optional `η'` offset term). Data properties `eta`, `etaPrime` added.
- Introduced **n-adic generalization**: class `NAdicNode` with `arity` and `hasComponent`.
- Consciousness becomes **continuous index** `C(t)`. Data property `consciousnessIndexC` added.

## Files
- `urf-v6-alignment.ttl` — new namespace `urf-v6#`, classes/properties above.
- `shapes/urf-v6-shacl.ttl` — validation with an `sh:or` requiring `(qpRe, qpIm)` **or** `qpAbsSq`.
- `examples/triadic-node-example-v6.ttl` — updated instance with complex q_p and η = 0.858.

## Relationship to URF v6 textbook
- See Part I §Limitations of Triadic Approximation (n-adic generalization).
- See Part II §Triadic Potential (U(1)-symmetric |q_p|^2 coupling).
- See Part III §Consciousness (continuous index C(t)).
- See Part IV §Quantum (path integral, renormalization).

