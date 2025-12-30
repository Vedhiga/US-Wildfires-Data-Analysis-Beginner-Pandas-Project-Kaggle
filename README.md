# 🔥 Wildfire Trend Analysis Across U.S. States (2000 onwards)

##  Objective
The goal of this analysis is to understand how wildfire occurrences vary **across different U.S. states over time**, and to identify states that consistently experience a higher number of fires.  
In simple words: *Who is catching fire more often, and who is improving?* 

---

##  Dataset Overview
This dataset contains detailed records of wildfires across the United States, including:
- Fire occurrence year (`FIRE_YEAR`)
- State where the fire occurred (`STATE`)
- Fire size and related attributes

The dataset is large (1.88 million records), which makes it ideal for learning **real-world data analysis** rather than toy examples.

---

##  Data Preparation
Before visualization, a few important steps were performed:

- Focused on **fires from the year 2000 onwards** to analyze modern trends
- Selected **top wildfire-prone states** to avoid overcrowding the visualization
- Aggregated data using a **year × state** frequency matrix

---

##  Heatmap Visualization: FIRE_YEAR × STATE
A heatmap was created to visualize:
- **Rows** → Fire Year  
- **Columns** → U.S. States  
- **Color Intensity** → Number of wildfire incidents  

Darker colors indicate a higher number of fires, while lighter shades suggest fewer incidents.

---

##  Key Observations
- **Texas** clearly stands out as the most wildfire-prone state, consistently showing darker shades across multiple years.  
  
- **California** and **New York** also show relatively high wildfire activity, although with more variation across years.

- Several other states display **lighter colors over time**, indicating a possible reduction in wildfire incidents or better control measures.

---

##  Interpretation
The visualization suggests that wildfire risk is **not evenly distributed** across states.  
Some states continue to experience persistent wildfire activity, while others appear to have made progress in reducing incidents over time.

This highlights the importance of **state-specific wildfire management strategies**, rather than a one-size-fits-all approach.

---

## Conclusion
This heatmap provides a clear and intuitive overview of wildfire trends across U.S. states.  
It helps identify high-risk regions, observe long-term patterns, and supports data-driven discussions around wildfire prevention and management.
