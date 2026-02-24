# EV vs. Gas Cars — Lifecycle Environmental Impact Analysis
*Research synthesis + quantified estimates (CO₂ + selected air pollutants)*

## Overview
Electric vehicles are often described as “zero-emission,” but tailpipe emissions are only part of the story. This project compares **battery electric vehicles (EVs)** vs **gasoline cars** across a simplified **lifecycle lens**—from material production and manufacturing to operation and end-of-life—using a combination of public sources and transparent back-of-the-envelope estimation.

Deliverables include a written analysis paper and presentation slides.

---

## Key questions
- Are EVs actually better for the environment once you include **electricity generation** and **battery supply chain**?
- How do EVs and gas cars compare across:
  - **Lifecycle greenhouse gases (CO₂-equivalent)**
  - **Selected air pollutants** (e.g., carbon monoxide as a proxy for harmful byproducts)
- What ethical and practical challenges come with a large-scale transition to EVs?

---

## Data & sources (high level)
This is a **research-based project** (no code). Inputs were gathered from public sources such as:
- U.S. EPA lifecycle estimates and vehicle-emissions materials
- U.S. Energy Information Administration (gasoline byproducts)
- U.S. Department of Energy / Alternative Fuels Data Center (EV emissions framing)
- Research and reporting on battery supply chains and materials
- Google Trends to contextualize public interest over time

All citations and details are included in the paper and slides.

---

## Approach
### 1) Public interest context (Google Trends)
I used Google Trends to compare search interest over time for terms like:
- “electric car environment impact”
- “gas car environmental impact”
- “car emission”

This section framed how public attention has shifted and where interest clusters geographically.

### 2) CO₂ lifecycle comparison
Using EPA lifecycle framing and supporting reporting, I compared lifecycle greenhouse gas emissions per mile and found a consistent high-level conclusion in the literature:
- **Gas cars emit roughly ~2× lifecycle GHG per mile compared to EVs** (model-year style comparisons), and the gap should widen as electricity generation and battery manufacturing decarbonize.

### 3) Air-pollutant proxy estimates (CO as an example)
Because detailed pollutant-by-material lifecycle inventories are difficult to find consistently, I used a transparent estimation approach:
- Approximate **engine production** pollution using steel-production byproduct logic
- Approximate **battery production** pollution using major battery material composition and a conservative “steel-like” upper bound for certain metals
- Compare **operation**: EV tailpipe is ~0; gas cars emit CO and other pollutants annually
- Compare **end-of-life**: a simplified landfill/recycling comparison using published landfill biogas estimates

---

## Results (interview-ready summary)
### Lifecycle GHG (CO₂-equivalent)
- A consistent lifecycle framing indicates **gas cars have about ~2× the lifecycle GHG per mile** vs EVs in typical comparisons.
- As grids get cleaner and battery manufacturing improves, **EV lifecycle advantage should grow**.

### Selected air pollutants (CO proxy)
Using a simplified lifecycle estimate and assuming a **15-year vehicle life**:
- **EVs (manufacturing process not included): ~4,396 lbs CO** (battery materials + end-of-life estimate)
- **Gas cars (manufacturing process not included): ~10,787 lbs CO** (engine materials + 15 years of operation + end-of-life estimate)

A key qualitative takeaway is that **gas-car tailpipe emissions accumulate quickly**, and can exceed EV supply-chain “front-loaded” pollution within a relatively short time horizon.

> Note: These air-pollutant calculations are deliberately conservative and are meant to compare **order-of-magnitude** differences with clear assumptions, not to replace a full LCA model.

---

## Ethics & real-world considerations
Beyond emissions, the project highlights key transition risks:
- **Data privacy:** modern EVs can collect extensive driving/behavior telemetry
- **Battery recycling/disposal:** environmental handling and supply-chain responsibility
- **Labor/human rights:** cobalt mining exposure and child labor risks in some regions
- **Workforce displacement:** EVs require fewer parts and less labor in manufacturing

---

## Repository contents
- `Project Analysis Paper.docx` — full written analysis and references
- `Project Presentation Slides.pptx` — slide summary and visuals

---

## What I would improve next
- Replace proxy estimates with a standardized **LCA database** approach (e.g., GREET-based or peer-reviewed LCA inventories)
- Break out lifecycle emissions by **regional electricity mix** (grid intensity)
- Quantify additional pollutants (NOx, PM) using consistent sources across lifecycle phases
- Add sensitivity analysis for battery size, vehicle class, and annual mileage

---

## Author
**Chance Xu**  
GitHub: https://github.com/chance-analytics
