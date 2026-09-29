# Aadhaar Migration Analytics — UIDAI Data Hackathon

Using UIDAI enrolment & update data as a real-time signal of internal migration in India.

## Problem

Internal migration is hard to measure in real time. Aadhaar update patterns offer a live proxy for population mobility.

## What I did

All analysis lives in `final_report.ipynb` (29 cells):

1. **Merged** UIDAI enrolment, demographic, and biometric update datasets; standardized dates to monthly periods
2. **Built a migration index** — demographic updates ÷ enrolments — at state and district level
3. **Ranked** top migration-receiving vs migration-sending states
4. **Segmented** by age group to separate job-driven vs family migration
5. **Analyzed** seasonal migration peaks
6. **Forecasted** Aadhaar update demand with Prophet

## Tech

Python · pandas · matplotlib · Prophet (Jupyter Notebook)

## Files

- `final_report.ipynb` — the full analysis
- `UIDAI_Migration_Analytics_AryanSingh.pdf` — report export

## Note

The competition datasets were local files (not committed to the repo); the notebook documents the full pipeline end to end. Built for the UIDAI Data Hackathon 2026.

## Author

**Aaryan Singh** — Data Analyst (SQL • Python • Power BI • Excel), Mumbai
💼 [LinkedIn](https://www.linkedin.com/in/aaryansingh-de) · 💻 [GitHub](https://github.com/Aryan787913)
