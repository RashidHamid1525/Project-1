# Air Quality Data Analysis (Nebraska)

## Overview
This project analyzes air quality data collected from PurpleAir sensors across Nebraska to identify pollution trends, environmental impacts, and potential public health risks.

The work was completed for the UNMC Water, Climate, and Health Group as part of CIVE 202.

The goal was to transform raw environmental data into meaningful insights about:
- Air pollution levels
- High-risk locations
- Environmental influences (temperature, humidity, altitude)
- Health-related air quality concerns

---

## Data & Tools Used
- Dataset: PurpleAir sensor data (CSV format)
- Language: Python  
- Environment: Jupyter Notebook  
- Libraries:
  - pandas
  - numpy
  - matplotlib

---

## What This Project Does

### 1. Data Processing
- Loads and cleans raw air quality data
- Handles missing or incorrect values
- Organizes data by sensor and date

### 2. Pollutant Analysis
- Calculates:
  - Mean
  - Median
  - Maximum values
- Focus pollutants:
  - VOC (Volatile Organic Compounds)
  - PM2.5
  - PM10

### 3. Hotspot Identification
- Finds top 5 locations with highest pollution levels
- Identifies dates and locations of peak pollution events

### 4. Environmental Impact Analysis
- Categorizes:
  - Temperature (Below Freezing, Cool, Warm, Hot)
  - Altitude (Low, Medium, High)
- Examines how these factors affect pollution levels

### 5. Health Risk Detection
- Identifies unhealthy VOC levels (≥ 25)
- Highlights potential risks to sensitive populations

---

## Key Features in Code

- Pivot tables for summarizing pollutant data  
- GroupBy operations for sensor-level analysis  
- Custom functions for:
  - Temperature classification  
  - Altitude classification  
- Filtering for:
  - Maximum pollutant events  
  - Unhealthy air quality conditions

---

## How to Run This Project
1) Clone the repository:
    git clone https://github.com/your-username/your-repo-name.git
2) Install dependencies:
  pip install pandas numpy matplotlib
3) Open the notebook:
   jupyter notebook Project1.ipynb
4) Run all of the cells.

---
## Acknowledgements
- UNMC Water, Climate, and Health Group  
- PurpleAir Data Platform  
- U.S. Environmental Protection Agency (EPA)  
- AirNow (air quality resources)  
