# 🚲 Austin CapMetro Bike Trip Analysis

This project analyzes over 2 million bike trip records from **Austin's Capital MetroBike system** to uncover usage trends, highlight demand patterns, and support infrastructure planning in collaboration with **CapMetro** and the **City of Austin**.

## 📌 Goals

- Identify high-traffic and underserved kiosks.
- Understand user behavior by time, location, and membership.
- Cluster kiosks by demand using unsupervised learning.
- Visualize data interactively to support city planning efforts.

## 📁 Project Structure

- `data_clean.ipynb` – Cleans and preprocesses the raw trip data.
- `EDA.ipynb` – Exploratory data analysis across time, geography, and user segments.
- `capmetrobikes_cluster_analysis.ipynb` – Applies **K-Means clustering** to categorize kiosks by demand level.
- `austin_capmetro_bike_demand_map.html` – Interactive map showing clustered kiosk activity across Austin.
- `Newly Suggested Kiosks.html` – Recommends kiosk locations for infrastructure investment based on spatial demand insights.

## 🔍 Key Methods

- **Data Cleaning & Feature Engineering:**
  - Processed over 2M trip logs with datetime parsing, trip duration metrics, and route generation.
  - Engineered features for seasonal usage, time-of-day segments, and log-transformed duration.

- **EDA Insights:**
  - Classic bikes dominate usage; most trips occur during the **evening rush** and **lunch** periods.
  - UT-area kiosks show the highest activity; seasonality peaks in **Spring** and **Fall**.

- **Clustering Analysis:**
  - Applied **K-Means** to group kiosks by demand volume (High, Medium, Low).
  - Results overlaid on **bike lane infrastructure** using **Folium** and **GeoPandas** for city planning use.

- **Interactive Mapping:**
  - HTML visualizations identify top kiosks (e.g., *21st & Speedway*, *Dean Keeton & Speedway*) by activity volume.
  - Suggested kiosk expansions shown in `Newly Suggested Kiosks.html`.

## 🛠 Tools & Libraries

- Python (pandas, seaborn, scikit-learn, folium, geopandas)
- Jupyter Notebooks
- HTML + Leaflet.js (via Folium)
- OpenStreetMap + City of Austin GIS layers

## 🌐 Outputs

- **📍 Cluster Map:** [`austin_capmetro_bike_demand_map.html`](austin_capmetro_bike_demand_map.html)
- **🆕 Suggested Kiosks:** [`Newly Suggested Kiosks.html`](Newly%20Suggested%20Kiosks.html)

## 🤝 Acknowledgments

Project developed through the **UT Austin MISA (Management Information Systems Association)**. Data and map feedback shared with **Capital Metro** and the **City of Austin** to support sustainable and equitable transit planning.

---

> *For questions or collaboration inquiries, feel free to reach out via GitHub or email.*

