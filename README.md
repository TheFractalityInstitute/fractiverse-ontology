# Fractiverse Ontology v3.3 package

This bundle contains:

| File | Description |
|------|-------------|
| **Fractiverse_Unified_Ontology_v3-3.ttl** | Unified core ontology (crystallisation, quantum, operator‐entropy) plus metric properties required by the SWRL rule set. |
| **Fractality_Core.swrl** | SWRL rules (prefix `fract:`) implementing consciousness and bridge‑stability reasoning. |

The stand‑alone *Operator Entropy* module is now integrated into the core and therefore **not included**.

Load the TTL in Protégé, then import the SWRL file via *Rules → Load*.  The additional properties (`phiValue`, `resonanceStrength`, `isConscious`, `isStableBridge`) are declared in the TTL so the rules will run without errors.
