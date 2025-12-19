# Study No. 2: Kinematic Anomalies in Gaia DR3 Data

## 1. Research Objective
To analyze the galactic rotation anomaly (flattened rotation curves) using empirical stellar data and determine if the effect is an emergent property of vacuum scaling.

## 2. Theoretical Framework
- **Key Hypothesis:** Gravitational coupling deviates from Newtonian $1/\sqrt{r}$ decay according to the scaling law identified in Study #1.
- **Relationship to Project Synapse:** Tests the macro-scale validity of the universal scaling law without invoking non-baryonic Dark Matter.

## 3. Data & Methodology
- **Source:** Gaia Data Release 3 (DR3).
- **Processing:** ADQL query of 5,000 local stars, radial velocity reconstruction, and linear regression of the velocity-distance gradient.
- **Metrics:** Reduced $\chi^2$, Root Mean Square Error (RMSE), Observed Gradient ($\nabla V$).

## 4. Primary Results
- **Quantitative Finding:** Observed Gradient $\nabla V \approx 0.0066$ km/s/pc.
- **Statistical Significance:** Reported an 88.13% correlation between observed stellar kinematics and the vacuum scaling prediction.

## 5. Directory Contents
- `Study_2_Gaia_Kinematics.html` - Formal Research Manuscript.
- `Study_02_Gaia_Analysis.ipynb` - Python Analysis Notebook.
- `gaia_study_2.png` - High-Resolution Stellar Velocity Profile.
