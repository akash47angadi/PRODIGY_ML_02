# Customer Segmentation Using K-means Clustering

This repository contains a Python implementation of the K-means clustering algorithm to group customers of a retail store based on their purchase history. The goal is to segment customers into distinct groups to better understand their behavior and optimize marketing strategies.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Visualization](#visualization)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Customer segmentation is a crucial aspect of marketing strategy. By grouping customers based on their purchase history, businesses can tailor their marketing efforts to different customer segments, improving customer satisfaction and increasing sales.

This project uses the K-means clustering algorithm to segment customers based on their purchase history.

## Dataset

Dataset used: https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python. 
The data should be stored in a CSV file named `customer_purchase_history.csv`.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/customer-segmentation.git
    ```

2. Navigate to the project directory:
    ```sh
    cd customer-segmentation
    ```

3. Create a virtual environment and activate it (optional but recommended):
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

4. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Ensure you have the `customer_purchase_history.csv` file in the project directory.

2. Run the Python script to perform customer segmentation:
    ```sh
    python customer_segmentation.py
    ```

3. The script will output the clustered data and display visualizations of the customer segments.

## Visualization

The script includes visualization of the clusters using a pair plot. The visualizations help in understanding the distinct customer segments.


