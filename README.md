# 🚨 Exploratory Data Analysis of 911 Calls Data using Python

## 📌 Project Overview

This project focuses on **Data Processing and Exploratory Data Analysis (EDA)** of a 911 emergency calls dataset obtained from Kaggle.

The main objective is to clean and process the raw data, create useful features from existing columns, and explore the dataset using Python data analysis and visualization libraries.

## 📊 Dataset

The dataset contains information about 911 emergency calls, including the **title, timestamp, and location** of each call.

The `title` column contains the category and specific reason for each call. For example:

```text
EMS: BACK PAINS/INJURY
Fire: VEHICLE FIRE
Traffic: VEHICLE ACCIDENT
```

The text before the colon represents the **call category**.

## 🛠️ Data Processing

The following data processing steps were performed:

### Extracting the Reason

A new `Reason` column was created by extracting the text before the colon in the `title` column.

For example:

```text
EMS: BACK PAINS/INJURY → EMS
Fire: VEHICLE FIRE → Fire
Traffic: VEHICLE ACCIDENT → Traffic
```

### Processing Timestamps

The timestamp column was initially stored as a string.

It was converted into a **datetime format** to make it easier to work with the time-related information.

Additional features were extracted from the timestamp, including:

* Year
* Month
* Day of Week

## 📈 Exploratory Data Analysis

EDA was performed to understand the structure and distribution of the dataset.

The analysis includes:

* Examining the different **reasons for emergency calls**
* Analyzing the distribution of calls across different categories
* Exploring call patterns based on **year, month, and day of the week**
* Creating visualizations to understand the processed data

## 📊 Data Visualization

The processed data was visualized using:

* Matplotlib
* Seaborn

Different plots were created to explore the distribution of emergency calls and the newly created features.

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## 🎯 Project Focus

This project primarily focuses on:

* Data Processing
* Feature Extraction
* Datetime Processing
* Exploratory Data Analysis
* Data Visualization
