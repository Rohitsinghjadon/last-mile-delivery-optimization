# Last-Mile Delivery Optimization

## Week 1 – Strategic Planning and Data Exploration

This repository supports a logistics data science project focused on improving **last-mile delivery performance**.

### Business Problem

An e-commerce logistics company wants to improve delivery reliability while controlling delivery cost and making better use of riders/vehicles. The project investigates delivery time, delays, traffic, weather, distance, rider experience, and delivery outcomes.

### Project Objectives

- Measure key last-mile delivery KPIs.
- Identify patterns associated with late deliveries.
- Explore operational differences between delivery zones.
- Build a baseline late-delivery prediction workflow.
- Prepare the project for future clustering and route/resource optimization.

### KPIs

1. **On-Time Delivery Rate**
2. **Average Delivery Time**
3. **Late Delivery Rate**
4. **First-Attempt Success Rate**
5. **Delivery Cost per Order**

### Data

`data/deliveries_synthetic.csv` is a **synthetic demonstration dataset** created for this project. It is not presented as real company data. The structure is designed to demonstrate the planned analytical workflow safely and reproducibly.

Potential real-world data sources for a future version include public logistics/delivery datasets from Kaggle and other open-data repositories.

### Methodology

```text
Data Collection
      ↓
Data Cleaning
      ↓
Feature Engineering
      ↓
EDA & KPI Analysis
      ↓
Late-Delivery Prediction
      ↓
Delivery-Zone Clustering
      ↓
Route / Resource Optimization
      ↓
Business Recommendations
```

### Python Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

### Run the Demo

```bash
pip install -r requirements.txt
python src/analysis.py
```

The script prints the main KPIs and trains a baseline Random Forest classifier for late-delivery prediction.

### Future Scope

- Time-based model validation
- Geospatial route analysis
- K-Means zone clustering
- Vehicle Routing Problem (VRP)
- Demand forecasting
- Power BI logistics dashboard
- Real-time delivery-risk monitoring

## Project Status

**Week 1: Strategic Planning and Data Exploration**

This repository is the technical companion to the Week 1 strategic planning report.
