# 03 — Solar PV Technology Review

## Technology landscape (2025)

Polycrystalline panels: **0% market share** — fully phased out of commercial manufacturing.
Monocrystalline silicon: **~100% of commercial PV market**.

### Cell architectures

| Technology | Efficiency | Cost (USD/W) | Notes |
|------------|-----------|--------------|-------|
| PERC monocrystalline | 20–22% | $0.85–$1.10 | Baseline cost-performance option |
| Bifacial monocrystalline | 21–23% | $0.90–$1.20 | +10–30% yield from rear surface |
| TOPCon (JinkoSolar Tiger Neo, LONGi Hi-MO X10) | 24–24.8% | $1.00–$1.30 | Current commercial efficiency leader |
| HJT (SunPower Maxeon 7, AIKO Neostar) | 24.1–26% | $1.20–$1.50 | Best low-light performance |
| Thin-film (CdTe, CIGS) | 10–13% | $0.50–$0.80 | Not recommended for Zambia |

**Recommendation for Zambia:** Bifacial TOPCon or PERC, 22–24% efficiency tier.

## Zambia solar resource

| Parameter | Value |
|-----------|-------|
| Global Horizontal Irradiation (annual) | 1,900–2,100 kWh/m² |
| Average daily irradiance | 5.5–5.78 kWh/m²/day |
| Annual sunshine hours | ~4,403 hours |
| Specific PV yield | 1,550–1,700 kWh/kWp/year |
| Seasonal variability | Low (bankability advantage) |
| Peak summer ambient temperature | 30–35°C |
| Cell temperature at peak | 50–60°C |
| Temperature derating (mono PERC) | ~8–12% at peak conditions |

## Performance ratio assumptions

For a Copperbelt plant with bifacial TOPCon modules:

| Loss component | Derating |
|----------------|---------|
| Inverter losses | ~3% |
| Cable losses | ~1.5% |
| Soiling | ~3% (maintained by wash system) |
| Temperature derating | ~8% |
| Availability | ~2% |
| **Total PR** | **~0.82** |

---

# 04 — Generation Capacity and Cost Analysis

## Yield model

For a 10 MW plant, bifacial TOPCon, Copperbelt GHI 2,050 kWh/m²/yr:

```
Annual generation = 10 MWp × 1,600 kWh/kWp × 0.82 (PR) = 13,120 MWh/year
```

## Scale projections

| Plant Scale | Annual Yield (MWh) | Land (ha) | CO₂ Displaced (t/yr) | Revenue @ $0.07/kWh |
|-------------|-------------------|-----------|----------------------|---------------------|
| 1 MW | 1,312 | 2–3 | 900 | $91,840 |
| 5 MW | 6,560 | 8–12 | 4,500 | $459,200 |
| 10 MW | 13,120 | 16–22 | 9,000 | $918,400 |
| 25 MW | 32,800 | 40–55 | 22,650 | $2,296,000 |
| 50 MW | 65,600 | 80–110 | 45,300 | $4,592,000 |

## CAPEX structure (5–25 MW, Zambia, 2025)

| Component | USD/kWp | % of Total |
|-----------|---------|------------|
| PV modules (bifacial TOPCon) | $250–$350 | 30–35% |
| Inverters | $60–$90 | 8–10% |
| Mounting structures | $80–$120 | 10–12% |
| DC and AC cabling | $40–$70 | 6–8% |
| Substation interconnection | $30–$60 | 4–6% |
| Civil works and ground prep | $50–$80 | 7–9% |
| EPC management | $60–$90 | 8–10% |
| Logistics and customs | $30–$50 | 4–5% |
| Contingency and commissioning | $40–$70 | 5–7% |
| **Total** | **$640–$980** | **100%** |

## 10 MW financial summary

| Parameter | Value |
|-----------|-------|
| Total CAPEX | USD 8.0–9.8 million |
| Annual generation | 13,120 MWh |
| PPA tariff | USD 0.065–0.085/kWh |
| Annual revenue (at $0.075/kWh) | USD 984,000 |
| Annual O&M (1.5% of CAPEX) | USD 135,000 |
| Net annual cash flow (pre-debt) | ~USD 849,000 |
| Simple payback | 10–12 years |
| LCOE (25-yr, 8% discount rate) | USD 0.038–0.055/kWh |
| IRR (equity, 25-year) | 12–18% |

---

# 05 — Transmission Infrastructure

## Overhead lines (OHL)

### Costs
- 69 kV single-circuit OHL: ~USD 285,000/mile (~USD 177,000/km) [US benchmark]
- 33 kV OHL in Zambia: ~USD 60,000–100,000/km (20–30% lower due to local labour costs)

### Advantages
- 4–14× cheaper than underground per km
- Easier fault location and repair (visual inspection)
- Established local ZESCO maintenance expertise
- No reactive power compensation required (short distances)

### Disadvantages
- Habitat fragmentation: 10–30m ROW clearing required
- Vulnerable to lightning, wind loading, tree-on-line failures
- Ongoing ROW vegetation maintenance cost (~USD 1–3/kWp/year)
- Incompatible with agrivoltaic land use beneath panels
- Visual impact — community acceptance friction

## Underground cables (UGC)

### Costs
- 69 kV UGC: ~USD 1.5M/mile (~USD 932,000/km) without terminals [US benchmark]
- 33 kV UGC in Zambia: ~USD 150,000–350,000/km

