# Ecommerce Revenue Pipeline

## Description
This pipeline was built and deployed by me.
Note: I didnt use delta lake because the data needs to handle incremental processing.

## Pipeline
![Image Alt Text](images/ecommerce-revenue-pipeline.png)

## Explain icons

| Icon | Description |Phrase|
|-----------------|-----------------|-----------------|
|![Image Alt Text](images/AirflowLogo.png)|Airflow|Data source|
|![Image Alt Text](images/deployment.png)|K8s Deployment|Silver processing|
|![Image Alt Text](images/hudi.png)|Hudi|Silver processing|
|![Image Alt Text](images/cronjob.png)|K8s Cron Job|Gold processing|
|![Image Alt Text](images/hive.png)|Hive|Storage Layer|
|![Image Alt Text](images/superset.png)|Superset|Dashboard|

