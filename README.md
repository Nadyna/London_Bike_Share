# London Bike Share Analysis: Exploring bike-sharing demand in relation to weather factors and daily patterns

## Project Overview  
The goal of this analysis is to determine and evaluate the key factors associated with bike share ride volume.  
  
I analyzed historical bike-sharing data from Kaggle: [London Bike Sharing Dataset](https://www.kaggle.com/datasets/hmavrodiev/london-bike-sharing-dataset) to explore how factors like weather, time of day, season, and day type affect ride volume.

This dataset includes over 17,000 hourly records of bike rentals, with features such as:
- **Timestamp-based data** (date, working day, holiday)
- **Weather conditions** (temperature, temperature "feels like", humidity, wind speed, weather category, season)
- **Ride count** (the count of new bike shares)
I chose this dataset because it offers rich temporal and environmental variables, which are ideal for exploring real-world patterns in transportation behavior and building practical, data-driven insights.

## Tools & Technologies
- **Python** (pandas, matplotlib, numpy, seaborn, scipy)
- **Jupiter Notebook** for code development and narrative
- **Tableau** for dashboard creation
- **Data Sourse** [London Bike Sharing Dataset on Kaggle](https://www.kaggle.com/datasets/hmavrodiev/london-bike-sharing-dataset)

## Methodology
1. **Data Cleaning**
   - Used bike-sharing dataset from [Kaggle](https://www.kaggle.com/datasets/hmavrodiev/london-bike-sharing-dataset)
   - Performed missing values checks, corrected data types, engineered features
2. **Exploratory Data Analysis (EDA)**
   - Visualized distributions and relationships between variables using histograms, KDEs, Q-Q plots
   - Analyzed ride frequency across seasons, weekdays, hours and weather conditions
4. **Statistical Testing**
   - Applied correlation analysis (Pearson & Spearman)
   - Used ANOVA, Kruskal_wallis, Mann-Whitney U test for group comparison
   - Performed assumption testing where applicable (normality, skewness)
6. **Visualization & Interpretation**
   - Developed interactive dashboard using Tableau
   - Interpreted technical results and translated them into business-relevant insights
8. **Documentation & Communication**
   - Summarised both analytical and business insights

## Analytical Insights

## Business insights

## Interactive Tableau Dashboard
You can explore the interactive dashboard here:
[Click to view on Tableau Public](https://public.tableau.com/shared/WGZJJX8Z4?:display_count=n&:origin=viz_share_link)

![Dashboard Preview](images/dashboard_preview.png)
