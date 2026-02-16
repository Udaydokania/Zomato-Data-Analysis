# Zomato Data Analysis Project 🍴

## 📌 Project Overview
This project is an Exploratory Data Analysis (EDA) focused on uncovering consumer behavior and restaurant trends within the Zomato ecosystem. [cite_start]By cleaning and visualizing a dataset of 148 restaurants[cite: 22], the analysis identifies key drivers for customer satisfaction, popular dining categories, and spending patterns for couples.

## 🛠 Tech Stack
- [cite_start]**Language:** Python [cite: 4]
- [cite_start]**Libraries:** Pandas, NumPy, Matplotlib, Seaborn [cite: 5, 6, 7, 8]
- [cite_start]**Environment:** Jupyter Notebook [cite: 3]

## 🧹 Data Cleaning & Preprocessing
A critical step in this analysis was the transformation of the `rate` column. Originally stored as a string (e.g., "4.1/5"), a custom `handleRate` function was implemented to:
- [cite_start]Split the string to isolate the numerator[cite: 25].
- [cite_start]Convert the value into a **float64** data type for numerical computation[cite: 26, 67].
- [cite_start]Ensure all null values were handled to maintain a clean dataset of 148 non-null entries[cite: 49, 66].

## 📊 Key Business Insights
Based on the visualizations and data aggregation, the following conclusions were reached:
- [cite_start]**Dominant Category:** The majority of restaurants fall under the **Dining** category, which also received the maximum number of customer votes[cite: 207, 209].
- [cite_start]**Rating Distribution:** Most restaurants in the dataset maintain a rating between **3.5 and 4.0**[cite: 211].
- [cite_start]**Spending Patterns:** The most common spending amount for couples is approximately **300 rupees** per order[cite: 213].
- [cite_start]**Service Preferences:** Dining restaurants primarily handle **offline orders**, whereas cafes are the preferred choice for **online ordering**[cite: 217, 218].

## 📂 Repository Structure
- [cite_start]`Zomato data.csv`: Raw restaurant dataset[cite: 10].
- [cite_start]`Zomato_Analysis.ipynb`: Full Python code for cleaning and visualization[cite: 3].
- [cite_start]`Zomato.pdf`: Exported project report for easy viewing.
- `requirements.txt`: Project dependencies.
