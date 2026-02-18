# Zomato Restaurant Analysis: EDA, Sentiment & Clustering 🍴🤖

## 📌 Project Overview
An end-to-end data science project performing deep-dive analysis on Zomato restaurant data. The project evolved from initial Exploratory Data Analysis (EDA) into advanced Natural Language Processing (NLP) to perform customer sentiment analysis and restaurant clustering based on cuisines and costs.

## 🛠 Tech Stack
- **Language:** Python
- **Core Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **NLP & ML Libraries:** Scacy, NLTK, TextBlob, Scikit-learn (K-Means, PCA)
- **Visualization:** WordCloud, Plotly Express

## 🔬 Project Workflow & Updates

### 1. Data Preprocessing & Cleaning
- [cite_start]**Numerical Conversion:** Transformed the `rate` column (e.g., "4.1/5") into a float format for statistical analysis[cite: 24, 28].
- [cite_start]**Text Standardization:** Cleaned the `Cost` column by removing commas and converting to an integer type[cite: 397].

### 2. Exploratory Data Analysis (EDA)
- [cite_start]**Popularity Metrics:** Identified that **Dining** is the most frequent restaurant type and receives the highest volume of customer votes[cite: 207, 209].
- [cite_start]**Spending Insights:** Discovered that the majority of couples prefer restaurants with an approximate cost of **300 rupees**[cite: 213].

### 3. Sentiment Analysis (NLP Update)
- [cite_start]**Text Refinement:** Leveraged **Lemmatization** and stop-word removal to prepare raw customer reviews for analysis[cite: 869, 1085].
- [cite_start]**Polarity & Subjectivity:** Used `TextBlob` to classify reviews into **Positive (7,492)**, **Negative (1,869)**, and **Neutral (593)** sentiments [cite: 1188, 1224-1229].

### 4. Machine Learning & Clustering
- [cite_start]**Feature Engineering:** Used `MultiLabelBinarizer` to encode the `Cuisines` column for mathematical modeling[cite: 1287].
- [cite_start]**K-Means Clustering:** Applied the **Elbow Method** and **Silhouette Analysis** to group restaurants into 5 distinct clusters based on cost, rating, and cuisine[cite: 1542, 1569].
- [cite_start]**Dimensionality Reduction:** Utilized **PCA (Principal Component Analysis)** to visualize high-dimensional restaurant data in a 2D space[cite: 1695].

## 📊 Key Business Conclusions
1. [cite_start]**Cuisine Dominance:** North Indian, Chinese, and Fast Food are the most popular and highly-rated cuisines among enthusiasts[cite: 1899, 1900].
2. [cite_start]**Review Behavior:** Peak review activity occurs around **5:00 PM** and **10:00 PM**, correlating with major meal times[cite: 728, 835].
3. [cite_start]**Affordability:** While expensive restaurants feature keywords like "Barbecue" and "Suites," affordable ones are dominated by "Bakery," "Dhaba," and "Fast Food" [cite: 677, 687-699].

## 📂 Repository Structure
- `Zomato data.csv`: Original restaurant dataset.
- `Zomato_Analysis.ipynb`: EDA and initial cleaning code.
- `Zomato_NLP_Clustering.ipynb`: Advanced NLP, Sentiment, and ML logic.
- `Zomato_NLP_Report.pdf`: Comprehensive project report with visualizations.
