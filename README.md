# Build-A-Bed | Student Homelessness Exploratory Data Analysis (SY 2021–22)

## Overview
This project explores district-level student homelessness data reported under the McKinney-Vento Act for the 2021–2022 school year. The analysis supports the Build-A-Bed initiative by identifying school districts within Cameron and Willacy Counties where students may be at elevated risk of inadequate sleeping conditions.

The focus of this project is exploratory data analysis (EDA), emphasizing distribution, concentration, and benchmarking rather than prediction or modeling.

---

## Data Source
- EDFacts McKinney-Vento Homeless Students dataset
- School Year: 2021–2022
- Level: Local Education Agency (LEA)
- Scope: Texas LEAs only

---

## Key Questions Explored
- How are homeless student counts distributed across districts in the service area?
- How concentrated is student homelessness within each county?
- How do local districts compare to the Texas median district?
- Where do districts fall relative to statewide distributions?

---

## Methods
- Filtered national EDFacts data to Texas LEAs
- Identified districts within Cameron and Willacy Counties
- Calculated district-level homelessness totals
- Computed county-level shares and totals
- Benchmarked districts against the Texas median
- Calculated Texas percentile ranks for contextual comparison
- Built an exploratory dashboard in Looker Studio for visualization

---

## Outputs
- Jupyter notebook documenting data cleaning and EDA
- Processed dataset used for dashboarding
- Interactive Looker Studio dashboard
- Static dashboard snapshot for reference

---

## Dashboard
An exploratory dashboard was created in Looker Studio to visualize district-level patterns, county comparisons, and benchmark context.

Link to dashboard:
(https://lookerstudio.google.com/s/l9rrf4smMWc)

---

## Notes on Data Coverage
Some school districts within the service area did not have publicly reported LEA-level homelessness data for the 2021–22 school year and are therefore excluded. Districts without published data were not estimated or inferred to avoid misrepresentation.

Student homelessness counts are used as a proxy indicator for housing and sleep instability and may underrepresent unmet need.

---

## Tools Used
- Python (pandas)
- Google Colab
- Looker Studio
- GitHub

---

## Status
Exploratory analysis complete.  
This repository serves as a foundation for future reporting, visualization, and grant-related analysis.
