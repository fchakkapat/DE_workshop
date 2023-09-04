# DATA ENGINEER WORKSHOP  
![image](https://github.com/fchakkapat/DE_workshop/assets/127225302/8999af4b-23f2-4c2f-9629-8a642f569c80)

## Workshop 1_Data Collection with python
Use `PyMySQL` Package to connect the `MySQL` database to `Python` for the purpose of data collection.Then, in order to make it simpler for users and improve the aesthetics of the tables, we changed it to `Pandas`. The tables (Employees & Jobs) were then joined and used the `Requests` package to obtain data from `REST APIs` in addition to a standard MySQL database. Finally, Saved the tables as a `CSV file`.
## Workshop 2_Data Cleansing with Pyspark
Clean and prepare are the part of data cleansing. Using Python's `PySpark` package, apply Spark in this cleaning process. First is prepare Python's environment. Loaded data into Spark after PySpark has been installed in Python. Then, Profiled the data to understand the various details of each column, including the count, mean, standard deviation, minimum and maximum. After that, we completed a sematic anomalies (such as rectifying the outlier) and a syntactical abnormalities (such as filling the null value). Finally, Saved the cleansed data as `CSV files`.  
## Workshop 3_Upload Data to Datalake (Google Cloud Storage)  
Explore the methods to upload data to a datalake using Google Cloud Storage, learn to upload data via the web UI, command, and API Python code.
## Workshop 4_Data Pipeline Orchestration (Airflow)
To create Pipeline to perform the process by set DAG ( Directed Acyclic Graph) and Create Environment on Google Cloud Composer and Run `Apache Airflow` from the pipeline that we created.
## Workshop 5_Data Warehouse (BiqQuery)
To load the data for workshop4 to `BigQuery` by using pipeline with Airflow.
## Workshop 6_Data Visualization (Looker studio)
Create data visualization from workshop5 data to analyze by BA or DA or DS next.
