# Citibike-Station-Inventory-Tracking

## Project Overview
This project focuses on designing and implementing a comprehensive end-to-end ETL/ELT pipeline using Spark streaming and Delta Lake. The pipeline handles bike and weather data, facilitating the development of a forecast model to predict hourly net bike changes at designated stations. MLflow is employed for model development and management, while real-time monitoring ensures performance consistency between staging and production environments.

## Features
ETL/ELT Pipeline: Utilizes Spark streaming and Delta Lake for efficient and scalable processing of bike and weather data.

Forecast Model: Develops a forecast model based on historical data, predicting hourly net bike changes at specified stations.

MLflow Integration: Leverages MLflow for streamlined model development, tracking, and versioning.

Real-time Monitoring: Implements real-time monitoring to compare staging and production model performance, ensuring consistency.

Pipeline Immutability: Ensures the immutability of the pipeline for data integrity and reproducibility.

## Requirements
Apache Spark
Delta Lake
MLflow
