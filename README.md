# Exoplanet Dataset — EDA & Data Cleaning
Built as the data cleaning/EDA component for PARIKALP 2026, a data science 
hackathon at MNIT Bhopal. My role covered EDA, physics-based validation, 
and cleaning; the team's modeling stage wasn't completed, so this stands 
as independent analytical work.

## Dataset
39,913 rows × 96 columns — exoplanet data, predicting planet radius (pl_rade) 
and mass (pl_bmasse)

## What I did
- Physics validation: caught and fixed unit/sign errors, invalid values 
  in orbital eccentricity, inclination, stellar mass
- Dropped 19 leakage/noise columns, 1,205 rows with impossible radius values
- Engineered 3 physics-informed features (correlation up to 0.48 with target)
- Final cleaned dataset: 38,708 rows × 80 columns, ready for modeling
