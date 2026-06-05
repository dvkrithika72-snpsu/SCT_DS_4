# Traffic Accident Data Exploratory Data Analysis (EDA)

## 🔍 Project Overview
This project performs an **Exploratory Data Analysis (EDA)** on a comprehensive US Traffic Accidents dataset. The goal is to identify hidden safety trends, patterns related to specific times of day, prominent weather conditions, and map out high-density accident hotspots to help understand contributing risk factors.

---

## 📊 Core Analytical Insights
* **Time Distribution:** The analysis reveals distinct peaks in traffic incidents, primarily aligned with morning and evening rush hours, showing a strong correlation between heavy traffic volume and accident frequency.
* **Weather Impact:** While severe conditions like heavy rain or snow cause visibility issues, a substantial number of recorded accidents occur during relatively clear or cloudy conditions, indicating that high volume and driver behavior remain primary factors.
* **Geospatial Hotspots:** Utilizing coordinate mapping, we successfully clustered high-frequency incident zones, highlighting dangerous highway interchanges and major intersection bottlenecks.

---

## 🛠️ Methodology & Features Analyzed
1. **Time-Series Extraction:** Parsed raw timestamp data into localized 24-hour markers to map hourly distributions.
2. **Categorical Frequency Profiling:** Grouped and isolated the top environmental and weather alerts to pinpoint major contributing hazards.
3. **Geospatial Clustering:** Built an interactive mapping layer using coordinate point arrays to cluster geographic density seamlessly.

---

## 💻 Technologies Used
* **Languages:** Python 3.11.9
* **Data Wrangling:** `pandas`
* **Plotting & Visualizations:** `matplotlib` & `seaborn`
* **Geospatial Mapping Engine:** `folium` (with `MarkerCluster` plugins)