# Std 2800 (5th ed.) – Irregularities (distilled from uploaded Std2800-V5Irregularities.pdf)
Source note: summary of the user's uploaded document; verify clause numbers against the official text before citing.

## Plan irregularities
- Geometric (re-entrant corners): >20% in both directions (ASCE 7-22 uses 15%).
- Torsional: TIR = Δmax/Δavg; >1.2 torsional irregularity, >1.4 severe. Accidental eccentricity 5%, Aj=1, rigid/semi-rigid diaphragm. ETABS: table "Diaphragm Max Over Avg Drifts".
- Diaphragm: stiffness change >50% in a bay; openings >25% of area.
- Out-of-plane offset: columns under discontinuous walls checked for Ω0E.
- Non-parallel systems.

## Height irregularities
- Geometric >130%; mass >1.5x adjacent floors (mass per clause 3-7-4; lighter roof exempt); in-plane discontinuity.
- Weak story <85% (very weak <65%).
- Soft story <70% of story above or <80% of avg of 3 above (very soft <60% / <70%).
- Story strength by mechanism: Vyi = 2ΣMpc/H (column mech.), Vyi = 2ΣMpG/H (beam mech.) (AISC 2005 commentary).
- ETABS story stiffness: copy file, fix story base, apply 10 t pattern, K = F/Δ.

## Restrictions (clause 3-3-3, as stated in the document)
- Very weak story: not allowed in any seismic design group.
- SDC-3: very soft story, weak story, severe torsional irregularity not allowed.
- 5th ed. requires strong-column/weak-beam for intermediate RC moment frames (ΣMnc ≥ ΣMnb at each joint) in addition to Mabhas 9.
