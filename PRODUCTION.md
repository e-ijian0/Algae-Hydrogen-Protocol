# Hydrogen Production from Algae

This protocol describes the induction, collection, and measurement of hydrogen gas produced by sulfur‑deprived algae.

## 1. Principle
Under sulfur‑deficient conditions, the green alga *Chlamydomonas reinhardtii* down‑regulates photosystem II (PS II) activity while maintaining photosystem I (PS I) activity. This creates an anaerobic environment inside the cells, activating the [FeFe]‑hydrogenase enzyme that catalyzes the reduction of protons to molecular hydrogen (H₂) using electrons derived from water splitting and/or stored carbohydrates.

## 2. Sulfur Deprivation
- **Medium preparation**: Prepare Tris‑Acetate‑Phosphate medium without sulfate (TAP‑S).
  - Omit MgSO₄·7H₂O; replace with equimolar MgCl₂·6H₂O (0.1 g L⁻¹ → 0.083 g L⁻¹ MgCl₂·6H₂O).
  - Omit (NH₄)₂SO₄ if present; use NH₄Cl as nitrogen source.
- **Wash step**: Harvest algae from normal growth medium by centrifugation (5000 × g, 10 min, 4 °C). Resuspend pellet in TAP‑S medium to remove residual sulfur.
- **Cell concentration**: Adjust to a final chlorophyll concentration of 20–25 µg mL⁻¹ (or OD₇₅₀ ≈ 1.5–2.0) for optimal H₂ production.

## 3. Induction Setup
- **Reactor vessel**: Use the same flat‑panel photobioreactor as for cultivation, but seal it to create a closed gas‑tight system.
- **Headspace flushing**: Before sealing, flush the headspace with argon or nitrogen for 10 min to remove oxygen.
- **Temperature**: 25 ± 1 °C.
- **Light intensity**: 50–100 µmol photons m⁻² s⁻¹ (lower than growth light to reduce PS II damage).
- **Agitation**: Gentle magnetic stirring (100 rpm) or airlift with argon (0.1 vvm) to keep cells suspended without introducing oxygen.

## 4. Gas Collection System
- **Gas outlet**: Connect the reactor’s headspace to a gas‑collection apparatus via sterile tubing.
- **Water displacement method**: 
  1. Fill a graduated cylinder with acidified water (0.1 M H₂SO₄) and invert it into a water bath.
  2. Lead the gas tubing to the bottom of the cylinder; evolved gas displaces water, allowing volume measurement.
- **Gas bag method**: Use foil‑lined gas‑sampling bags (e.g., Cali‑5‑Bond) with one‑way valves to collect cumulative gas.
- **Online monitoring**: Connect a gas flowmeter (e.g., bubble‑flow meter) or a mass‑spectrometer inlet for real‑time H₂ quantification.

## 5. Hydrogen Measurement
- **Gas chromatography (GC)**:
  - Inject 100 µL of headspace gas into a GC equipped with a thermal conductivity detector (TCD) and a molecular‑sieve column (e.g., 5 Å, 2 m × 1/8″).
  - Carrier gas: argon or nitrogen at 30 mL min⁻¹.
  - Column temperature: 50 °C; detector temperature: 100 °C.
  - Calibrate with standard gas mixtures (H₂ in N₂, 1–10 % v/v).
- **Electrochemical sensor**: Use a portable H₂ sensor (e.g., H₂‑Trace) for quick, approximate readings.
- **Calculation of total H₂ produced**:
  \[
  H_2\;(\text{mmol}) = \frac{P \cdot V}{R \cdot T} \cdot x_{H_2}
  \]
  where \(P\) = atmospheric pressure (atm), \(V\) = total gas volume (L), \(R\) = 0.0821 L·atm·mol⁻¹·K⁻¹, \(T\) = temperature (K), and \(x_{H_2}\) = mole fraction of H₂ in the gas.

## 6. Typical Timeline
- **Lag phase (0–24 h)**: Residual sulfur is consumed; O₂ evolution decreases, culture becomes anaerobic.
- **Hydrogen production phase (24–96 h)**: H₂ evolution peaks around 48–72 h, then gradually declines as stored carbohydrates are exhausted.
- **Cessation (after 96 h)**: Production stops; cells can be re‑fed with sulfur to restart growth.

## 7. Yield Optimization
- **Pre‑culture conditioning**: Grow algae under high‑light (200 µmol m⁻² s⁻¹) with elevated CO₂ (5 %) to boost starch reserves.
- **Chlorophyll concentration**: Keep below 25 µg mL⁻¹ to avoid self‑shading and ensure uniform anaerobiosis.
- **pH control**: Maintain pH 7.0–7.5; a slight drop (pH 6.8) can enhance hydrogenase activity.
- **Additives**: 10 mM acetate (as in TAP medium) sustains metabolism; higher acetate (up to 30 mM) may increase H₂ yield but can inhibit growth.

## 8. Safety Considerations
- **Hydrogen flammability**: H₂/air mixtures are explosive at 4–75 % (v/v). Work in well‑ventilated areas, avoid sparks, and use leak‑proof connections.
- **Anaerobic conditions**: Avoid introduction of oxygen after induction, as O₂ irreversibly inactivates [FeFe]‑hydrogenase.
- **Gas disposal**: Vent collected H₂ through a fume hood or burn it in a controlled flare if large quantities are generated.

## 9. Troubleshooting
- **No H₂ detected**: Check sulfur deprivation (ensure complete washing), verify anaerobiosis (use methylene‑blue indicator), test hydrogenase activity with dithionite‑reduced methyl viologen assay.
- **Low yield**: Increase starch reserves by longer growth phase, optimize light intensity during production, reduce chlorophyll concentration.
- **Culture contamination**: Discard batch; sterilize reactor and use fresh axenic inoculum.

## 10. References
1. Melis, A., & Happe, T. (2001). *Plant Physiology* 127, 740–748.
2. Ghirardi, M.L., Posewitz, M.C., Maness, P.C., et al. (2007). *Annual Review of Plant Biology* 58, 71–91.
3. Kosourov, S., Patrusheva, E., Ghirardi, M.L., et al. (2007). *Applied Biochemistry and Biotechnology* 143, 80–89.