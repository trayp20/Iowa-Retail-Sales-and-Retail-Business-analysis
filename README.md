# Retail Sales and Retail Business Analysis

This project cleans and explores a dataset of Iowa retail business registrations.

## Contents

- `Retail_Sales_and_Retail_Use_Business_Registrations.csv` – raw business registration records
- `Cleaned_Business_Registrations.csv` – subset of important columns saved by the notebook
- `analysis.ipynb` – Jupyter notebook performing the cleaning and summary
- `business_status_by_city.png` – sample visualization produced from the notebook

## Quick Start

1. Install Python 3 with `pandas` and `jupyter`.
2. Launch the notebook:
   ```bash
   jupyter notebook analysis.ipynb
   ```
3. Execute the cells to reproduce the cleaning steps and generate the visualization.

The raw dataset was downloaded from the Iowa open data portal and includes information such as business name, county, city, and permit status. The notebook removes unnecessary columns, fills missing values, and outputs a cleaned CSV for further analysis.

