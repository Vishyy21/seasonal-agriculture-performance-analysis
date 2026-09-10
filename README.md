# Seasonal Agriculture Performance Analysis

## VOIS AICTE Batch 1 2026–2027 — Major Project

This project analyzes agricultural performance across **Kharif, Rabi and Zaid** seasons using the dataset provided for the VOIS major project.

### Objective
The objective is to identify meaningful seasonal patterns, trends, relationships, differences and variations in agricultural performance, and turn those findings into evidence-based recommendations.

### Dataset
The analysis uses the provided file:
- `seasonal_agriculture_performance_dataset (2).csv`

Key areas covered include:
- Seasonal yield and profitability
- Water use and water efficiency
- Irrigation method comparisons across seasons
- Crop-level profitability
- Yield distribution
- Relationships among numerical variables

### Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

### Main Findings
- Kharif has the highest average yield among the three seasons.
- Kharif also shows the strongest average profit and water-efficiency performance.
- Zaid has the lowest average yield and water efficiency and the highest average water use.
- Irrigation performance differs by season; the analysis compares irrigation methods using the provided data.
- Sugarcane and Chilli stand out for average profitability in the analyzed dataset.

### Visualizations
The `charts/` folder contains six generated visualizations:
- `01_average_yield_by_season.png` — average yield by season
- `02_average_profit_by_season.png` — average profit by season
- `03_water_efficiency_by_season.png` — average water efficiency by season
- `04_yield_distribution_boxplot.png` — yield distribution by season
- `05_irrigation_season_yield.png` — irrigation method and seasonal yield comparison
- `06_profit_by_crop.png` — top crops by average profit

### Project Files
- `Seasonal_Agriculture_Performance_Analysis.ipynb` — complete analysis notebook
- `seasonal_agriculture_performance_dataset (2).csv` — original project dataset
- `seasonal_summary.csv` — corrected seasonal summary table
- `charts/` — generated visualizations
- `requirements.txt` — Python dependencies
- `PROJECT_INFO.txt` — project metadata

### How to Run
1. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Open `Seasonal_Agriculture_Performance_Analysis.ipynb` in Jupyter Notebook or Google Colab.
3. Keep `seasonal_agriculture_performance_dataset (2).csv` in the same working directory.
4. Run the notebook cells from top to bottom.

### Note
This repository is prepared for the VOIS major project submission and is based on the provided project problem statement and dataset.
