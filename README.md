# Global Energy Trends: A Comprehensive Analysis of Key Regions and Generation Modes using Power BI

### SmartInternz Internship Project

##  Project Overview
This Power BI project provides a comprehensive analysis of **global energy production, consumption, and sustainability trends** across major regions and energy sources. Developed during the **SmartInternz internship**, the dashboard delivers actionable insights into how renewable and non-renewable energy generation impacts global development and environmental goals.

##  Objectives
- Analyze energy generation and consumption patterns by **continent and country**.
- Compare **renewable** and **non-renewable** power generation trends.
- Highlight the shift towards **sustainable and clean energy** sources.
- Enable data-driven decision-making through **interactive visualizations**.

##  Tools & Technologies
- **Microsoft Power BI** – Data modeling, analysis, and visualization
- **Microsoft Excel / CSV** – Dataset storage and preprocessing
- **Kaggle Dataset:** [Renewable Power Generation](https://www.kaggle.com/datasets/jamesvandenberg/renewable-power-generation)

##  Key Insights

- Global comparison of **energy generation trends** by region and type.
- Breakdown of **renewable vs. non-renewable** contributions.
- Identification of leading countries in **sustainable energy adoption**.
- Insights into **regional energy consumption** and **TWh patterns**.

##  Data Model & Relationships
Each dataset includes an **Index column** to establish relationships between tables:
- **Continent_Table** → Related to **Country_Table** via `Continent`
- **Country_Table** → Linked with **Country_Consumption_TWH** and **Country_Generation_TWH** via `Country`
- **Continent_Consumption_TWH** and **Continent_Generation_TWH** → Connected via `Continent`
These relationships ensure accurate aggregation and filtering across visuals.

##  Dashboard Features
- Global and regional **energy trend visualizations**
- **Dynamic filters** for year, continent, and generation mode
- **Maps, charts, and KPI cards** for intuitive data exploration
- Clear comparison between **renewable** and **non-renewable** sources


## How to View the Dashboard

1. **Download the `.pbix` file** from this repository.
2. Open the file using **Microsoft Power BI Desktop**.
3. Explore visuals with **interactive filters and slicers**.
4. Optionally, **publish the report to Power BI Service** for online sharing.

