# Solar Challenge Week 1 - MoonLight Energy Solutions

## Objective
Quick EDA and cross-country comparison of solar measurement data from Benin, Sierra Leone, and Togo. Produce cleaned datasets (local only), EDA notebooks, and a Streamlit dashboard.

## Setup
1. Clone repo:
   `git clone git@github.com:<user>/solar-challenge-week1.git`
2. Create and activate venv:
   see README in repo (or use `python3 -m venv .venv`)
3. Install:
   `pip install -r requirements.txt`
4. Notebooks:
   - `notebooks/benin_eda.ipynb`
   - `notebooks/sierraleone_eda.ipynb`
   - `notebooks/togo_eda.ipynb`
   - `notebooks/compare_countries.ipynb`

## CI
A basic GitHub Actions workflow installs `requirements.txt` to validate the environment.

## How I worked
- Branching: `setup-task`, `eda-benin`, `eda-sierraleone`, `eda-togo`, `compare-countries`, `dashboard-dev`
- Data files: **not** committed; exported cleaned CSVs saved to `data/` which is ignored.

## Submission
- GitHub link to main branch
- PDF final report (Medium-style) in `reports/`
- Dashboard screenshot in `dashboard_screenshots/`