### Advantages
- Zero habitat disruption — surface returns to natural/agricultural state within months
- Unaffected by lightning or storms
- No ROW maintenance cost
- Fully compatible with agrivoltaic land use (goat grazing, beekeeping above route)
- Superior community acceptance for land negotiations
- Lower resistive losses than OHL in hot climates (soil temp 20–28°C at burial depth)

### Disadvantages
- 4–10× capital cost premium over OHL for same voltage and capacity
- Fault location requires specialist TDR equipment; repair time days–weeks
- Thermal derating required in high soil temperature zones
- Reactive power compensation needed for runs > ~5–8 km at 33 kV

## Trade-off decision

**Recommendation:** Underground cable for all connections ≤ 8–10 km.

For a 3 km, 33 kV connection on a 10 MW plant:
- OHL capital cost: USD 90,000–300,000
- UGC capital cost: USD 450,000–1,050,000
- Premium for underground: USD 360,000–750,000
- As % of 10 MW plant CAPEX: **3.7–9.4%**

This premium is justified by: zero ROW maintenance, storm resilience, agrivoltaic
compatibility, and community acceptance — all directly material to project bankability.

## Transmission losses (33 kV UGC, 3 km)

| Loss component | Value |
|----------------|-------|
| Resistive (I²R) losses | ~1.5–2.5% |
| Dielectric losses (XLPE) | <0.1% |
| **Total** | **~1.5–3%** |

---

# 06 — Grid Integration via Existing Substations

## Strategic rationale

Building a new 33 kV substation adds USD 500,000–1,500,000 to project costs and
12–24 months to permitting timelines.

By connecting to existing ZESCO 33 kV busbars under the 2024 Open Access Regulations,
this cost is eliminated entirely.

## Integration requirements

| Item | Specification | Cost |
|------|--------------|------|
| Anti-islanding protection | IEEE 1547 / IEC 62116 compliant relay | Part of below |
| Directional overcurrent relays | Coordinated with ZESCO feeder protection | USD 20,000–60,000 total |
| U/O voltage and frequency relays | Grid code compliant | Included above |
| Revenue-grade metering | Class 0.5S bidirectional | USD 15,000–40,000 |
| SCADA communications | Real-time integration with ZESCO | Included above |
| Wheeling agreement | Open access framework legal document | USD 10,000–30,000 legal |

## Copperbelt substation network

The Copperbelt has Zambia's densest existing substation infrastructure:
33 kV and 66 kV substations at Kitwe, Ndola, Mufulira, Chingola, and Solwezi.

Copperbelt Energy Corporation (CEC) operates a parallel transmission network
serving mines directly — also an integration target under open access rules.

## Established precedents

- 33 MWp Kitwe solar plant: commissioned February 2023 via existing substation
- 60 MW Copperbelt Energy solar PV plant: operational
- 100 MW Chisamba Solar PV Plant: commissioned June 2025 (ZESCO)

---

# 07 — Agri-Ecological Co-location System

## Concept

Agrivoltaics (agri-PV) co-locates solar generation with agricultural and ecological
systems. By November 2024, US agrivoltaic sites totalled 60,000 acres and 10 GW of solar —
more than double 2020 acreage, across nearly 600 operational sites (NREL/NLR, 2024).

## Panel wash water as irrigation

| Parameter | Value |
|-----------|-------|
| Panels per 10 MW plant | ~25,000 |
| Water per panel per wash | 2–4 litres |
| Wash frequency | Fortnightly (26 washes/year) |
| Annual wash water volume | 1.3–2.6 million litres |
| Irrigation benefit | Supplemental moisture in dry-wet transitional periods |
| Soiling loss reduction | Maintains PR at high end (reduces soiling from 5% to ~3%) |
| Bifacial yield benefit | Irrigated sward improves rear-surface albedo |

## Goat grazing

Vegetation management cost (conventional mowing): USD 1–3/kWp/year.
For a 10 MW plant: USD 10,000–30,000/year over 25 years.

Goat grazing eliminates this cost and adds revenue:
- Natural grazing height: 15–30 cm (below panel height)
- Shade utilisation: goats shelter under panels in heat, reducing water needs
- Stocking density: ~1 goat per 0.1–0.2 ha under panels
- 20 ha plant: supports 100–200 goats
- Revenue: meat (chevon) and dairy for local market
- Community benefit: herd ownership by local pastoral communities = social licence

## Apiculture

Iowa State University research: **412% increase** in honey production at agrivoltaic
sites versus conventional sites (ASCE, 2026).

| Parameter | Value |
|-----------|-------|
| Hives per 10 MW plant (5 ha habitat) | 50–100 |
| Annual honey production | 2,500–5,000 kg |
| Export price (premium organic) | USD 5–12/kg |
| Annual honey revenue | USD 12,500–60,000 |

## Native habitat creation

- Native wildflower and grass seed mix (miombo woodland ecotype)
- Nitrogen-fixing species for soil improvement
- Boundary indigenous shrub planting — wildlife corridor
- Raptor perch structures on panel racking — natural pest control

## Co-location revenue summary

| Component | Saving / Revenue |
|-----------|-----------------|
| Mowing cost eliminated | USD 10,000–30,000/yr |
| Improved panel efficiency (soiling) | +1–2% yield |
| Bifacial rear yield (improved albedo) | +0.5–1% yield |
| Goat meat and dairy | Community / secondary revenue |
| Honey production | USD 12,500–60,000/yr |
| Carbon / biodiversity credits | Non-monetised; ESG value |
