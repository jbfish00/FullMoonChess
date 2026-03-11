# FullMoonChess — Chicago Crime Analysis

**BYU 2024 Case Study** | R & Python

## Overview

Does a full moon affect crime rates in Chicago? This project investigates whether **full moons**, **weather conditions**, **holidays**, or **weekends** have a statistically meaningful relationship with the volume and type of crime in Chicago. The analysis combines Chicago crime records with moon phase data, historical weather, and federal holiday calendars.

## Research Questions

- Do full moons, weather, holidays, or weekends affect overall crime counts in Chicago?
- Do these factors have different effects on specific types of crime?
- Can crime counts or types be predicted for the coming year?
- Can crime locations (ward, community area, or lat/long) be predicted?

## Data

| File | Description |
|------|-------------|
| `crimes_cleaned.csv` | Cleaned Chicago crime records |
| `full_moon.csv` | Historical full moon dates |
| `weather.csv` | Historical Chicago weather data |
| `holidays.csv` / `US Federal Pay and Leave Holidays 2004 to 2100.csv` | Federal holiday calendar |

## Analysis

| File | Description |
|------|-------------|
| `CleaningFiles.Rmd` | Data cleaning and merging pipeline (R) |
| `analysis.Rmd` | Statistical analysis and visualizations (R) |
| `analysis.py` | Additional analysis (Python) |

## Key Visualizations

- `CommonCrimes.png` — Distribution of most common crime types
- `CrimeCounts.png` / `CrimeCountsHalf.png` — Crime volume over time

## Technologies

- R, RMarkdown, Python, Pandas, ggplot2
