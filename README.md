# TRIP700 FSW Deep Rolling — ML Workshop
This project explores Deep Rolling process parameters on 
Friction Stir Welded TRIP 700 Advanced High Strength Steel (1.2 mm) 
using Machine Learning for residual stress and microhardness prediction.

## Objective
- Preprocess experimental DOE dataset (3³ Full Factorial Design)
- Explore relationships between Deep Rolling parameters and responses


## Dataset
- 54 samples (27 combinations × 2 replications)
- Base material : TRIP 700 Steel (1.2 mm thickness)
- Welding process : Friction Stir Welding (FSW) — HAAS VF2 CNC
- Factor A : Deep Rolling Pressure [40 / 70 / 100 bar]
- Factor B : Feed Rate [0.10 / 0.20 / 0.30 mm/rev]
- Factor C : Number of Passes [1 / 2 / 3]
- Response 1 : Residual Stress (RS_MPa) — XRD Pulstec μ-X360, Cos α method
- Response 2 : Microhardness (HV) — Vickers Microhardness Test

## Tasks
- Data loading and inspection
- Feature scaling and normalization (Z-score, Min-Max, coded -1/0/+1)
- Main Effects Plot per factor
- Interaction Plots (A×B, A×C, B×C)
- Correlation analysis between HV and RS
- Linear Regression baseline (R², RMSE)
- ANOVA significance testing per factor
- Response Surface / Contour plot optimization