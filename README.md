# Bologna Airport Operational Analysis

This project explores operational performance at Bologna Guglielmo Marconi Airport (ICAO: LIPE) using a structured, data-driven approach.

Combining publicly available datasets with domain knowledge in airport operations, this work highlights post-pandemic trends in traffic recovery, delay patterns, and environmental impact — particularly CO₂ emissions.

---

## Project Scope

- **Location:** Bologna Airport (Italy)
- **Period Covered:** 2017–Q1 2025
- **Themes Explored:**
  - IFR traffic evolution
  - ATC pre-departure delays (vs. slot delays)
  - Passenger load factor and emissions efficiency
  - National vs local performance contrasts

This analysis was designed with a practical purpose: to identify structural patterns that can inform operational planning, capacity management, and sustainable recovery strategies.

---

## Highlights

- **Traffic Recovery Analysis:** Bologna’s IFR movements and passenger volumes now exceed pre-pandemic benchmarks.
- **Delay Insights:** ATC-related delays surged in 2024–2025, particularly in early summer months, while slot delays remained negligible.
- **CO₂ Emissions Efficiency:** Load factor strongly correlates with emissions per passenger — reinforcing the role of operational efficiency in sustainability.

---

## Repository Structure

Bologna-Airport-Operational-Analysis/

├── Bologna Airport Operational Analysis.ipynb # Main notebook 
├── data/ # Source datasets (Eurocontrol, Assaeroporti, Our World in Data) 
| ├── .csv, .xlsx and .md files
├── figures/ # saved charts 
├── README.md # Project overview (you are here)

---

### Column Reference

The project uses raw flight and delay data from Eurocontrol.
For transparency, a full description of the raw dataset columns can be found in [Column Reference – Eurocontrol Dataset](data/column_reference.md)

>*Note: The column `FLT_DEP_1` was used as the reference for IFR departures due to its completeness and consistency across years. A detailed rationale is provided in the notebook.*


---

## Tools Used

- Python (Pandas, Matplotlib, Plotly)
- Jupyter Notebook
- Excel (pre-cleaning & verification)
- Public datasets (Eurocontrol, Assaeroporti, Our World in Data)

---

## Author

This case study is part of a professional portfolio combining 25 years in aviation with recent training in data analysis.  
It is intended for recruiters, airport operators, and stakeholders interested in airport performance, sustainability, and resilience planning.

For more insights or to get in touch, please visit [LinkedIn](https://www.linkedin.com/in/virginia-levy-abulafia?trk=contact-info)
