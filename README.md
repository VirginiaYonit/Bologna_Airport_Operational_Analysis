# Bologna Airport Operational Analysis
### Structured insights from 25 years of airport operations

This project explores the operational performance of Bologna Guglielmo Marconi Airport (ICAO: LIPE) through a structured, data-driven approach.

Combining publicly available datasets with domain knowledge from 25 years in aviation, the analysis highlights key post-pandemic trends related to traffic recovery, delay patterns, and environmental impact, especially CO₂ emissions.

## Project Scope

* Location: Bologna Airport (Italy)

* Period Covered: 2000–Q1 2025

## Project Sturcture

  1. Pre and post pandemic situation:

      * IFR traffic evolution

      * ATC pre-departure delays vs slot allocation 

      * Passenger load factor and emissions efficiency

      * National vs local performance comparison
    
   2. A [interactive dashboard](https://github.com/VirginiaYonit/BLQ-Dashboard) that tracks 25 years of air traffic (passengers, cargo, delays and emissions) at Bologna Airport.

This work is designed with a practical purpose: to identify patterns that support operational planning, capacity management, and sustainable recovery strategies.

## Key Insights

* Traffic Recovery: Bologna’s IFR movements and passenger volumes now exceed pre-pandemic benchmarks.

* Delay Trends: Pre-departure delays rose significantly in 2024–2025, especially in early summer, while slot delays remained low.

* CO₂ Efficiency: Load factor shows a strong correlation with emissions per passenger underlining the link between efficiency and sustainability.

## Repository Structure

├── Bologna Airport Operational Analysis.ipynb   # Main notebook
├── data/                                       # Source datasets
│   ├── .csv, .xlsx, and .md files
├── figures/                                    # Saved visualizations
├── README.md                                   # Project overview (you are here)


## Column Reference

Raw flight and delay data from Eurocontrol are fully documented in the notebook.
Note: Column FLT_DEP_1 was used as the reference for IFR departures due to its completeness and consistency across years.

## Data Integration & Governance

This project involved working with over 50 datasets originating from multiple public sources (Eurocontrol, Assaeroporti, Our World in Data) and internal archives.

Key challenges and actions:
* Merging heterogeneous data structures across years
* Handling missing or inconsistent values
* Normalizing airport and flight identifiers
* Aligning different reporting formats and time references
* Ensuring data quality through validation and documentation

These steps reflect real-world experience in data governance, including traceability, integrity checks, and the harmonization of multi-source inputs — all essential for producing reliable insights in complex operational environments like aviation.

## Tools Used

* Python (Pandas, Matplotlib, Plotly)

* Jupyter Notebook

* Excel (pre-cleaning & verification)

* Open data: Eurocontrol, Assaeroporti, Our World in Data

## Author

This case study is part of a professional portfolio that combines 25 years of experience in aviation with new training in data analysis and visualization.

For questions or collaboration, feel free to connect via [LinkedIn](https://www.linkedin.com/in/virginia-levy-abulafia?trk=contact-info).




