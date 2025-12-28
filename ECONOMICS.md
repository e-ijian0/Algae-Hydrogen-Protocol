# Economic Feasibility Analysis

This document breaks down the key cost drivers of the algae‑to‑hydrogen production process, based on a bench‑scale (5 L) photobioreactor system. The numbers are indicative and can be scaled for pilot (50 L) or industrial volumes.

## 1. Capital Expenditure (CapEx)

| Item | Specification | Unit Cost (USD) | Quantity | Total (USD) |
|------|---------------|-----------------|----------|-------------|
| Photobioreactor (flat‑panel) | Polycarbonate, 5 L working volume, integrated airlift | 800 | 1 | 800 |
| Temperature control | Water jacket + chiller/heater (PID) | 1,200 | 1 | 1,200 |
| Lighting system | LED panels (680 nm peak), 150 µmol m⁻² s⁻¹ | 400 | 2 | 800 |
| CO₂ supply system | Regulator, flowmeter, gas mixer | 300 | 1 | 300 |
| Pumps & tubing | Peristaltic pump, silicone tubing, connectors | 250 | 1 | 250 |
| Gas collection setup | Gas bags, valves, bubble‑flow meter | 150 | 1 | 150 |
| Sterilization equipment | Autoclave (shared facility) | (shared) | – | – |
| **Total CapEx** | | | | **3,500** |

*Note: Costs assume fabrication in‑house; commercial turn‑key systems are 2–3× more expensive.*

## 2. Operating Expenditure (OpEx) per Batch (5 L culture, 7‑day cycle)

### 2.1 Nutrients & Chemicals
- **TAP medium components** (for 5 L):
  - Tris base: 12.1 g → $0.50
  - Acetic acid (glacial): 5 mL → $0.30
  - NH₄Cl: 1.875 g → $0.20
  - MgSO₄·7H₂O: 0.5 g → $0.10
  - CaCl₂·2H₂O: 0.25 g → $0.05
  - Phosphate salts: 0.82 g → $0.15
  - Trace elements (Hunter’s mix): 5 mL → $0.25
  - **Total nutrients**: ~$1.55 per batch.

### 2.2 Gases
- **CO₂**: 2 % in air, 0.3 vvm for 5 L → ~0.3 L min⁻¹ CO₂.
  - Over 7 days (10,080 min) → 3,024 L CO₂ = 3.024 m³.
  - Bulk CO₂ cost: $0.10 m⁻³ → $0.30 per batch.
- **Argon/N₂ for anaerobiosis**: 10 min flush at 1 L min⁻¹ → 10 L ≈ $0.05.
- **Total gases**: $0.35 per batch.

### 2.3 Energy Consumption
- **LED lights**: 2 panels × 40 W each = 80 W, continuous for 7 days (168 h) → 13.44 kWh.
- **Chiller/heater**: 100 W average → 16.8 kWh.
- **Pump & airlift compressor**: 20 W → 3.36 kWh.
- **Total energy**: 33.6 kWh per batch.
- Electricity cost @ $0.12 kWh⁻¹: **$4.03 per batch**.

### 2.4 Labor
- **Preparation, inoculation, monitoring, harvest**: 2 h per batch × $25 h⁻¹ = $50.
- *Note: Labor dominates small‑scale costs; automation reduces this significantly at scale.*

### 2.5 Total OpEx per Batch
| Category | Cost (USD) |
|----------|------------|
| Nutrients | 1.55 |
| Gases | 0.35 |
| Energy | 4.03 |
| Labor | 50.00 |
| **Total** | **55.93** |

## 3. Hydrogen Output and Revenue

- **Typical yield**: 100–150 mL H₂ per liter culture per batch (5 L → 0.5–0.75 L H₂).
- **Energy content**: 0.75 L H₂ ≈ 0.067 mol × 286 kJ mol⁻¹ = 19.2 kJ (5.3 Wh).
- **Market value of hydrogen**: Bulk green H₂ price ~$5 kg⁻¹. 0.75 L H₂ = 0.067 g → negligible monetary value at bench scale.

*The current bench‑scale process is **not economically viable** for hydrogen sales alone.* The primary value lies in protocol development, strain improvement, and scaling studies.

## 4. Cost‑Reduction Strategies

### 4.1 Scaling Effects
- **CapEx per liter** decreases dramatically with volume (economies of scale).
- **Labor** can be distributed over larger batches (e.g., 50 L requires only ~3× the labor of 5 L).
- **Energy efficiency**: LED efficacy improves; heat integration reduces cooling needs.

### 4.2 Alternative Nutrient Sources
- Use wastewater or agricultural runoff as nutrient supply (cuts nutrient cost to near zero).
- Replace purified CO₂ with flue gas (after scrubbing) or biogas.

### 4.3 Process Intensification
- **Continuous culture** instead of batch: higher volumetric productivity, lower downtime.
- **Immobilized algae** on cheap substrates reduces harvesting cost.
- **Hybrid systems** that co‑produce high‑value compounds (carotenoids, proteins) alongside H₂.

### 4.4 Photobioreactor Design Optimization
- **Thin‑film reactors** with ultra‑short light paths (<5 mm) boost light utilization.
- **Outdoor cultivation** using sunlight eliminates lighting energy cost (but adds weather dependence).
- **Modular, stackable panels** reduce material costs per unit volume.

## 5. Break‑Even Projections

For a hypothetical 50 L pilot system operating continuously:
- **CapEx**: $15,000 (estimated)
- **Annual OpEx**: $10,000 (nutrients, energy, minimal labor)
- **Annual H₂ output**: 3,000 L (≈ 0.27 kg) → value ~$1.35 (still negligible).
- **Co‑product revenue**: If algae biomass is sold as feed supplement ($5 kg⁻¹) and 50 kg biomass is produced annually → $250 revenue.

*Conclusion*: Stand‑alone hydrogen production from algae is currently not cost‑competitive with conventional hydrogen (steam methane reforming) or even other green‑hydrogen routes (PV‑electrolysis). The pathway to economic feasibility requires:
1. **Dramatic improvement in hydrogen yield** (10–100×) through genetic engineering or novel reactor designs.
2. **Valorization of the residual biomass** for higher‑value products (pharmaceuticals, nutraceuticals).
3. **Integration into a circular‑economy framework** where algae treat waste streams and produce H₂ as a bonus.

## 6. References
1. Oncel, S.S. (2013). *Bioresource Technology* 135, 598–607.
2. Ghirardi, M.L., et al. (2009). *Photosynthesis Research* 102, 523–540.
3. Huesemann, M.H., et al. (2010). *Biofuels, Bioproducts and Biorefining* 4, 287–302.