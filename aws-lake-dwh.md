## Data lake S3 and Data warehouse Redshift

**Description:** The data ingestion comes from data pipelines built with Lambda or Emr for big data process. The data are encrypted and compressed on S3 with the right data format. The Data warehouse on Redshift contains the tables, the views and the materialised views to provide the cleaned data ready for analysis. Both PowerBi and Tableau visualisation tools can be connected to Redshift to visualise the data in real time

<img src="images/aws-lake-dwh.png?raw=true"/>