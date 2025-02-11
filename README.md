# My Project Phase 1 
Your company is expanding in to new industries to diversify its portfolio. Specifically, they are interested in purchasing and operating airplanes for commercial and private enterprises, but do not know anything about the potential risks of aircraft. You are charged with determining which aircraft are the lowest risk for the company to start this new business endeavor. You must then translate your findings into actionable insights that the head of the new aviation division can use to help decide which aircraft to purchase.
## Overview
The goal of this analysis is to determine which aircraft pose the least danger for both commercial and private operations as part of the company's entry into the aviation sector. We offer practical advice to help choose aircraft types with the best safety records by examining past aviation accident data.
## Business Understanding
### Stakeholder 
1. Business executives: Concerned with reducing threats to their finances and reputation.
2. Head of the New Aviation Division: Charged with choosing aircraft that are both safe and effective.
3. Regulatory Compliance Team: Makes ensuring that aviation safety rules are followed.
### Key business questions
1. Which aircraft models are the least likely to be involved in accidents?
2. What are the most common flight phases for accidents?
3. How has safety in aviation changed over time?
## Data Understanding and Analysis
### Source of data
The dataset used for this analysis is sourced from Kaggle:
https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses
### Description of data
The dataset contains 88,889 aviation accidents with 31 attributes, including:
1. Aircraft Details: Make, Model, Number of Engines, Engine Type.
2. Accident Severity: Fatal and serious injuries.
3. Operational Factors: Flight purpose, weather conditions, flight phase.
4. Date & Location: Country, airport name, event date.
### Analysis
- Removed redundant or highly missing columns (e.g., Latitude, Longitude, Schedule).
- Standardized categorical values (e.g., Weather Conditions, Aircraft Categories).
- Converted date fields to proper datetime format.
- Extracted accident severity (Fatal vs. Non-Fatal incidents).
### Three visualizations (the same visualizations presented in the slides and notebook)
![Aircraft Makes and Models Involved in Accid![Fatality Rate by Aircraft Make](https://github.com/user-attachments/assets/a120f5bf-23c7-436e-85d8-5614a833940e)
ents](https://github.com/user-attachments/assets/2c254d74-d7ec-4d14-a72e-27f60f0971a9)
![Aircraft vs Weather](https://github.com/user-attachments/assets/b6f143ab-846e-4a67-bbe4-9959bf04cc2e)

### Tableau Dashboard 
https://public.tableau.com/app/profile/noel.seda/viz/InvestigationofAviationAccidents/InvestigationofAviationAccidents

## Conclusion
- Modern aviation safety improvements have reduced accident rates significantly since the 2000s.
- Certain aircraft models have higher accident frequencies, but risk needs to be adjusted for usage rates.
- Takeoff and landing phases are the most dangerous, indicating a focus on pilot training and aircraft stability is essential.

As the business joins the aviation sector, this study offers a strong basis for choosing the least risky aircraft.
