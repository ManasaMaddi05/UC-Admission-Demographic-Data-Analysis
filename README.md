# UC Admissions Demographics: 2021–2023 Analysis

## Overview
Our team analyzed whether demographic changes in **California counties** from 2021–2023 are reflected in **University of California admissions demographics** during the same period. Using UC admissions data and U.S. Census estimates, we cleaned, merged, and analyzed the datasets through both visualizations and statistical modeling.  

**Key finding:** County demographic shifts show little correlation with UC admissions changes, suggesting that factors like admissions policy, outreach, and socioeconomic variables may play a larger role.

---

## Research Question
Do year-to-year shifts in California county racial/ethnic makeup correspond to changes in UC admissions demographics, and if so, which groups are most affected?

---

## Data Sources
- **UC Admissions by School (2021–2023):** Applicants, admits, and enrollees by demographic group for California public high schools.
- **California County Demographics (2021–2023):** U.S. Census estimates with racial/ethnic breakdowns.

---

## Methods
- **Data Cleaning:** Standardized county names, handled nulls, converted counts to integers.
- **Focus Variable:** Admitted student counts.
- **Feature Engineering:** Calculated year-over-year percentage changes for demographic shares in both datasets.
- **Visualization:** Generated pie charts, boxplots, and scatter plots to identify patterns.
- **Statistical Modeling:** Applied OLS regression to test correlation between county-level shifts and UC admissions trends.

---

## Results
- Most demographic groups showed **no statistically significant correlation** (p > 0.3).
- UC admissions demographics were **remarkably stable** over time.
- Hispanic/Latinx representation varied more across counties than other groups.
- African American admit share fluctuations were observed in certain counties but not directly tied to county population data.

---

## Limitations
- Census estimates contain margins of error, especially for smaller counties.
- Private and out-of-state high school data were excluded.
- Socioeconomic and application rate data were not included in this model.

---

## Tools & Technologies
- Python: `pandas`, `numpy`, `matplotlib`, `seaborn`, `statsmodels`
- Jupyter Notebook
- Git/GitHub for version control

---

## Contributors
- Ishan Banerjee
- Lakshmi Manasa Maddi
- Ritvik Mohindru
- Rakshan Patnaik
- Sai Sri Lasya Yadlapati

