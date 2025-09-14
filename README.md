# Aviation Accident Analysis

Goal: Assess commercial/passenger jet safety (1983–2023) to recommend makes and models with low severe-injury and low total-destruction rates, and explore contributing factors.

## Key Findings

- Small segment: Lower average severe-injury and destruction for makes such as American Champion, Aeronca, Stinson, Maule, Diamond, Aviat (verify N for each model).
- Large segment: Boeing, Airbus, Embraer, De Havilland, McDonnell Douglas show lower mean severe-injury and competitive destruction rates.
- Weather: IMC accidents have higher severe-injury and destruction than VMC.
- Engine type: Turbofan aircraft show the lowest mean severe-injury and destruction; turbojet/turboprop higher on average.

## Key Visualizations (done in notebook)

- Top-15 makes by lowest mean severe-injury (Small vs Large, side-by-side).
- Distributions: violin (Small) and strip (Large) for injury fraction.
- Top-15 makes by lowest destruction (Small vs Large).
- Model-level bars (N≥10) for both segments.
- Factor plots: Weather (VMC/IMC) and Engine Type vs injury/destruction

## Make/Model Recommendations

### Small segment (<20 seats) — shortlist models with lowest mean severe-injury fraction (N ≥ 10 per model) and competitive destruction rates:

- Diamond DA-20 / DA-40 family
- Aeronca 7-series (7CCM/7AC variants)
- Stinson 108-1
- Maule M-series (MX-7, M-5, M-5-235C, M-4-220C)
- Aviat A-1 variants
- Grumman G-164A/B (where relevant to mission)

Action: Prioritize these for small-aircraft operations; confirm sample counts and destroyed-fraction before final ranking.

### Large segment (≥20 seats) — models with lowest mean severe-injury fraction (N ≥ 10) and solid destruction rates:

- Embraer EMB-145LR
- Boeing 737 family (incl. 737-7H4)
- Beech 76 / 200 / B200
- Cessna 337 / 402 / 402C
- Boeing 767 (select variants)

Action: Favor these types for large-transport risk selection; validate with destroyed-fraction and sample sizes.

## Factor Analysis (at least two)

### Weather Condition (IMC vs VMC)

Accidents in IMC show higher mean severe-injury fractions and higher destruction rates than VMC; distributions have a heavier right tail → more high-severity events.

### Engine Type

Turbofan aircraft exhibit the lowest mean severe-injury and lower destruction rates.

Turbojet/turboprop groups are higher on average with wider right tails; reciprocating is intermediate.
