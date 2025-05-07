# Solar Augmentation Potential of U.S. Fossil-Fired Power Plants  
**Project: Udacity Data Visualization**

This project analyzes the potential for integrating solar thermal energy into existing or planned fossil-fueled power plants in the southern, western, and central U.S. states. Using data from the NREL Geothermal Prospector and Electric Power Research Institute (EPRI), I evaluated how plant characteristics, fuel source, and solar augmentation technologies intersect to influence capacity expansion and pollution reduction outcomes.

---

## Project Objective

To explore and communicate, through effective data visualization, which coal and natural gas plants offer the highest solar augmentation potential using either power tower or parabolic trough technology. Emphasis is placed on:

- Ranking solar integration feasibility
- Comparing augmentation technologies
- Identifying standout states and plants by fuel type and potential

---

## Data Source

- **Geothermal Prospector:**  
  https://maps.nrel.gov/?da=geothermal-prospector  
- **NREL Report:**  
  https://www.nrel.gov/docs/fy11osti/50597.pdf  
- **Map Shapefiles:**  
  https://www.naturalearthdata.com/

---

## Methodology Summary

- Combined two raw datasets into a cleaned dataframe with 633 records and 9 variables
- Merged plant location, capacity, fuel type, solar tech type, and augmentation scores
- Visualized relationships using Seaborn, Matplotlib, and geopandas
- Prioritized clarity, accessibility, and stakeholder relevance (e.g. colorblind-safe palettes)

---

## Key Visuals & Findings

### 1. **Augmentation Potential by Technology and Fuel Type**  
- Power tower technology consistently provides higher augmentation capacity than parabolic trough
- Coal plants yield greater solar augmentation potential than natural gas plants
- Plants ranked "Good" or "Fair" often provide substantial capacity, supporting strategic investment beyond "Excellent" sites

### 2. **State-by-State Augmentation Rankings**  
- **Arizona** leads in "Excellent" potential across both fuel types  
- **Texas** has the highest total augmentation potential but mostly from "Good" and "Fair" ranked plants  
- Highlights nuanced trade-offs between quantity and quality of opportunities across states

### 3. **Interactive Map of Top Plants**  
- Displays up to 3 top-ranked plants per state by fuel type and capacity  
- Visualizes where investments in solar augmentation may yield greatest returns  
- Map designed for rapid stakeholder insight at both national and state level

---

## Final Insights

- Coal plants, particularly with "Good" or better ranks, are prime candidates for solar augmentation
- Power tower technology should be prioritized for maximum capacity gain
- State-level energy policies could benefit from geospatial, rank-weighted analysis when allocating infrastructure funds
- Arizona stands out as a high-priority state for solar-fossil hybrid retrofitting

---

## Skills Demonstrated

- Data wrangling, cleaning, and preparation
- Multivariate visual analysis
- Geospatial visualization using geopandas
- Strategic storytelling through data
- Adherence to visualization best practices

---

*Submitted as part of the Udacity Data Analyst Nanodegree. Project evaluated and passed with distinction.*