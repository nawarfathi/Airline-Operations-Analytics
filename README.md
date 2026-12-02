# Airline Operations Analytics

## Project Overview

This project analyzes airline operational performance using flight data from August 2026.

The goal is to identify operational patterns, evaluate airline performance, investigate flight delays, and examine cancellation and diversion trends.

The analysis focuses on understanding the factors associated with operational inefficiencies and identifying opportunities for improvement.

## Dataset

- **Source:** Bureau of Transportation Statistics (BTS)
- **Period:** August 2026
- **Data Type:** U.S. airline flight operations
- **Raw Data:** Available in the `data/` directory

## Project Structure

```text
Airline-Operations-Analytics/
│
├── data/
│   └── [Raw dataset CSV]
│
├── 01_Data_Quality_Assessment.ipynb
├── 02_Exploratory_Data_Analysis.ipynb
└── README.md
```

## Project Workflow

### 1. Data Quality Assessment

- Dataset inspection and structural assessment
- Missing value analysis and handling
- Data validation and consistency checks
- Identification of potential data quality issues
- Creation of derived features

### 2. Exploratory Data Analysis (EDA)

- Arrival and departure delay analysis
- Delay patterns by airline, airport, weekday, and scheduled departure hour
- Analysis of delay causes
- Departure delay recovery analysis
- Flight distance and delay relationships
- Cancellation and diversion analysis
- Comparative airline operational performance

## Key Findings

- Arrival delay rates reached their highest level around 7 PM.
- Late aircraft and carrier-related delays accounted for approximately 70.59% of total delay-cause minutes.
- Departure and arrival delays showed a very strong positive correlation (Pearson r = 0.98).
- Southwest Airlines (WN) showed the highest proportion of flights with a positive departure-to-arrival delay reduction (43.09%) among the analyzed airlines.
- Hawaiian Airlines (OH) recorded the highest cancellation rate (8.48%).
- United Airlines (UA) recorded the highest diversion rate (0.74%).
- Delta Air Lines (DL) had the lowest arrival delay rate (21.62%).

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Business Recommendations

- Improve aircraft turnaround planning to reduce late-aircraft delays.
- Review operational resource allocation during evening departure periods.
- Investigate airports and airlines with consistently high delay rates.
- Monitor cancellations and diversions as separate operational performance indicators.
- Evaluate delay recovery strategies, particularly during afternoon operations.

## Conclusion

This project provides an exploratory assessment of airline operational performance and highlights meaningful differences across airlines, airports, and departure periods.

The findings can help identify areas that deserve further operational investigation and support data-driven decision-making.

---

*This project was developed as part of a data analytics portfolio.*
