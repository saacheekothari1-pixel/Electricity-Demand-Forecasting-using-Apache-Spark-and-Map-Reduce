
# Electricity Demand Forecasting using Apache Spark
#### By Aarya Khobaragade and Saachee Kothari

## Project Overview

This project analyzes large-scale household electricity consumption data and forecasts electricity demand using Big Data technologies and Machine Learning.

Using Apache Spark, the project processes, cleans, transforms, and analyzes millions of electricity consumption records. The project implements a Random Forest Regression model using Spark MLlib to predict electricity demand.

An interactive Gradio Dashboard is developed to visualize electricity consumption trends, prediction results, and model performance.

## 🎯 Objectives

- Process large-scale electricity consumption datasets using Apache Spark.
- Perform data cleaning and preprocessing.
- Implement MapReduce operations using Spark RDDs.
- Analyze electricity consumption using Spark SQL.
- Perform feature engineering.
- Predict electricity demand using Random Forest Regression.
- Evaluate model performance.
- Visualize insights through a Gradio dashboard.

## 📊 Dataset

**Individual Household Electric Power Consumption Dataset**

Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/235/individual+household+electric+power+consumption)

- Approximately 2.07 million records.
- One-minute interval measurements.
- Nearly four years of electricity consumption data.

### Dataset Features

- Date
- Time
- Global Active Power
- Global Reactive Power
- Voltage
- Global Intensity
- Sub Metering 1
- Sub Metering 2
- Sub Metering 3

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming |
| Apache Spark | Distributed Processing |
| PySpark | Spark Integration |
| Spark RDD | MapReduce |
| Spark SQL | Data Analysis |
| Spark MLlib | Machine Learning |
| Random Forest | Demand Prediction |
| Pandas & NumPy | Data Processing |
| Matplotlib | Visualization |
| Gradio | Interactive Dashboard |
| Google Colab | Development Environment |

## ⚙️ Project Workflow

1. Data Acquisition
2. Data Loading using Apache Spark
3. Data Cleaning and Preprocessing
4. MapReduce Operations using Spark RDD
5. Feature Engineering
6. Data Analysis using Spark SQL
7. Machine Learning using Spark MLlib
8. Electricity Demand Forecasting
9. Model Evaluation
10. Interactive Gradio Dashboard

## 🤖 Machine Learning Model

**Algorithm:** Random Forest Regression

### Input Features

- Year
- Month
- Day
- Hour
- Day of Week
- Previous Electricity Demand
- Voltage
- Global Intensity
- Reactive Power
- Sub Metering Values

### Evaluation Metrics

- RMSE (Root Mean Squared Error)
- MAE (Mean Absolute Error)
- R² Score

## 📈 Gradio Dashboard

The interactive dashboard provides:

- Electricity consumption analysis
- Hourly demand trends
- Monthly consumption patterns
- Actual vs Predicted demand
- Model performance metrics
- Feature importance visualization

## 📁 Project Structure

```text
Big-Data-Electricity-Forecasting/
│
├── B1_B1_01,14_BDA_PROJECT.ipynb
│
└── README.md
```

## 🚀 How to Run

### Google Colab

1. Clone or download this repository.
2. Open Google Colab.
3. Upload the `.ipynb` notebook.
4. Run all cells sequentially.
5. Install the required dependencies when prompted.
6. Load and process the dataset.
7. Train the machine learning model.
8. Launch the Gradio dashboard.

### Install Dependencies

```bash
pip install pyspark gradio pandas numpy matplotlib requests
```

## 🔮 Future Scope

- Real-time electricity consumption monitoring.
- Integration with smart electricity meters.
- Cloud-based deployment.
- Advanced time-series forecasting models.
- Renewable energy consumption analysis.
- Large-scale distributed processing using Hadoop and Spark.

## 👥 Project Information

**Project Title:** Big Data Analytics and Electricity Demand Forecasting using Apache Spark

**Course:** Big Data Analytics

**Institution:** Ramdeobaba University

**Project Type:** Academic Project

---

⭐ If you find this project interesting, consider giving this repository a star!
