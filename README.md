# earthquake-prediction-model
This model predicts the magnitude class of earthquakes

# 🌍 Earthquake Magnitude Classification Model

This repository contains a Machine Learning project that **predicts the magnitude class of earthquakes** using historical seismic data. It’s built as a practical example of applying ML to geophysical data.

---

## 📚 About the Project

Using global earthquake data (e.g. USGS/ISC catalogs), this model classifies earthquakes into categories:

- **Minor** (< 5.0)
- **Moderate** (5.0 – 5.9)
- **Strong** (6.0 – 6.9)
- **Major** (≥ 7.0)

The model leverages features such as:

✅ Latitude  
✅ Longitude  
✅ Depth  
✅ Month of occurrence

This project demonstrates data preprocessing, feature engineering, model training, and visualization for real-world datasets.

---

## 🗂 Dataset

The dataset used has columns like:

| Column        | Description                     |
|---------------|---------------------------------|
| Date          | Date of earthquake              |
| Time          | Time of earthquake              |
| Latitude      | Epicenter latitude              |
| Longitude     | Epicenter longitude             |
| Depth         | Depth in km                     |
| Magnitude     | Earthquake magnitude            |
| Type          | Type of seismic event           |
| Other columns | Metadata from seismic catalogs  |

**Example Record:**

| Date       | Time     | Latitude | Longitude | Depth | Magnitude | Type       |
|------------|----------|----------|-----------|-------|-----------|------------|
| 01/02/1965 | 13:44:18 | 19.246   | 145.616   | 131.6 | 6.0       | Earthquake |

---

