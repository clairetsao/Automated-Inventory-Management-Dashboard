# Automated-Inventory-Management-Dashboard
## Overview
This project aims to create an automated inventory management dashboard that enables warehouse managers and procurement teams to track the latest stock levels, preventing stockouts and overstocking. The dashboard provides insights through various analyses and visualizations to support data-driven decision-making.

<img width="1080" alt="Screenshot 2024-05-25 at 11 49 49 AM" src="https://github.com/clairetsao/Automated-Inventory-Management-Dashboard/assets/145289997/5ce13d94-cc5c-4914-972d-a6c9adc8b580">


I build the ETL pipeline based on the following process

<img width="1078" alt="Screenshot 2024-05-25 at 11 49 27 AM" src="https://github.com/clairetsao/Automated-Inventory-Management-Dashboard/assets/145289997/d8272aab-1b43-483a-8c1c-5447f401d2fa">

## Extract
The data ingestion process retrieves and verifies data from the following sources:
- Material_Master_Data.xlsx
- Sales_Order.xlsx
- Stock_level.xlsx


## Transform
Automated data transformation is performed using a Jupyter Notebook. The extracted data is processed and organized to ensure it is usable for analysis. The following data analyses are conducted:
- ABC Inventory Classification: Categorizing items based on their value to prioritize management efforts.
- XYZ Classification: Categorizing items based on the variability of their demand.
- Inventory Turnover Ratio: Calculating how often inventory is sold and replaced over a period.
- Safety Stock & Reorder Points: Determining optimal stock levels to avoid stockouts.
- Stock Status Classification: Classifying inventory based on current stock levels and status.


## Load 
The transformed data is moved to a data repository and connected to Tableau for data visualization. This setup enables the creation of an interactive dashboard that displays the latest stock levels and prioritizes important items.
<img width="988" alt="Screenshot 2024-05-25 at 11 32 11 AM" src="https://github.com/clairetsao/Automated-Inventory-Management-Dashboard/assets/145289997/52ae1d30-2921-4b21-a080-bc71ca4ccc52">
