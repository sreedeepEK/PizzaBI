## PizzaBI 

This repository contains sales analysis and dashboarding for a pizza dataset using SQL and Power BI. The goal was to simulate a real-world analyst task and show how SQL and Power BI work together to turn data into insights.


### Dashboard Link (PDF & PBIX file)

- 📄 **PDF Version:** [`dashboard.pdf`](https://github.com/sreedeepEK/PizzaBI/blob/main/dashboard.pdf)
- 📊 **Power BI File (PBIX):** [`dashboard.pbix`](https://github.com/sreedeepEK/PizzaBI/blob/main/dashboard.pbix)


## Preview

![Demo](https://github.com/sreedeepEK/PizzaBI/blob/b4ee754dfa7fe31675675a524feb41bba2876a37/demo.gif)

#### Data Processing (SQL)

##### Data Ingestion
- CSV files loaded into staging tables  
- Schema and data types validated  

##### Data Cleaning
- Date and numeric field standardization  
- Handling null and invalid values  
- Removal of redundant columns  

##### Transformations
- Table joins for consolidated datasets  
- Derived columns for analytical use  
- Aggregations for reporting-ready tables  


##### Business Metrics (SQL)

Key analytical outputs include:

- Revenue and profit calculations  
- Time-based performance (monthly/yearly)  
- Category and segment-level analysis  
- Summary tables for reporting consumption  


##### Power BI Data Model

- Connection to final SQL tables/views  
- Relationship management between tables  
- Data type and format validation  
- Measures created using DAX for KPIs  


##### Dashboard Features

- KPI summary cards  
- Trend analysis visuals  
- Category and segment breakdowns  
- Interactive slicers and filters

## License

This project is licensed under the MIT License.

See the [LICENSE](https://github.com/sreedeepEK/PizzaBI/blob/main/LICENSE) file for details.
