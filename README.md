# ABC Car Sale Dashboard


### Project Overview
The objective of this project is to analyze customer car preferences based on the company's sales history. By leveraging historical sales data, we aim to identify trends, patterns, and insights that can help the company make informed decisions about inventory management, marketing strategies, and customer segmentation.


### Tools
  - Python - Data cleaning
  - Power BI- Creating Dashboard


### Data Cleaning/Preprocessing
  - Removed Missing values from the variable ‘Levy’.
  - Variables with ‘0’ as a data value which doesn’t have a logical meaning remove in Engine volume & Price.
  - Remove the unnecessary string terms from Mileage and Engine volume variables.
  - Add new Columns:
      - Manufacturer categorised according to Manifacture_country.
      - Categorized the Condition according to the Mileage variable.(Mileage = 0 Brand new and otherwise into Used)



### DashBoard 
  [click here >>>>>](https://github.com/DanukaDilshann/Power-BI-Dashboard/blob/main/Dashboard/Dashboard.md)

### Key Insights
  - Vehicles manufactured in Japan, South Korea, Germany and United State are sold mostly.
  - Over 95% of the vehicle sold are second-hand and manufactured within 2006 to 2020 .
  - Front Wheel vehicles have more demand.
  - Selected 4 manufacturing countries have 33 manufacturing companies and almost 695 vehicle models from them were sold.
  - High demand for Black or White, Automatic gear vehicles with less than 1M mileage.
  - Leathered interior was preferred more.
