# Estradiol-Loaded PLA Microneedle Array Design & Validation



## Clinical Problem

Menopausal hormone replacement therapy via oral estradiol suffers from hepatic first-pass metabolism, reducing treatment effectiveness.



## Solution

Transdermal PLA microneedle patch for steady estradiol delivery without injection pain.



## Design Specifications

- Material: Polylactic Acid (PLA) - structural barrier

- Drug payload: Estradiol (loaded internally during fabrication)

- Geometry: 5×5 needle array, 1.1mm height, 0.911mm base diameter

- Base substrate: 20×20×2.5 mm with hollow drug reservoir

- Reference: Khosraviboroujeni et al. (2021) https://doi.org/10.1007/s13346-021-01006-4



## Structural Validation (FEA)

**Simulation Setup:**
- Tool: COMSOL Multiphysics
- Load case: 4N skin penetration force
- Material: E = 2.34 GPa, ν = 0.39, σ_y = 52 MPa

**Results:**
- Maximum stress: 6.06 MPa
- Safety factor: 8.58
- **Conclusion:** Hollow base substrate successfully distributes insertion load across all 25 needles.

## Drug Release Validation (Mass Transfer FEA)

**Simulation Setup:**
- Tool: COMSOL Mass Transfer
- Species: Estradiol
- Diffusion coefficient: 1e-10 m²/s
- Initial concentration: 1000 mol/m³
- Time range: 0 to 180 days

**Results:**

- Maximum stress: 6.06 MPa

- Safety factor: 8.58

- Hollow base substrate successfully distributes insertion load across all 25 needles. Design validated for transdermal delivery with drug reservoir capacity.

- Estradiol concentration decreases from 1000 to near-zero over 180 days
- Steady diffusion through PLA matrix validated
- **Conclusion:** Design validated for sustained 6-month transdermal delivery



## Drug Release Mechanism

Estradiol release follows PLA degradation in vivo (2-6 months). Structure validated per Khosraviboroujeni et al.



## Files

- `/CAD` - SolidWorks and STEP files

- `/FEA` - COMSOL stress results and screenshots
