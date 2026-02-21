# Carbon and GHG Emissions and global factors affecting them

## 📌 Problem Statement
Global carbon (CO₂) and greenhouse gas (GHG) emissions continue to rise, contributing significantly to climate change. This project investigates:
Which countries contribute most to global CO₂ and GHG emissions?
What are the major factors driving these emissions?
How do GDP and population correlate with emission levels?
What role does the aviation industry play in overall emissions?
Which flight types and aviation activities contribute most?

## 📂 Dataset
- Source: Our World in Data (OWID) and Organisation for Economic Co-operation and Development (OECD)
- Size: 60k+ records
- Key features: country, carbon and ghg emissions from sources like cement production, methane emissions per capita, 
emissions due to land-use change, etc

## 🔍 Approach
- Pulling the data using an API call
- Processing and structuring the data using PySpark
- Data cleaning
- Exploratory data analysis
- Creating a Power BI dashboard to draw insights

## 📊 Key Insights
- Even though the overall CO2 emissions from cement industry are low in comparison to other sectors, they have increased significantly over time which is obviously because of increased infrastructure, road developments and urbanization. 
- Land use change contributes significantly to overall CO2 emissions every year and hence, urbanization needs to be properly planned and avoid excessive conversion of forest area to agricultural or other such type of land uses.
-  “High-income countries” i.e. the countries with a high Gross National Income(GNI) per Capita contribute to more than 50% of the overall CO2 emissions.
-  The contribution to overall emissions from the aviation industry has always been significant from “Passenger” flights than the “Cargo or Freight” flights and in recent years, the emissions from “Cargo” flights have also increased significantly.

## 🛠 Tech Used
Google Cloud Storage (Blob Storage) | Python | PySpark | MongoDB | Power BI

## 🚀 Business Impact
This analysis can support:
📊 ESG and sustainability analysts in evaluating the relationship between economic growth and environmental impact.
✈️ Aviation industry stakeholders in understanding which flight types and operational activities contribute most to emissions.
💰 Governments and economic planners in assessing whether GDP growth correlates with carbon intensity.
📈 Data-driven climate strategy development through scalable processing of large environmental datasets.
🌍 Policy makers in identifying high-emission countries and sectors to design targeted climate regulations.

By combining economic, demographic, and sector-specific data, this project demonstrates how data analytics can inform climate policy and sustainability initiatives.
