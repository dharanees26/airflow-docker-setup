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

---

## Folder Structure

```plaintext
├── dags/               # Airflow DAGs
├── scripts/            # Python scripts for data ingestion and database operations
├── config/             # Configuration files (e.g., db_config.json)
├── sql/                # SQL files for database setup
├── logs/               # Airflow logs
├── Dockerfile          # Dockerfile for Airflow image
├── docker-compose.yml  # Docker Compose configuration
├── requirements.txt    # Python dependencies
└── README.md           # Project documentation








