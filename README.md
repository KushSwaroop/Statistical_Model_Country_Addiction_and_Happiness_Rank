# Statistical Model: Country Addiction and Happiness Rank

This project analyzes the relationship between digital screen time, social-media addiction, and World Happiness Report rankings across nine countries.

## Contents

- `screentimeanalysis.ipynb` - primary analysis, normalization, visualizations, and final dataset creation.
- `final_analysis_screentime.ipynb` - analysis using the cleaned final dataset and happiness-rank data.
- `avg_screentime_calc.ipynb` - supporting screen-time calculations and Nordic progression data preparation.
- `screen time dataset countries/final_dataset_cleaned_data.csv` - cleaned country/year dataset with:
  - `country_name`
  - `year`
  - `screen_time_hours`
  - `addiction_score`
- `screen time dataset countries/` - source CSV datasets used by the notebooks.
- `WHR26_Data_Figure_2.1.xlsx` - World Happiness Report ranking data used by the analysis.

## Dataset structure

The final dataset contains one row per country and year. `addiction_score` is a country-level value and is repeated consistently across that country's annual observations. Screen-time ranges in the Nordic and Denmark progression datasets are converted to annual midpoint values.

## Running the notebooks

1. Open the repository folder in Jupyter or VS Code.
2. Use a Python environment with `pandas`, `numpy`, `matplotlib`, `plotly`, and `openpyxl` installed.
3. Run the data preparation cells before running the visualization and final-analysis cells.

Some historical cells contain machine-specific absolute paths from the original exploratory session. For a fresh checkout, use the repository-relative paths shown in the later notebook cells or update those paths to the local checkout.

## Outputs

Generated graphs and other exploratory outputs are intentionally excluded from version control. The reproducible cleaned CSV is tracked as the primary data deliverable.
