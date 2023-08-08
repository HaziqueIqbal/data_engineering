## Hi folks 👋
### Welcome to my Uber Analytics Project
In this project, I conducted an analysis on an Uber dataset, which can provide valuable insights to organizations for making informed decisions through the interpretation of visualized data.
You can find code in [Jupyter Notebook](https://github.com/HaziqueIqbal/uber_data_engineering/tree/main/uber_analytics/Notebook)
### Project Architecture
The data is stored within GCP's cloud storage. Subsequently, I employed Compute Engine to deploy MAGE.AI, wherein I established an ETL pipeline on the deployed MAGE instance. Data is sourced from Google Cloud Storage, undergoes transformation, and is subsequently stored in Big Query. The creation of reports and visualization of the data was accomplished using Looker Studio.

<p align="center">
  <img src="https://github.com/HaziqueIqbal/uber_data_engineering/blob/main/uber_analytics/Images/Architecture.png">
</p>

### Build With
- Python
- Google Cloud Store
- Google Compute Engine
- Google BigQuery
- Google Looker Studio
- Mage-AI

### ETL Pipeline
<p align="center">
  <img src="https://github.com/HaziqueIqbal/uber_data_engineering/blob/main/uber_analytics/Images/ETL.PNG">
</p>

### Database Schema
<p align="center">
  <img src="https://github.com/HaziqueIqbal/uber_data_engineering/blob/main/uber_analytics/Schema/uber_schema.drawio.png">
</p>

### Uber Dashboard
![dashboard_image](https://github.com/HaziqueIqbal/uber_data_engineering/blob/main/uber_analytics/Looker/Uber_Dashboard_2023-1.png)
