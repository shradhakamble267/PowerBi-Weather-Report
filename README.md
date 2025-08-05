# 🌍 Weather Analysis Dashboard

This Power BI dashboard offers a geographic and statistical overview of weather-related data across cities and countries. It utilizes the **`cities`** dataset, which includes detailed location attributes such as city, state, station ID, longitude, latitude, country, ISO2, and ISO3 codes.

---

## 📊 Dashboard Overview

The dashboard is structured into multiple visual components that help users explore and interpret spatial data:

### 1. Sum of Latitude by City
- A bar chart visualizing the total latitude values for cities like:
  - Longyearbyen
  - Tromsø
  - Murmansk
  - Naryan-Mar
  - Salekhard
  - Rovaniemi
  - Oulu
  - Anadyr
  - Tura
  - Nuuk

### 2. Average Latitude
- A large numeric card displaying the **average latitude** across all entries: **23.73**

### 3. Country & State Filters
- Interactive slicers to filter data by:
  - **Countries**: Afghanistan, Albania, Algeria, American Samoa, Andorra, Angola, Anguilla, Antigua and Barbuda
  - **States**: Badakhshan, Badghis, Jawzjan, Kunar, Kunduz, Nangarhar, Dibër, Durrës, Shkodër, Adrar

### 4. Sum of Latitude by State
- A donut chart showing latitude totals by state, including:
  - Unknown
  - Southern
  - Skåne
  - Krasnoyarsk
  - Crimea
  - Montana

### 5. Count of States by Longitude
- A pie chart representing the number of states at specific longitudes:
  - -80.4599
  - -73.2500
  - -70.2500
  - -63.6000
  - -16.2500
  - 10.4003
  - 3.0800

### 6. Report Description
> "This report shows how the longitude and latitude differ from country to country and state to state. ISO most commonly refers to isotherms, which are lines on weather maps connecting points of equal temperature."

---

## 🗂 Dataset Details

- **Dataset Name**: `cities`
- **Columns**:
  - `city`
  - `state`
  - `station id`
  - `longitude`
  - `latitude`
  - `country`
  - `iso2`
  - `iso3`

---

## 🚀 How to Use

- Use filters to explore specific regions.
- Compare latitude and longitude distributions across cities and states.
- Use visual summaries to identify geographic trends and anomalies.

---
