# Real-Time IoT Data Pipeline

A data engineering project that simulates IoT sensor data and processes it through batch and streaming pipelines to support real-time monitoring, anomaly detection, and data visualization.

## Project Overview

This project focuses on building a pipeline for temperature and humidity sensor data. It covers data generation, ingestion, ETL processing, streaming analytics, alerting, and dashboard development.

The project is part of the AI & Data Science Track and is aligned with Data Pipelines and Big Data Processing.

## Project Objectives

- Simulate temperature and humidity sensor readings.
- Ingest and store incoming sensor data.
- Build a batch ETL pipeline to transform and process data.
- Implement streaming analytics and threshold-based alerts.
- Visualize sensor metrics through a dashboard.
- Document the system architecture, implementation, and results.

## Project Milestones

### Milestone 1 — Data Simulation and Ingestion

- Generate sensor readings using Python.
- Simulate new readings every five seconds.
- Store data in files or a message queue.

Deliverables:
- Sensor data generator.
- Sample data logs.

### Milestone 2 — Batch Data Pipeline (ETL)

- Extract data from CSV files or a stream.
- Transform data by calculating averages and identifying anomalies.
- Load processed data into SQL storage or a data lake.

Deliverables:
- ETL script or Azure Data Factory pipeline.
- Processed dataset.

### Milestone 3 — Streaming Pipeline and Alerts

- Process incoming data in real time.
- Apply threshold-based alert rules.
- Explore Apache Kafka or Azure Stream Analytics.

Deliverables:
- Streaming pipeline implementation.
- Alert logic and output.

### Milestone 4 — Dashboard and Final Report

- Visualize sensor readings and key metrics.
- Present alerts and pipeline results.
- Document findings and system performance.

Deliverables:
- Dashboard or demonstration.
- Final project report.

## Technology Stack

The planned technologies include:

- Python
- SQL
- CSV
- Apache Kafka or Azure Stream Analytics
- Azure Data Factory (optional)
- Power BI, Streamlit, or Grafana

The final technology stack will be documented as implementation decisions are made.

## Repository Structure

```text
real-time-iot-data-pipeline/
├── docs/
├── data/
├── src/
│   ├── ingestion/
│   ├── batch_etl/
│   ├── streaming/
│   └── alerts/
├── dashboard/
├── tests/
├── reports/
├── requirements.txt
├── .gitignore
└── README.md
```

Directories and files will be added as development progresses.

## Project Status

Planning and repository setup.

Implementation progress, documentation, and deliverables will be updated throughout the project.

## Team

Developed collaboratively as a graduation project.

Team members and responsibilities will be added as the team setup is completed.

## License

No license has been selected yet.
