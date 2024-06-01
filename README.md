# Customer Segmentation

This project involves customer segmentation analysis using a dataset of mall customers. The goal is to categorize customers into different segments based on their characteristics and purchasing behaviors.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)

## Introduction
Customer segmentation is a crucial part of marketing strategies, allowing businesses to target specific groups of customers effectively. This project utilizes data analysis and machine learning techniques to segment customers into meaningful categories.

## Dataset
The dataset used in this project is `Mall_Customers.csv`, which includes the following features:
- `CustomerID`: Unique identifier for each customer
- `Gender`: Gender of the customer
- `Age`: Age of the customer
- `Annual Income (k$)`: Annual income of the customer in thousands of dollars
- `Spending Score (1-100)`: Score assigned by the mall based on customer behavior and spending nature

## Installation
To run this project, you need to have Python installed along with several libraries. You can install the required libraries using the following command:
```bash
pip install -r requirements.txt
```

## Usage
1. Clone the repository:
```bash
git clone https://github.com/KumarranMahesh/Customer-Segmentation.git
```

2. Navigate to the project directory:
```bash
cd Customer-Segmentation
```

3. Ensure you have the dataset `Mall_Customers.csv` in the data directory.

4. Run the Jupyter notebook or Python script to execute the project.

## Features
- **Data Cleaning & Preprocessing**: Handling missing values, encoding categorical variables.
- **Data Visualization**: Visualizing distributions of features.
- **Clustering**: Implementing K-Means clustering to segment customers.
