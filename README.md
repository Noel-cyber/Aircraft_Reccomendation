# My Project Phase 1 
Your company is expanding in to new industries to diversify its portfolio. Specifically, they are interested in purchasing and operating airplanes for commercial and private enterprises, but do not know anything about the potential risks of aircraft. You are charged with determining which aircraft are the lowest risk for the company to start this new business endeavor. You must then translate your findings into actionable insights that the head of the new aviation division can use to help decide which aircraft to purchase.
## Overview
As part of the company’s expansion into the aviation industry, this report aims to identify the lowest-risk aircraft for commercial and private operations. By analyzing historical aviation accident data, we provide actionable insights to guide the selection of aircraft models with the best safety records.
## Business Understanding
### Stakeholder 
1. Company Executives: Interested in minimizing financial and reputational risks.
2. New Aviation Division Head: Responsible for selecting safe and efficient aircraft.
3. Regulatory Compliance Team: Ensures adherence to aviation safety regulations.
### Key business questions
1. Which aircraft models have the lowest accident rates?
2. What are the primary causes of aviation accidents?
3. During which phases of flight do most accidents occur?
4. How has aviation safety improved over time?
## Source of data
The dataset used for this analysis is sourced from Kaggle:
https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses
## Description of data
The dataset contains 88,889 aviation accidents with 31 attributes, including:
1. Aircraft Details: Make, Model, Number of Engines, Engine Type.
2. Accident Severity: Fatal and serious injuries.
3. Operational Factors: Flight purpose, weather conditions, flight phase.
4. Date & Location: Country, airport name, event date.
## Data Understanding and Analysis
- Removed redundant or highly missing columns (e.g., Latitude, Longitude, Schedule).
- Standardized categorical values (e.g., Weather Conditions, Aircraft Categories).
- Converted date fields to proper datetime format.
- Extracted accident severity (Fatal vs. Non-Fatal incidents).
## Three visualizations (the same visualizations presented in the slides and notebook)
## Conclusion

## Summary of conclusions including three relevant findings
- Modern aviation safety improvements have reduced accident rates significantly since the 2000s.
- Certain aircraft models have higher accident frequencies, but risk needs to be adjusted for usage rates.
- Takeoff and landing phases are the most dangerous, indicating a focus on pilot training and aircraft stability is essential.

This analysis provides a solid foundation for selecting the lowest-risk aircraft as the company enters the aviation industry.
