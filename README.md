# Live Product Intelligence for E-commerce

This project simulates the role of a Business Intelligence (BI) analyst at an e-commerce company. It builds a complete BI system that collects live product data, stores it in a database, predicts prices using machine learning, and visualizes key insights with interactive dashboards.


## Project Overview

The goal of this project is to demonstrate end-to-end capabilities in building a data-driven BI system similar to what large e-commerce companies like Amazon or Flipkart use to:
- Track product trends and performance in real-time  
- Analyze pricing and demand patterns  
- Predict product prices based on attributes and ratings  
- Create automated dashboards to monitor key business metrics


## Tools and Technologies Used

| Tool / Technology | Purpose                              |
|-------------------|------------------------------------|
| Python            | Data processing, modeling, visualization |
| pandas            | Data cleaning and manipulation      |
| scikit-learn      | Machine learning for price prediction |
| SQLAlchemy        | Python-PostgreSQL database connection |
| PostgreSQL (Render) | Free hosted SQL database            |
| FakeStoreAPI      | Source of live product data         |
| Google Colab      | Cloud environment for running Python code |
| Metabase          | Business Intelligence dashboards    |
| Matplotlib        | Visualizing prediction results      |


## Project Steps

1. **Set Up PostgreSQL Database:**  
   Created a free PostgreSQL database on Render.com to store live product data.

2. **Fetch and Store Live Product Data:**  
   Used Python and the FakeStoreAPI to pull real-time product information (like category, price, ratings) and store it in the database.

3. **Data Cleaning and Preparation:**  
   Cleaned and prepared the data using pandas, including handling categorical and numerical features.

4. **Build and Train a Price Prediction Model:**  
   Applied a linear regression model to predict product prices based on category and rating data.

5. **Save Predictions:**  
   Stored the predicted prices back into the PostgreSQL database for further analysis.

6. **Visualize Results:**  
   Created scatter plots comparing actual and predicted prices and built interactive dashboards in Metabase for product insights.

7. **Automate Updates:**  
   Setup automated workflows using Google Colab notebooks connected to the database to keep data and predictions up-to-date.


## Learning Outcomes

- End-to-end BI system design and implementation
- Working with live APIs to collect real-time data
- SQL database creation, management, and querying
- Data preprocessing and feature engineering with pandas
- Training and evaluating machine learning models with scikit-learn
- Data visualization and dashboard creation using Matplotlib and Metabase
- Automating workflows and connecting cloud services


## Project Structure

Google Colab notebooks: Python scripts for data fetching, processing, modeling, and visualization.
PostgreSQL database: Tables storing raw product data and model predictions.
Metabase dashboards: Interactive dashboards built on top of the database for business insights.
