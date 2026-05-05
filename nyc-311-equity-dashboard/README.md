# NYC 311 Service Equity Dashboard

## Overview

This project analyzes whether wealthier neighborhoods in New York City receive faster 311 service resolution times.

It combines:

* NYC 311 complaint data
* Census median income data (ZIP-level)

## Key Questions

* Do higher-income areas receive faster service?
* Which complaint types show the biggest inequality?
* How does resolution time change over time?

---

## Dashboard Preview

![Dashboard](dashboard.png)

---

## Features

* Interactive filters (Borough, Complaint Type, Income Group, Date)
* Geographic map of resolution times by ZIP code
* Income vs resolution time analysis
* Time trend analysis
* Complaint-type comparison across income groups

---

## Key Insights

* Higher-income ZIP codes tend to have slightly faster resolution times
* Heat/Hot Water complaints show the largest delays
* Low-income areas consistently experience longer resolution times

---

## Tools Used

* Python (Pandas, Plotly, Dash)
* Census Data API
* NYC Open Data (311)

---

## How to Run

```bash
pip install pandas plotly dash
python app.py
```

---

## Files

* `Cencus.ipynb` → Data processing & analysis
* `dashboard.png` → Final dashboard view

---

## Author

Mahin Chowdhury
