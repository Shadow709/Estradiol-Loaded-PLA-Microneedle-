# Estradiol-Loaded PLA Microneedle Array Design & Validation

## Clinical Problem
Menopausal hormone replacement therapy via oral estradiol suffers from hepatic first-pass metabolism causing the oral treatment to be ineffective. 

## Solution
Transdermal PLA microneedle patch for steady estradiol delivery without injection pain.

## Design Specifications

- Material: Polylactic Acid (PLA) - structural barrier

- Drug payload: Estradiol (loaded internally during fabrication)

- Geometry: 5×5 needle array, 1.1mm height, 0.911mm base diameter

- Base substrate: 20×20×2.5 mm

- Reference: Khosraviboroujeni et al. (2021)

(https://doi.org/10.1007/s13346-021-01006-4)

## Structural Validation (FEA)
- Validated PLA needle structure can penetrate through skin

- Load case: 4N skin penetration force

- Material: E = 2.34 GPa, ν = 0.39, σ_y = 52 MPa

- Max stress: 25.3 kPa

- Safety factor: >2000

- Result: PLA structure confirmed safe for transdermal delivery

## Drug Release Mechanism
Estradiol release follows PLA degradation in vivo (2-6 months).
Structure validated; degradation kinetics per Khosraviboroujeni et al.

## Results
- Max stress: 0.0132 MPa
- Safety factor: 3,939
- Conclusion: Hollow base substrate provides adequate stress distribution. 
  Design validated for transdermal insertion with drug reservoir capacity.

## Files

- `/CAD` - SolidWorks and STEP files

- `/FEA` - COMSOL results
