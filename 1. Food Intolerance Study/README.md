# Food Intolerance Analysis Using Cross-Correlation

This project explores the use of time-series cross-correlation to identify potential food intolerances based on symptom tracking during the COVID-19 lockdown. It applies a physics-inspired approach to evaluate time delays between allergen ingestion and gastrointestinal reactions, using real-world data logged over an 11-day period.

## Features

- Processes binary-encoded allergen and reaction tracking data
- Visualises allergen intake over time with pre- and post-consumption padding
- Applies cross-correlation to evaluate likely delay between ingestion and symptoms
- Normalises results to control for frequency bias
- Identifies top allergens responsible for reactions (e.g. dairy, sulphites)

## Key Tools

- Python (pandas, NumPy, matplotlib)
- Signal analysis: cross-correlation
- Custom data cleaning and plotting
- Normalisation techniques to correct sample size imbalance

## Future Ideas

- Develop a phone app to streamline intake and reaction logging
- Collect longer-term data to analyse dosage thresholds and reaction likelihood
- Apply Monte Carlo simulations for statistical validation and confidence bounds
- Extend to other individuals or allergens for broader study
- Use machine learning models to predict likelihood or severity of future reactions