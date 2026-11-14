# Electricity-Demand-Forecasting-using-Apache-Spark-and-Map-Reduce
📌 Project Overview

This project focuses on analyzing large-scale household electricity consumption data and forecasting electricity demand using Big Data technologies and Machine Learning.

Using Apache Spark, the project processes, cleans, transforms, and analyzes millions of electricity consumption records. A Random Forest Regression model is implemented using Spark MLlib to predict electricity demand based on historical consumption patterns and other relevant features.

An interactive Gradio Dashboard is developed to visualize electricity consumption trends, forecast results, model performance, and feature importance.

🎯 Objectives

Process large-scale electricity consumption datasets using Apache Spark.

Perform data cleaning and preprocessing.

Implement MapReduce operations using Spark RDDs.

Analyze electricity consumption patterns using Spark SQL.

Perform feature engineering on time-series data.

Predict electricity demand using Random Forest Regression.

Evaluate model performance using RMSE, MAE, and R².

Visualize insights through an interactive Gradio dashboard.

📊 Dataset

Individual Household Electric Power Consumption Dataset

Source: UCI Machine Learning Repository

The dataset contains approximately 2.07 million measurements collected over almost four years at one-minute intervals.

Dataset Features

Date and Time

Global Active Power

Global Reactive Power

Voltage

Global Intensity

Sub Metering 1

Sub Metering 2

Sub Metering 3

The target variable for prediction is demand_kw, derived from Global Active Power.

🛠️ Technologies Used

Technology

Purpose

Python

Programming language

Apache Spark (PySpark)

Distributed data processing

Spark RDD

MapReduce operations

Spark SQL

Data analysis and aggregation

Spark MLlib

Machine Learning

Random Forest Regression

Electricity demand prediction

Pandas & NumPy

Data manipulation

Matplotlib

Data visualization

Gradio

Interactive dashboard

Google Colab

Development environment

⚙️ Project Workflow

Data Acquisition: Download the electricity consumption dataset from UCI.

Data Processing: Load the dataset into Apache Spark.

Data Cleaning: Handle missing values, convert data types, and prepare timestamps.

MapReduce: Aggregate electricity readings using Spark RDD transformations.

Feature Engineering: Extract time-based features and previous electricity demand.

Spark SQL Analysis: Analyze hourly and monthly electricity consumption patterns.

Machine Learning: Train a Random Forest Regression model using Spark MLlib.

Model Evaluation: Evaluate predictions using RMSE, MAE, and R².

Visualization: Generate demand trends, prediction comparisons, and feature importance plots.

Dashboard: Present analytical insights through Gradio.

🤖 Machine Learning Model

Algorithm: Random Forest Regression (Apache Spark MLlib)

Input Features

Year, Month, Day

Hour and Minute

Day of Week

Weekend Indicator

Previous Electricity Demand

Voltage

Reactive Power

Global Intensity

Sub-metering values

Target Variable

demand_kw

Evaluation Metrics

Root Mean Squared Error (RMSE)

Mean Absolute Error (MAE)

R² Score

The dataset is split chronologically into training and testing sets to preserve the time-series order.

📈 Gradio Dashboard

The project includes an interactive dashboard featuring:

Dataset and model summary cards

Hourly electricity demand trends

Monthly electricity consumption analysis

Actual vs Predicted demand visualization

Model evaluation metrics

Random Forest feature importance

📁 Project Structure

Big-Data-Electricity-Forecasting/
│
├── B1_B1_01,14_BDA_PROJECT.ipynb
│
└── README.md

🚀 How to Run the Project

Option 1: Google Colab (Recommended)

Download or clone this repository.

Open Google Colab.

Upload the .ipynb notebook.

Run the notebook cells sequentially.

Allow the notebook to install the required dependencies.

The dataset will be downloaded automatically from UCI.

Execute the analysis, model training, and Gradio dashboard cells.

Open the generated Gradio interface to explore the results.

Option 2: Install Dependencies

pip install pyspark gradio pandas numpy matplotlib requests

The notebook includes Java detection and setup for running Spark in Google Colab.

💾 Data Storage

The notebook uses local storage in Google Colab for its runnable implementation.

It also demonstrates how the raw dataset can be stored and accessed through HDFS in a real Hadoop cluster.

Processed data is saved in Parquet format for efficient analytical processing.

🔮 Future Scope

Integrate real-time electricity consumption data.

Deploy the forecasting model as a cloud-based application.

Implement advanced forecasting algorithms.

Integrate renewable energy consumption analysis.

Extend the system to support multiple households and smart grids.

Explore large-scale deployment using Hadoop and distributed Spark clusters.

👥 Project Information

Project: Big Data Analytics and Electricity Demand Forecasting using Apache Spark

Course: Big Data Analytics

Institution: Ramdeobaba University

Project Type: Academic / Big Data Analytics and Machine Learning

⭐ If you find this project interesting, consider giving this repository a star!
