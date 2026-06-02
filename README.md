#  Airbnb Rental Economy Analytics

This project provides a comprehensive data analysis of Airbnb listings, processed using Apache Spark to handle large-scale datasets. The project explores pricing trends, geographical distribution, and review metrics to understand the rental economy.

## Key Features
- **Big Data Processing:** Utilized PySpark for efficient cleaning and aggregation of over 276,000 listing records.
- **Data Engineering:** Automated the transformation of raw data into a structured format suitable for high-performance analysis.
- **Interactive Dashboard:** Integrated a dashboard directly within the Jupyter Notebook environment using ipywidgets for exploratory data analysis (EDA).
- **Visual Analytics:** Includes dynamic charts and real-time metric updates based on geographical filtering.

##  Project Structure
- /data/cleaned/: Contains the processed datasets ready for analysis.
- /notebooks/: Contains the end-to-end processing and analysis pipeline.
    - 04_pyspark_analysis.ipynb: The main analytical notebook featuring the interactive dashboard.

## 🛠 How to Run
1. Ensure you have pyspark, pandas, matplotlib, and ipywidgets installed in your environment.
2. Open the project in VS Code.
3. Navigate to notebooks/04_pyspark_analysis.ipynb.
4. Run all cells.
5. Use the **interactive dropdown menu** at the bottom of the notebook to filter by city and visualize the data.

##  Dashboard Interface
The project features a built-in dashboard interface that allows users to:
- Select a city to filter data.
- View real-time calculations for listing counts and nightly price averages.
- Visualize room type distribution through dynamically generated charts.