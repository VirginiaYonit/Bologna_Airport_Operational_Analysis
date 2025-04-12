
## Column Reference – Raw Eurocontrol Dataset

This document provides a structured reference for key columns used in the analysis notebook, based on the raw Eurocontrol and operator datasets.

> *Note: The column `FLT_DEP_1` was used as the reference for IFR departures due to its completeness and consistency across years. A detailed rationale is provided in the notebook.*

| Column Name        | Source            | Label       | Description                                               | Example     |
|--------------------|-------------------|-------------|-----------------------------------------------------------|-------------|
| YEAR               | Network Manager   | YEAR        | Reference year                                            | 2014        |
| MONTH_NUM          | Network Manager   | MONTH_NUM   | Month (numeric)                                           | 01          |
| MONTH_MON          | Network Manager   | MONTH_MON   | Month (3-letter code)                                     | JAN         |
| FLT_DATE           | Network Manager   | FLT_DATE    | Date of flight                                            | 01-Jan-2014 |
| APT_ICAO           | Network Manager   | APT_ICAO    | ICAO 4-letter airport code                                | EDDK        |
| APT_NAME           | PRU               | APT_NAME    | Airport name                                              | Cologne-Bonn|
| STATE_NAME         | -                 | -           | Country in which the airport is located                   | Germany     |
| FLT_DEP_1          | Network Manager   | -           | Number of IFR departures (Eurocontrol)                    | 66          |
| FLT_DEP_IFR_2      | Airport Operator  | -           | IFR departures (from airport-submitted data)              | 66          |
| DLY_ATC_PRE_2      | Airport Operator  | -           | ATC pre-departure delay (IATA Code 89) reported by APT    | 0           |
| FLT_DEP_3          | Airlines (CODA)   | -           | IFR departures reported by airlines                       | 52          |
| DLY_ATC_PRE_3      | Airlines (CODA)   | -           | ATC pre-departure delay (IATA Code 89) reported by airline| 2           |
