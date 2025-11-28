# Global-Cancer-Incidence-Analysis
Exploratory Data Analysis (EDA) on Global Cancer Rates (2020) implementing fundamental algorithms (Bubble Sort, Insertion Sort, Linear Search) from scratch using Python, Pandas, and Matplotlib.

# 🌍 Global Cancer Incidence Analysis (2020)

A data analysis project exploring the global cancer incidence rates in 2020. This project was developed as a final assignment for the **Algorithm and Programming (Alpro)** course at **Institut Teknologi Sumatera (ITERA)**.

The primary goal of this project is not only to analyze data but to demonstrate the practical application of fundamental computer science algorithms (Sorting and Searching) using Python.

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Pandas](https://img.shields.io/badge/Library-Pandas-150458)
![Status](https://img.shields.io/badge/Status-Completed-green)

## 📊 Project Overview

This program analyzes a dataset of Global Cancer Incidence to identify:
* The most prevalent types of cancer in 2020.
* The percentage contribution of each cancer type.
* Rankings of cancer cases from highest to lowest.

## 🛠️ Key Algorithms Implemented

Unlike standard data analysis that relies solely on built-in library functions, this project includes **manual implementations** of classic algorithms to demonstrate algorithmic logic:

1.  **Bubble Sort:** Used to sort cancer cases in ascending order.
2.  **Insertion Sort:** Implemented to organize case data efficiently.
3.  **Quick Sort:** Utilized via the Pandas library for rapid dataframe sorting.
4.  **Linear Search:** Used to find specific cancer types (e.g., "Lung Cancer") within the dataset.

## 📈 Visualizations

The project utilizes `Matplotlib` to visualize the findings:
* **Bar Plot:** To compare the total new cases for different cancer types.
* **Pie Chart:** To show the percentage distribution of the top 5 cancer types.
* **Scatter Plot:** To observe the spread of data points regarding new cases.

## 🧰 Tech Stack

* **Language:** Python
* **Libraries:**
    * `Pandas` (Data Manipulation)
    * `NumPy` (Numerical Operations)
    * `Matplotlib` (Data Visualization)
* **Environment:** Jupyter Notebook / Google Colab

## 📂 File Structure
├── alpro_dataset_cancer.csv # The raw dataset ├── Global-Cancer-Incidence-Analysis.ipynb # Main Jupyter Notebook source code ├── README.md # Project Documentation

## 🔍 Key Insights

Based on the analysis of the 2020 dataset:
* **Highest Incidence:** Breast Cancer (12.5% of all cases).
* **Lowest Incidence (in dataset):** Vaginal Cancer (0.1%).
* **Top 5 Cancers:** Breast, Lung, Colorectal, Prostate, and Stomach cancer.

## 🚀 How to Run

1.  Clone this repository:
    ```bash
    git clone [https://github.com/your-username/Global-Cancer-Incidence-Analysis.git](https://github.com/Kaisarkai/Global-Cancer-Incidence-Analysis.git)
    ```
2.  Install the required libraries:
    ```bash
    pip install pandas numpy matplotlib
    ```
3.  Open the `.ipynb` file in Jupyter Notebook or Google Colab and run all cells.

## 👥 Author
**Muhammad Kaisar Firdaus** - *Data Science Student, ITERA*

---
*This project is for educational purposes to demonstrate the application of algorithms in data science.*
