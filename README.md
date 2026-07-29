# SpaceX Falcon 9 Landing Prediction

An end-to-end data-science capstone that investigates whether a Falcon 9 first stage will land successfully—from API collection and web scraping to SQL analysis, interactive maps, dashboards, and machine-learning models.

## Why landing prediction matters

First-stage reusability is a major driver of Falcon 9 launch economics. Estimating landing success helps explain launch risk and cost while providing a realistic classification problem involving operational, geographic, payload, and orbital data.

## Project workflow

1. Collect launch records through the SpaceX API
2. Scrape historical Falcon 9 launch tables
3. Clean data and create binary landing outcomes
4. Explore launch sites, payloads, orbits, and success rates
5. Query mission data with SQL
6. Map launch sites and nearby infrastructure with Folium
7. Build an interactive Plotly Dash application
8. Compare classification models and tune hyperparameters

## Repository guide

| Asset | Purpose |
| --- | --- |
| `Capstone.ipynb` | SpaceX API data collection |
| `Web scrapping.ipynb` | Historical launch web scraping |
| `Data Wrangling.ipynb` | Cleaning and outcome-label preparation |
| `EDA.ipynb` | Exploratory analysis and feature engineering |
| `Sql data.ipynb` | SQL-based mission analysis |
| `Data visualization.ipynb` | Statistical visual exploration |
| `Interactive Visual Analytics with Folium lab.ipynb` | Launch-site mapping |
| `Machine learning Predictions.ipynb` | Classification and model comparison |
| `spacex.py` | Plotly Dash application |
| `spacex_launch_dash.csv` | Dashboard dataset |
| `Capstone project (1).pdf` | Final presentation |

## Technologies

Python, Pandas, NumPy, Requests, Beautiful Soup, SQL, Matplotlib, Seaborn, Folium, Plotly Dash, and scikit-learn.

## Run the dashboard

```bash
git clone https://github.com/sohanmirylkar/SpaceX_project.git
cd SpaceX_project
python -m venv .venv
python -m pip install -r requirements.txt
python spacex.py
```

Open the local address printed by Dash.

## Run the notebooks

```bash
python -m pip install jupyter pandas numpy requests beautifulsoup4 matplotlib seaborn folium plotly scikit-learn
jupyter notebook
```

Some notebooks depend on external APIs, IBM Db2, or remotely hosted course datasets and may require credentials or compatibility updates.

## Context

Completed as part of the IBM Applied Data Science Capstone.

## Author

Sohan Miryalkar
