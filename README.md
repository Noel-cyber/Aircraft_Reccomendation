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
1. Manufacturers like Cessna, Piper, and Beech, despite having high accident counts (as seen in previous analyses), maintain comparatively lower fatality rates. This suggests that while these aircraft are involved in more incidents, they are less likely to result in fatalities, likely due to their smaller size and operational contexts
2. General aviation manufacturers (e.g., Cessna, Piper) show lower fatality rates compared to manufacturers like Boeing and Northrop Douglas, which are involved in commercial aviation. This difference highlights the potential impact of operational scale and passenger volumes on fatality outcomes.
3. The majority of accidents occur under VMC, suggesting that environmental factors (e.g., weather) are less influential compared to operational or human factors.

### Three visualizations (the same visualizations presented in the slides and notebook)
![Fatality Rate by Aircraft Make](https://github.com/user-attachments/assets/e9351736-81ff-4c04-92b9-d12b0bbf24d1)
![Aircraft Reliability](https://github.com/user-attachments/assets/daf7ded3-0cb0-4a58-8db4-af232c602e6e)
![Aircraft Performance Under Different Weather Conditions](https://github.com/user-attachments/assets/eb410e1b-31b1-4ecc-abb4-605c7774917f)

### Tableau Dashboard 
https://public.tableau.com/app/profile/noel.seda/viz/InvestigationofAviationAccidents/InvestigationofAviationAccidents

## Conclusion
- The majority of incidents result in substantial damage, followed by a smaller portion classified as destroyed.
- Minor damage and unknown damage classifications are relatively infrequent compared to substantial damage.
- Certain aircraft models have higher accident frequencies, but risk needs to be adjusted for usage rates.
- Takeoff and landing phases are the most dangerous, indicating a focus on pilot training and aircraft stability is essential.

As the business joins the aviation sector, this study offers a strong basis for choosing the least risky aircraft.
