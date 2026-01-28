# gcn4-ros-mechanism-dft (DRAFT!!!)
Mechanistic study of ROS generation on g-C3N4-based photocatalysts using spectroscopy/electrochemistry and DFT/TD-DFT.

## Some updates
- 1st Proposal: [docs/proposal_draft.pdf](docs/proposal_draft.pdf)
- idea sketch uploaded

### Charge-dynamics–guided ROS generation on g-C3N4 hybrids (Experiment + DFT/TD-DFT)

#### TL;DR
We design g-C3N4-based hybrid photocatalysts to suppress electron–hole recombination, extend charge-carrier lifetime, and enhance O2 reduction pathways that generate reactive oxygen species (ROS). We combine spectroscopy/electrochemistry with DFT/TD-DFT to obtain a mechanism-level understanding and provide a PDT-relevant evaluation.

---

## Motivation
ROS (e.g., ¹O2, •O2−, •OH) generated under light irradiation can drive oxidative processes relevant to PDT, sterilization, and model pollutant degradation. However, ROS yield is often limited by fast charge recombination. This project focuses on correlating charge-carrier dynamics with ROS formation.

---

## Objectives
1. Increase charge-carrier lifetime (τ) by hybridization/modification of g-C3N4.
2. Identify the dominant mechanism behind recombination suppression (band alignment, interfacial transfer, trap engineering).
3. Quantitatively link charge dynamics to ROS generation efficiency and pathway (type I vs. type II).

---

## Research Questions (RQs)
- RQ1: How do modifications affect τ and recombination kinetics?
- RQ2: Which physical factors explain the trend (interfacial energetics, trap states, transfer resistance)?
- RQ3: Which ROS species increase, and under what conditions (wavelength, dissolved O2, scavengers)?

---

## Approach
### Work Package 1 — Materials / Samples
- Baseline: pristine g-C3N4
- Variants: g-C3N4 + [polymer hybrid / cocatalyst / dopant]
- Controls: dark control, no-O2 control, scavenger tests

### Work Package 2 — Charge Dynamics & Transport
- TRPL / TA (optional): lifetime components and recombination channels
- Transient photocurrent: charge extraction kinetics
- EIS: interfacial charge-transfer resistance and capacitance models

### Work Package 3 — ROS Identification & Quantification
- ¹O2: [probe name / method]
- •O2−: [probe name / method]
- •OH: [probe name / method]
- Optional: EPR spin trapping for validation
- Output metrics: ROS yield rate, apparent quantum yield (if feasible)

### Work Package 4 — Computation (DFT/TD-DFT)
- Band alignment / frontier levels for g-C3N4 and modifiers
- O2 adsorption and charge transfer descriptors (e.g., Δq, adsorption energy)
- Excited-state insight (TD-DFT) as supporting evidence for ¹O2 plausibility

---

## Key Metrics (KPI)
- Charge lifetime τ: [TRPL/TA-derived]
- Interfacial transport: [photocurrent response time], [EIS Rct]
- ROS: [species-specific signal], [rate], [normalized yield]
- Demonstration: [dye degradation / antibacterial test] (choose one)

---

## Milestones (Example)
- Week 1–2: sample prep + baseline characterization
- Week 3–5: charge dynamics & electrochem measurements
- Week 6–8: ROS assays + pathway discrimination
- Week 9–12: DFT/TD-DFT + mechanism integration + report

---

## Repository Layout

