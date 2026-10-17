F1 Race Analytics with FastF1

Exploratory data analysis of Formula 1 race and telemetry data using the [FastF1](https://github.com/theOehrly/Fast-F1) Python library, built as a mini project.

## Data

- **Source:** FastF1 API (official F1 timing and telemetry data)
- **Races / seasons covered:** [e.g. 2023 Monaco GP, 2024 season]
- **Data types used:** [lap times, telemetry, tyre compounds, weather, results]

## Methodology

1. **Data collection:** loaded sessions through FastF1 with caching enabled
2. **Cleaning:** [e.g. removed in/out laps, handled missing telemetry]
3. **Analysis & visualization:** [e.g. lap-time trends, speed traces, tyre degradation]
4. **[Modeling, if any]:** [e.g. regression for lap-time prediction]

## Repository Structure

```
├── notebooks/
│   ├── 01_f1_data_exploration.ipynb   # data loading and EDA
│   └── 02_f1_analysis_v2.ipynb        # refined analysis
├── report/
│   └── F1_Mini_Project_Report.pdf     # full project report
├── requirements.txt
└── README.md
```

## Tech Stack

Python · FastF1 · Pandas · NumPy · Matplotlib · Jupyter

## Report

The full write-up is in [`report/F1_Mini_Project_Report.pdf`](report/F1_Mini_Project_Report.pdf).
