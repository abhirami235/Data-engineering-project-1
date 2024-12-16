# Uber Data Analytics - Modern Data Engineering Project

##Introduction
This project demonstrates a complete Modern Data Engineering pipeline for analyzing Uber trip data, leveraging cutting-edge tools and technologies in the Google Cloud Platform (GCP) ecosystem. The project aims to process, analyze, and derive meaningful insights from Uber's trip dataset while showcasing efficient, scalable, and modern data engineering practices.
## Project Overview

In this project, we:
Utilize Mage.ai, a modern orchestration tool, to design and manage the data workflows.

Store and process raw datasets using Google Cloud Storage for reliable and scalable data handling.

Load and transform the data in BigQuery, Google’s fully-managed data warehouse, to enable advanced analytics and querying at scale.

## Objectives
Data Ingestion: Seamlessly ingest raw Uber trip data into Google Cloud Storage.

Data Transformation: Clean, process, and transform the data using Mage.ai pipelines.

Data Analysis: Use BigQuery to perform analytics and derive insights, such as ride demand trends, peak usage times, and popular pickup/drop-off locations.

Scalability and Automation: Leverage GCP's serverless capabilities to create a pipeline that is highly scalable, efficient, and automated.
## Key Features
Automated Workflows: Mage.ai facilitates the creation and monitoring of robust ETL workflows.

Cloud-Native Approach: By relying on GCP tools, the project takes advantage of the platform’s scalability, security, and managed infrastructure.

Actionable Insights: Advanced analytics performed on BigQuery provide data-driven insights that can be applied to business decisions.


## Architecture
![Project Architecture](architecture.jpg)

## Technology Stack
1. Programing language - Python
2. Scripting Language - SQL
3. Google Cloud Platform
   - BigQuery
   - Cloud Storage
   - Looker Studio
   - Compute Instance
4. Mage.AI (Modern Data Pipeline Tool)
5. **Modern Data Pipeline Tool:** https://www.mage.ai/

## Datasets Used
TLC Trip Record Data 
The project uses the TLC Trip Record Data, a publicly available dataset maintained by the NYC Taxi and Limousine Commission (TLC). It provides detailed records of trips made by yellow and green taxis in New York City, along with Uber and other for-hire vehicle rides.

### Here is the original dataset used - https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page
**Data Attributes:**
- Pick-up and Drop-off Information: Dates, times, and precise locations.
- Trip Details: Distances travelled, duration, and rate types.
- Fare Information: Base fare, taxes, tolls, surcharges, and total fare amounts.
- Passenger Count: The number of passengers reported by drivers.
- Payment Details: Payment methods (e.g., cash, card).
## Yellow and Green Taxi Trip Records
The dataset includes comprehensive trip records for yellow and green taxis, capturing:
- Pick-up and drop-off timestamps and geographic locations (latitude/longitude or location IDs).
- Fare breakdowns, including surcharges and additional fees.
- Trip distances and the reported passenger count by drivers.
- Relevance to the Project
- This dataset provides the necessary information to:
- Analyze taxi trip patterns, including peak hours and high-demand areas.
- Compare ride trends across different taxi types and payment methods.
- Build scalable ETL workflows for data ingestion, transformation, and analysis in a real-world context.
## Data Model
![Data Model Image](data_model.jpeg)
## Scripts for project
1. [Extract Python File](mage-files/extract.py)
2. [Load Python File](mage-files/load.py)
3. [Transform Python File](mage-files/transform.py)

## Challenges and Learnings
### Challenges
- Handling large datasets and ensuring efficient processing.
- Optimizing SQL queries for performance in BigQuery.
- Setting up and managing GCP services for a seamless pipeline.
### Key Learnings
- Cloud-native tools like BigQuery and Cloud Storage simplify handling big data.
- Mage.ai offers an intuitive and efficient way to orchestrate data pipelines.
- Scalability and automation are key to modern data engineering solutions.

##Future Work
This project can be extended in the following ways:

1. Real-Time Data Streaming: Integrate Google Pub/Sub for real-time data ingestion.
2. Predictive Analytics: Build machine learning models to predict ride demand.
3. Advanced Visualizations: Use tools like Tableau or Power BI for enhanced insights.
4. Additional Data Sources: Include weather or traffic data for deeper analysis.
