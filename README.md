##Real-Time Data Ingestion Using Apache Airflow##

This project demonstrates real-time data ingestion by consuming data from a public API, processing it using Python, and storing it in a database. The entire workflow is orchestrated with Apache Airflow.

#Workflow Description
Data Ingestion:

A Python script fetches data from a public API at regular intervals.
The script handles API authentication (if required) and parses the data into a usable format.
Data Processing:

The fetched data is cleaned and transformed using Python.
Transformations may include filtering, aggregation, or reformatting the data for compatibility with the database schema.
Data Storage:

The processed data is stored in a database (e.g., PostgreSQL, MySQL).
The database schema is predefined to handle the ingested data structure.
Orchestration with Apache Airflow:

Apache Airflow schedules and orchestrates the entire pipeline.
A Directed Acyclic Graph (DAG) is created to define the workflow steps:
Task 1: Fetch data from the API.
Task 2: Process the data.
Task 3: Insert the processed data into the database.
Airflow handles task dependencies, retries, and logging.


Repository Contents
dags/: Contains the Airflow DAGs for orchestrating the workflow.
scripts/: Python scripts for API consumption, data processing, and database interactions.
docker-compose.yml: Docker setup for deploying Airflow and other services (e.g., database).
requirements.txt: Python dependencies for the project


# Airflow Docker Setup with MySQL and phpMyAdmin

This repository provides a complete setup for running **Apache Airflow** with **MySQL** and **phpMyAdmin** using Docker Compose.

## Features
- **Airflow Webserver** for workflow orchestration
- **MySQL** as the backend database for Airflow
- **phpMyAdmin** for managing the MySQL database via a web interface
- Modular folder structure for better organization
- Easy-to-deploy setup with Docker Compose

---

## Services

| Service          | Description                        | URL                          |
|-------------------|------------------------------------|------------------------------|
| Airflow Webserver | Airflow's web-based interface     | [http://localhost:8080](http://localhost:8080) |
| phpMyAdmin        | MySQL database management         | [http://localhost:8081](http://localhost:8081) |




![Screenshot 2025-01-12 094653](https://github.com/user-attachments/assets/631a7ffa-82ae-4236-b934-9cae588f445e)


![image](https://github.com/user-attachments/assets/7b818a71-3d84-4ee9-8196-8f99da37ee2a)







![image](https://github.com/user-attachments/assets/ac88bb53-919f-41c9-911a-b750a84b01d9)








