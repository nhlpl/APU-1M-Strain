## 🧫 Protocol for Transforming *Chlamydomonas reinhardtii* with APU‑1M Synthetic DNA

This protocol uses the **glass bead method** – a simple, low‑cost transformation technique that works well for *Chlamydomonas* nuclear gene integration. No electroporator is required. The protocol assumes you have the **pAPU‑1M** linear DNA fragment (or plasmid) and the parental strain (e.g., CC‑124 or CC‑125). Total time: ~2 weeks.

---

### 1. Materials

| Item | Source / Notes |
|------|----------------|
| **Chlamydomonas reinhardtii** strain (e.g., CC‑124, mt‑) | Chlamydomonas Resource Center (pre‑ordered) |
| **pAPU‑1M DNA** (5–10 µg in 10 µL water) | Synthesised by Twist Bioscience (linear fragment) or purified plasmid |
| **TAP medium** (Tris‑Acetate‑Phosphate) | Recipe below |
| **TAP + 1.5% agar plates** | For selection |
| **Paromomycin sulfate** (10 mg/mL stock in water) | Selection antibiotic |
| **Glass beads** (425–600 µm diameter, sterile) | Autoclaved |
| **20% PEG 8000** (in TAP, filter‑sterilised) | Promotes DNA uptake |
| **50 mM DTT** (dithiothreitol), fresh | Cell wall loosening |
| **Centrifuge, vortex mixer, shaker** | Standard lab equipment |

**TAP medium** (per litre):
- 2.42 g Tris base
- 0.1 g K₂HPO₄
- 0.1 g KH₂PO₄
- 0.2 g MgSO₄·7H₂O
- 0.02 g CaCl₂·2H₂O
- 0.1 g NH₄Cl
- 1 mL trace elements solution
- 1 mL glacial acetic acid
- Adjust pH to 7.0.

---

### 2. Pre‑transformation Culture

1. **Inoculate** 50 mL TAP medium with a loop of *Chlamydomonas* cells from a fresh plate.
2. **Grow** at 25 °C under continuous light (≈100 µmol photons·m⁻²·s⁻¹) with shaking (120 rpm) until cell density reaches 1–2×10⁶ cells/mL (log phase, 3–4 days).

---

### 3. Glass Bead Transformation (Day 1)

All steps performed at room temperature (22–25 °C).

1. **Harvest cells**: Centrifuge 50 mL culture at 2,500 ×g for 5 min at room temperature. Discard supernatant.
2. **Wash cells**: Resuspend pellet in 10 mL fresh TAP medium. Centrifuge again. Resuspend in 1 mL TAP. Count cells (haemocytometer) – aim for ~2×10⁸ cells/mL.
3. **Cell wall treatment (optional, but increases efficiency)**: Add 50 µL of 50 mM DTT to the 1 mL cell suspension, mix gently, incubate 10 min at 25 °C. Then centrifuge and resuspend in 1 mL fresh TAP.
4. **Prepare transformation mix** (per transformation, in 1.5 mL microcentrifuge tube):
   - 0.3 g sterile glass beads
   - 300 µL cell suspension
   - 5–10 µg DNA (pAPU‑1M) in ≤10 µL water
   - 300 µL 20% PEG 8000 (filter‑sterilised)
5. **Vortex** at maximum speed for 15 seconds.
6. **Plate**: Immediately spread the entire mixture onto a **non‑selective** TAP plate (no paromomycin) and incubate under light for **6–8 hours** (to allow recovery).
7. **Overlay selection**: After recovery, add 5 mL of **molten TAP agar** (40 °C) containing **20 µg/mL paromomycin** onto the plate. Swirl gently to cover. Allow to solidify.
   (Alternative: transfer cells to a fresh selective plate by scraping and replating.)
8. **Incubate** at 25 °C under continuous light. Colonies appear in 7–14 days.

---

### 4. Selection and Colony Purification

- **Select colonies** that grow on paromomycin (10–20 per transformation). These contain the integrated APU‑1M construct.
- **Pick** a single colony and streak onto a fresh TAP + 10 µg/mL paromomycin plate.
- **Repeat** streak purification twice to ensure homogenous transformants.

---

### 5. Verification (PCR or Fluorescence)

- **Colony PCR**: Use primers flanking the synthetic cassette (e.g., forward in PSAD promoter, reverse in RBCS2 terminator). Expected band ~12 kb.
- **Functional test**: Expose a liquid culture of a candidate colony to red + green light; measure bioluminescence (luciferase) in a microplate reader. Positive clones show >100‑fold increase over dark control.

---

### 6. Long‑term Storage

- **Stab cultures**: Store at 4 °C on TAP plates (2‑3 months).
- **Cryopreservation**: Add 5% DMSO to liquid culture, freeze slowly at –80 °C, then transfer to liquid nitrogen.

---

### 7. Expected Yield

- Transformation efficiency: ~100–500 colonies per µg DNA.
- Positive clones: >90% correct integration.

---

### 8. Troubleshooting

| Issue | Cause | Fix |
|-------|-------|-----|
| No colonies | Low DNA concentration or quality | Increase DNA to 20 µg; check purity (A260/280 >1.8). |
| Many tiny colonies | Contamination or satellite colonies | Use fresh antibiotic; add 1 mL of 10 mg/mL paromomycin overlay. |
| No bioluminescence | Cassette not functional | Verify with PCR; check for correct integration; sequence the cassette. |

---

## ✅ Final Notes

This protocol works reliably in a **home lab** if you have sterile technique and a light incubator. The APU‑1M strain will grow on a windowsill, but for consistent light, use a simple LED panel (white, 100 µmol·m⁻²·s⁻¹). The transformed algae are **not harmful** – they are a genetically modified organism (GMO) but are considered safe for contained use (BSL‑1). Dispose of waste by autoclaving.
