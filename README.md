# Spatial-Soil-Analysis
An analysis and model system investigating how Clay, Organic Carbon, and pH interact and react with the soil around it, in the Region of South Africa.

# 🌍 Spatiotemporal Soil Analysis

### Clay, Organic Carbon, and pH Across Space and Time

## Overview

This project explores how key soil properties—**clay content**, **organic carbon**, and **pH**—vary across both **space and time**.

Rather than building a traditional predictive model, this work focuses on **insight-driven analysis**, combining spatial interpolation, temporal trends, and behavioral metrics to better understand how soil systems evolve.

The result is a lightweight **spatiotemporal insight framework** designed to extract structure, stability, and relationships from environmental data.

---

## Objectives

* Map spatial distributions of soil variables
* Analyze temporal trends and stability
* Identify relationships between variables over time
* Quantify system behavior (memory, volatility, structure)
* Build a cohesive, interpretable analytical pipeline

---

## Methods

### 1. Spatial Analysis

Spatial interpolation was performed using **Kriging**, a geostatistical method that estimates values across continuous space from discrete observations.

This enables:

* Smooth spatial surface generation
* Region-to-region comparison
* Identification of geographic patterns

---

### 2. Temporal Analysis

Each variable was aggregated across space to evaluate:

* Mean trends over time
* Changes in distribution
* Long-term directional movement

---

### 3. Relationship Analysis

Pairwise correlations were computed between:

* Clay ↔ Organic Carbon
* Organic Carbon ↔ pH
* Clay ↔ pH

These relationships were tracked over time to observe how interactions between variables evolve.

---

### 4. Behavioral Metrics

To move beyond static analysis, the following metrics were introduced:

#### Hurst Exponent

Measures long-term memory of a time series:

* **H > 0.5** → persistent trends
* **H ≈ 0.5** → random behavior
* **H < 0.5** → mean-reverting dynamics

Applied per spatial unit to understand local system behavior.

---

#### Variance (Volatility)

Quantifies stability over time:

* High variance → unstable regions
* Low variance → stable regions

---

#### Moran’s I

Measures spatial autocorrelation:

* High values → clustering of similar values
* Low values → spatial dispersion

---

## Key Insights

* Soil properties exhibit **distinct spatial clustering**, indicating localized environmental drivers
* Temporal trends vary by variable, with some showing **persistent behavior** and others **mean reversion**
* Relationships between variables are **not static**, evolving over time
* Behavioral metrics reveal differences between **stable regions** and **high-variability zones**

---

## Tools & Technologies

* Python (Pandas, NumPy, SciPy)
* Geospatial libraries (GeoPandas, PyKrige)
* Visualization (Matplotlib, Seaborn)

---

## Why This Project Matters

Most entry-level data science projects focus on prediction.

This project instead demonstrates:

* Spatial reasoning
* Time series analysis
* Feature interaction analysis
* Interpretable, insight-driven modeling

It reflects a shift from:

> “What can I predict?”
> to
> “What is the system doing?”

---

## Future Improvements

* Incorporate additional soil or environmental variables
* Apply clustering to identify behavioral regions
* Extend to full spatiotemporal modeling frameworks
* Integrate external climate or land-use data

---

## Author

**William V. Fullerton**
B.S. Statistics & Data Science (Dec 2025)
Robert Morris University

---

## Notes

This project was developed as part of a broader effort to build **clean, interpretable, and reusable analytical frameworks** for real-world data.
