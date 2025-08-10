# Live Product Intelligence for E-commerce 

I built a comprehensive, real-time Business Intelligence system tailored for an e-commerce platform. This system collects live product data, stores it efficiently in a cloud-hosted database, predicts product prices using machine learning, and visualizes actionable insights through dynamic, interactive dashboards.

Designed to enable data-driven decision-making at scale — on par with industry leaders like Amazon, Flipkart, and Myntra.


## System Overview

The system continuously tracks, analyzes, and predicts product performance in real-time, providing critical capabilities such as:

- Instant monitoring of product trends and customer demand  
- Deep insights into pricing patterns and competitive intelligence  
- Accurate price predictions based on product attributes and customer ratings  
- Automated, interactive dashboards that deliver meaningful business metrics to stakeholders  

This end-to-end BI system integrates data ingestion, processing, predictive modeling, and visualization into a seamless workflow.


## Tools and Technologies

| Tool / Technology       | Role                                                  |
|------------------------|-------------------------------------------------------|
| **Python**             | Core data processing, modeling, and visualization engine |
| **pandas**             | Data transformation and feature engineering           |
| **scikit-learn**       | Machine learning framework for price prediction       |
| **SQLAlchemy**         | Database connectivity and operations with PostgreSQL  |
| **PostgreSQL (Render)**| Cloud-hosted, scalable database backend               |
| **FakeStoreAPI**       | Real-time product data ingestion source                |
| **Google Colab**       | Cloud environment for running and automating workflows|
| **Metabase**           | Business Intelligence dashboards for visualization     |
| **Matplotlib**         | Custom data visualizations and model evaluation plots  |


## Implementation Details

1. **Database Setup:**  
   Provisioned a PostgreSQL database on Render.com to securely store incoming product data and prediction results.

2. **Data Ingestion:**  
   Integrated the FakeStoreAPI to fetch real-time product attributes, prices, and ratings, storing this data continuously in the database.

3. **Data Preparation:**  
   Processed and cleaned raw data using pandas, including handling categorical and numerical variables to prepare for modeling.

4. **Predictive Modeling:**  
   Developed and trained a linear regression model that predicts product prices based on category and rating data.

5. **Prediction Storage:**  
   Saved all price predictions back into the PostgreSQL database, enabling further analysis and dashboarding.

6. **Visualization:**  
   Created scatter plots and interactive Metabase dashboards to compare actual vs predicted prices and provide actionable business insights.

7. **Workflow Automation:**  
   Automated data fetching, model retraining, and dashboard updates using Google Colab notebooks, ensuring the system remains current with minimal manual effort.


## Key Competencies Demonstrated

- Architecting a scalable, end-to-end Business Intelligence pipeline  
- Working with live APIs and real-time data streams  
- Building robust SQL database schemas and efficiently querying data  
- Engineering features and training machine learning models with scikit-learn  
- Crafting insightful visualizations and interactive dashboards for stakeholders  
- Automating cloud-based workflows for continuous data and model updates  


## System Components

- **Google Colab notebooks:** Control scripts for data extraction, processing, modeling, and visualization.  
- **PostgreSQL database:** Central data warehouse storing raw and processed data along with prediction results.  
- **Metabase dashboards:** Custom BI dashboards delivering rich insights from the data in real-time.

