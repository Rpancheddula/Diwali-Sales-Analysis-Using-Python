# Diwali Sales Analysis 🪔📊

## Data Source 💾

The analysis uses the `Diwali Sales Data.csv` file.
The dataset (`Diwali Sales Data.csv`) is included in this repository.

## Overview 📝

This project performs an Exploratory Data Analysis (EDA) on Diwali sales data. The goal is to uncover trends and insights regarding customer demographics, popular product categories, and regional sales performance during the Diwali season. This information can be valuable for understanding customer behavior and informing future marketing or sales strategies.

## Data Source 💾

The analysis uses the `Diwali Sales Data.csv` file. The dataset is included in this repository.

The dataset contains transactional information including user demographics (User ID, Name, Gender, Age Group, Marital Status, State, Zone, Occupation) and order details (Product ID, Product Category, Orders, Amount).

## Tools & Libraries Used 🛠️

* **Language:** Python 3
* **Libraries:**
    * pandas: For data manipulation and analysis.
    * numpy: For numerical operations.
    * matplotlib: For basic plotting.
    * seaborn: For enhanced statistical visualizations.
* **Environment:** Jupyter Notebook

## Installation & Setup ⚙️

1.  **Clone the repository:**
    ```bash
    git clone : https://github.com/Rpancheddula/Diwali-Sales-Analysis-Using-Python.git
    cd Diwali-Sales-Analysis-Using-Python
    ```
2.  **Install required libraries:**
    ```bash
    pip install -r requirements.txt
    ```

## Analysis Steps 📈

1.  **Data Loading:** Imported the necessary libraries and loaded the dataset using pandas.
2.  **Data Inspection:** Examined the data structure, shape, column types, and initial rows (`head()`, `tail()`, `info()`, `shape()`).
3.  **Data Cleaning:**
    * Identified and dropped irrelevant columns (`Status`, `unnamed1`).
    * Checked for and handled null values (dropped rows with null 'Amount').
    * Verified cleaning steps.
4.  **Exploratory Data Analysis (EDA):**
    * Analyzed sales distribution based on **Gender**.
    * Analyzed sales distribution based on **Age Group** (combined with Gender).
    * Analyzed the total number of **Orders** and total **Amount** spent by the top 10 **States**.
    * Analyzed the distribution based on **Marital Status**.
    * Analyzed sales distribution based on **Occupation**.
    * Analyzed sales distribution based on **Product Category**.
    * Visualized findings using count plots and bar charts from seaborn and matplotlib.
5.  **Conclusion:** Summarized the key insights derived from the analysis.

## Key Findings & Insights 💡

* **Gender:** Females represent a significantly higher number of buyers and have a higher total purchasing amount compared to males.
* **Age Group:** The age group 26-35 shows the highest number of buyers and the largest spending amount, particularly among females.
* **State:** Uttar Pradesh, Maharashtra, and Karnataka are the top 3 states in terms of both the number of orders and the total sales amount.
* **Marital Status:** Unmarried individuals contribute more to the total sales amount compared to married individuals.
* **Occupation:** Customers from IT, Healthcare, and Aviation sectors are the top 3 contributors to sales amount.
* **Product Category:** Food, Clothing & Apparel, and Electronics & Gadgets are the most popular product categories by sales amount.

## Conclusion 🎯

The analysis indicates that the primary customer segment driving Diwali sales consists of **married women aged 26-35, residing in Uttar Pradesh, Maharashtra, or Karnataka, and working in the IT, Healthcare, or Aviation sectors.** They primarily purchase products related to **Food, Clothing & Apparel, and Electronics & Gadgets.**

To potentially increase overall sales, marketing efforts could focus more strategically on less represented demographics or product categories such as Office, Veterinary supplies, Books, and Household items.

## How to Use 🚀

1.  Ensure you have Jupyter Notebook or Jupyter Lab installed.
2.  Navigate to the project directory in your terminal.
3.  Launch Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
4.  Open the `Diwali Sales Analysis.ipynb` file and run the cells sequentially.
