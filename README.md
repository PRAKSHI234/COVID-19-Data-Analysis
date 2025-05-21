# COVID-19-Data-Analysis
By using Apache Spark and pyspark

🎯 Objectives
1. To analyze large-scale COVID-19 datasets using Apache Spark and PySpark.
2. To extract meaningful insights such as daily case trends, growth rates, and country-level summaries.
3. To apply grouping, window functions, and Spark SQL for advanced analytical tasks.
4. To simulate real-world data analytics on health-related time-series data.

📎 Skills Demonstrated
1.PySpark DataFrame APIs
2.Spark SQL & Window Functions
3.Time-series and GroupBy analysis
4.Data cleaning and transformation
5.Exporting results for visualization

⚙️ Implementations
1. Spark Session Setup:
Initialized a Spark session to handle large datasets with efficient in-memory processing.

2. Data Ingestion:
> Loaded global COVID-19 data (e.g., confirmed cases, deaths, recoveries) using Spark DataFrames.
> Handled structured data with date-wise case counts across multiple countries.

3. Data Cleaning & Transformation:
>Preprocessed the dataset to ensure schema consistency and remove nulls or irrelevant fields.
>Parsed dates and ensured correct typing for analytical operations.

4.Time-Series Analysis:
Used window functions (e.g., row_number, lag) to calculate:
> Daily new cases
> Daily growth rate
> Moving averages

Performed rolling analysis on time-based windows to track the spread.

5. Country-wise Aggregation: 
Grouped data by country to identify:
> Countries with highest daily spikes
> Overall trendlines over time
> Comparative metrics (e.g., % growth)

6. Data Export & Reporting:
> Saved key analytics results as CSV files for reporting.
> Designed outputs to be compatible with BI tools or dashboards.

✅ Outcomes
1. Successfully built a scalable data analytics pipeline to process pandemic data.

2. Gained practical experience using PySpark for:
> Window operations
> Grouped analytics
> Time-series trend detection

3. Derived actionable insights such as peak infection periods, top affected countries, and growth trends.

4. Produced clean, structured summaries suitable for visual analytics or research reports.
