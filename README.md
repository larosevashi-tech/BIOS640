# BIOS640 - week 4
NHANES Blood Pressure Dataset

## Repository structure

```
bios640-week4/
├── README.md
├── bios640-week4.Rproj
├── .gitignore
├── data/
│   ├── raw/
│   │   ├── 2013-2014_DEMO_H.xpt.txt
│   │   ├── 2015-2016_DEMO_I.xpt.txt
│   │   ├── 2017-2018_DEMO_J.xpt.txt
│   │   ├── 2013-2014_BPX_H.xpt.txt
│   │   ├── 2015-2016_BPX_I.xpt.txt
│   │   └── 2017-2018_BPX_J.xpt.txt
│   └── clean/
│       ├── cleaned_NHANES.csv
│       ├── diet.csv
│       └── nhanes_bp_demographics_clean.rds
├── reports/
│   ├── week2_nhanes_cleaning.Rmd
│   ├── week2_nhanes_cleaning.pdf
│   ├── week3_nhanes_report.html
│   ├── week3_nhanes_report.Rmd
│   ├── week3_nhanes_report.pdf
│   ├── nhanes_tables_report.Rmd
│   └── nhanes_tables_report.pdf
├── dashboard/
│   ├── nhanes_dashboard.Rmd
│   └── nhanes_dashboard.html
├── figures/
│   └── ex2_age_histogram.png, ex2_gender_bar.png, ...
└── references/
    ├── references.bib
    └── packages.bib
```
## What each folder contains

- **`data/raw/`** holds the original NHANES demographic and blood pressure files for the 2013 to 2014, 2015 to 2016 and 2017 to 2018 waves.
- **`data/clean/`** holds the cleaned datasets read by the reports.
- **`reports/`** holds each R Markdown source next to its rendered output. This covers the Week 2 cleaning report, the Week 3 analysis report and the Exercise 4 table report.
- **`figures/`** holds the plots exported with `ggsave()` from the Week 3 report.

## Viewing and reproducing the outputs

Rendered files are committed.

To rebuild them, open `bios640-week4.Rproj` in RStudio so that `here()` resolves paths from the repository root.

## Data source

National Health and Nutrition Examination Survey (NHANES), CDC National Center for Health Statistics. https://wwwn.cdc.gov/nchs/nhanes/

