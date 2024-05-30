# New york motor vehicle collision analysis from 2012-2024 using Pyspark, Azure Blob storage and Power BI

### Complete pyspark code to extract, load, and transform CSV data for new york motor vehicle collision data [New York Motor Vehicle Collision CSV Data](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Vehicles/bm4k-52h4/about_data)

<br>

👉 &nbsp; This repository contains a code to extract, load, transform, and analyze motor vehicle crash data from the publicly available datasets by New York city using PySpark, Azure and Power BI. Below are the tech stack involved in this project.

👉 &nbsp; This repository intends to give an overview of how pyspark code can be leveraged to extract, load, transform, and analyze Big Data.

👉 &nbsp; Provided dataset contains 4.5 million of records containing crash data from 2012 to 2024.

<br>

## Tech stack

- Azure Blob Storage
- Databricks Notebook and Spark Cluster
- PySprak
- Power BI

## Steps Performed

- Motor crash CSV data is loaded into Azure Blob Storage

- Created Databricks workspace and Spark cluster on Databricks to write pyspark code for ETL

- Using Pyspark notebook, data is first loaded and transformed to remove null, and duplicate values as well as added new columns such as Year of crash, month of Crash etc which simplifies the further analysis of data.

- Performed analysis using pyspark code to understand the data better.

- Load the cleaned dataset again into Azure blob storage in the form of CSV.

- Connected Azure blob container containing cleaned CSV data as data source in Power BI

- Before building the dashboard, some more columns were added such as a string representation of the month in which the crash happended.

- Built detailed dashboards using a cleaned version of Motor vehicle crash data, below is the snapshot of the Power BI dashboard.

- Added further drill down by Year, to analyze the crash data year-wise.

### Motor Vehicle Collision Data Power BI dashboard

![alt text](https://github.com/abhijitmorye/new-york-motor-vehicle-collision-analysis/blob/main/img/mv_crash_power_bi_dashboard.JPG?raw=true)

### Azure Blob Storage Snapshot

![alt text](https://github.com/abhijitmorye/new-york-motor-vehicle-collision-analysis/blob/main/img/mv_azure_blob_storage.JPG?raw=true)

## Note

Data file has been deleted since file size exceeded for github push. You can find the lnk for dataset in description.
