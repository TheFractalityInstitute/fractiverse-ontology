# Fractality Ontology (URF v5 Alignment)

This folder contains the **semantic twin layer** of the Unified Resonance Framework (URF v5.0).  
It updates the original **Fractal Trinity Ontology (FTO)** to align with the rigorous field theory presented in the URF v5.0 textbook.

## Structure

- `urf-v5-alignment.ttl` – Core ontology definitions and mappings
  - Introduces URF classes: `urf:TriadicNode`, `urf:PhaseState` (+ Subcritical / Critical / Supercritical)
  - Defines measurable properties: `urf:surfaceVolumeRatio`, `urf:multiInformationRate`, `urf:phaseLockValueSPC`, `urf:consciousnessThresholdKappa`, etc.
  - Provides `skos:closeMatch` links from FTO heuristic categories (Energy / Information / Structure) to URF v5 triadic node components (qs / qp / qc).

- `shapes/urf-v5-shacl.ttl` – SHACL shapes for validation
  - Ensures each `urf:TriadicNode` has `qs`, `qp`, `qc` (floats).
  - Validates ranges for Is/v, PLV_spc, κ_crit, etc.

- `examples/triadic-node-example.ttl` – Minimal worked example
  - Shows one annotated Triadic Node instance with realistic values.

## Purpose

The Trinity Ontology (FTO) remains as a **pedagogical and semantic bridge**.  
URF v5 is the **formal physics substrate**. Together:

- **URF v5** → equations, predictions, experimental design  
- **FTO (v5.0 aligned)** → ontology layer for symbolic reasoning, AI systems, and cross-disciplinary communication  

## References

- **Canonical physics**: [URF v5.0 Textbook](../URF-v5_0-Textbook-1e.pdf)
- **Ontology home**: [fractiverse-ontology GitHub repo](https://github.com/TheFractalityInstitute/fractiverse-ontology)
