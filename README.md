# U.S. Gun Violence Trends

This notebook explores U.S. gun incident records from 2014 to 2022. It summarizes how recorded incidents vary over time and compares state totals and selected 2015 city counts with population estimates.

Pandas is used for cleaning and aggregation, with Matplotlib, Seaborn, and Plotly for charts. These are descriptive comparisons; they do not identify causes. State rates use the full study period and 2022 population estimates. City rates cover the 15 cities with the highest raw incident counts in 2015.

## Run

From the repository root, install the dependencies and open the notebook:

```sh
python -m pip install -r requirements.txt
jupyter notebook notebooks/us_gun_violence_trends.ipynb
```

The input tables are in `data/`. The incident records retain date, city, state, and outcome counts; street addresses have been removed.
