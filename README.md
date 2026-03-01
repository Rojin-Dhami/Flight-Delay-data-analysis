# ✈️ Airline Delay Cause — Exploratory Data Analysis

An end-to-end EDA on the US Airline Delay Cause dataset, uncovering the key drivers of flight delays, worst-performing carriers, and seasonal trends across a decade of data.

---

## 📁 Dataset
- **Source:** https://www.kaggle.com/datasets/sriharshaeedala/airline-delay/data
- **Size:** 171223, 21 columns
- **Period:** 2013 – 2023
- **Key columns:** `arr_flights`, `arr_del15`, `arr_delay`, `carrier_delay`, `weather_delay`, `nas_delay`, `security_delay`, `late_aircraft_delay`

---

## 🎯 Goals
- Understand the root causes of flight delays
- Identify worst-performing airlines and airports
- Spot time-based and seasonal trends

---

## 🔧 Feature Engineering
| Feature | Description |
|---|---|
| `delay_rate` | % of arriving flights delayed ≥15 min |
| `cancel_rate` | % of arriving flights cancelled |
| `avg_delay_per_flight` | Average delay severity in minutes |
| `period` | Year-Month datetime for time series |

---

## 📊 Key Visualizations
- Distribution plots of numerical columns
- Delay cause breakdown (stacked bar by carrier)
- Year × Month delay rate heatmap
- Time series of delay rate 


---

## 💡 Key Findings
- **Late Aircraft + Carrier delays** account for ~75% of all delay minutes — both fully within airline control
- **Weather** contributes only ~5% of total delay minutes, far less than passenger perception suggests
- **June–July and December** are consistently the worst months across all years
- **2020** saw a historic low (0.097 delay rate) due to COVID-19; **2022–2023 rebounded to all-time highs (~0.22)**
- **SkyWest Airlines** accumulates disproportionately high delays relative to its operational size
- **Security delays** are negligible and structurally independent from all other delay causes

---

## 🛠️ Tech Stack
![Python](https://img.shields.io/badge/Python-3.10-blue)
![Pandas](https://img.shields.io/badge/Pandas-2.0-lightblue)
![Seaborn](https://img.shields.io/badge/Seaborn-0.12-teal)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7-orange)

---



