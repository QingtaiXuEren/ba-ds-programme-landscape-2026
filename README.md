# BA/DS Master’s Programme Landscape 2026

A pilot dataset and reproducible pipeline for BA/DS master’s programmes in North America, Europe, Asia, and Oceania. The project tracks how these programmes differ in 2026 in curriculum composition, prerequisites, test policy, tuition, duration, and public reporting of outcomes, and supports a defensible shortlist for WKU BA graduates applying between October and December 2026.

## What the data are

The dataset contains one row per programme for the year 2026. Each row records:

- programme identity and location
- school type, college type, and ranking tier
- curriculum composition across statistics, programming, machine learning, data visualization, and business analytics
- prerequisites
- GRE/GMAT policy
- tuition amount and currency
- duration in months
- whether outcomes are publicly reported
- English requirement
- work experience requirement
- application fee
- minimum GPA
- whether non-business backgrounds are accepted
- study mode
- application deadline
- source URL and access date

The unit of observation is the programme-year. The pilot contains records collected by four team members across four regions.

## Where they came from

Data were collected from official programme websites:

- programme page
- curriculum page
- admission page
- tuition page
- employment report page

Each member collected programmes from their assigned region:

- North America — Yuhang Yu
- Europe — Xiaoxue He
- Asia — Guangxuan Sun
- Oceania — Qingtai Xu

QS Top 100 rankings were used to build and cross-check the sampling frame. A small number of universities blocked automated requests; those programmes were collected manually into the same coding sheet.

Robots.txt was checked before each request, and requests were spaced by one second. No data were collected from behind login walls.

## When they were collected

September 2026. First collection attempt: 22 September 2026.

## How to reproduce the pilot

1. Install dependencies:

   ```bash
   pip install -r requirements.txt
