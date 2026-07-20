# Bellabeat Case Study

Analysis of smart fitness device usage data, with marketing recommendations for **Bellabeat Time**.

## Data source

[FitBit Fitness Tracker Data](https://www.kaggle.com/datasets/arashnic/fitbit) — Kaggle, shared by Mobius, CC0: Public Domain license.
Data collected from 30 Fitbit users via Amazon Mechanical Turk (March–April 2016).

## Contents

- `Bellabeat_analysis.ipynb` — full pipeline: load, clean, analyze, chart, and generate the report
- `Bellabeat_case_study.docx` — final report (Ask → Prepare → Process → Analyze → Share → Act)

## Folder structure

```
bellabeat-case-study/
├── Bellabeat_analysis.ipynb
└── data/
    └── Fitabase Data 3.12.16-4.11.16/
        ├── dailyActivity_merged.csv
        ├── hourlyCalories_merged.csv
        ├── hourlyIntensities_merged.csv
        ├── hourlySteps_merged.csv
        ├── minuteSleep_merged.csv
        └── weightLogInfo_merged.csv
```

Download the CSVs from the [Kaggle dataset page](https://www.kaggle.com/datasets/arashnic/fitbit) and place them as shown above. Everything else (`analysis/`, charts, the `.docx`) is generated automatically when the notebook runs.

## How to run

```
pip install pandas numpy matplotlib jupyter
jupyter notebook Bellabeat_analysis.ipynb
```

Run all cells top to bottom — the notebook regenerates the charts, `stats.json`, and the Word report from scratch.

## Tools

Python (pandas, numpy, matplotlib, python-docx).
