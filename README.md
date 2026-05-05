# TRIP700 FSW Deep Rolling 
This project explores Deep Rolling process parameters on 
Friction Stir Welded TRIP 700 Advanced High Strength Steel (1.2 mm) 
using Design of Experiment (DOE) for residual stress 
and microhardness analysis.

## Objective
- Preprocess experimental DOE dataset (3³ Full Factorial Design)
- Explore relationships between Deep Rolling parameters and responses
- Prepare data for statistical analysis using Minitab
- Identify optimal parameters using ANOVA and Regression Model

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
- Handle missing values and outliers (IQR method)
- Feature scaling and normalization (Z-score, Min-Max, coded -1/0/+1)
- Exploratory Data Analysis (EDA)
- Main Effects Plot per factor
- Interaction Plots (A×B, A×C, B×C)
- Correlation analysis between HV and RS
- ANOVA significance testing (p-value < 0.05)
- Regression Model for RS and HV prediction
- Response Surface / Contour plot optimization