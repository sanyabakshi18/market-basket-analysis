# Market Basket Analysis Project using Apriori Algorithm

## Overview
This project performs Market Basket Analysis on retail transaction data to discover relationships between products that are frequently purchased together. The analysis was implemented using Python in Google Colab with the Apriori Algorithm and association rule mining techniques.

The project helps in understanding customer purchasing behavior by generating frequent itemsets and analyzing relationships using support, confidence, and lift metrics.

---

## Features
- Data preprocessing and cleaning
- Transaction encoding for analysis
- Frequent itemset generation using Apriori Algorithm
- Association rule mining
- Calculation of:
  - Support
  - Confidence
  - Lift
- Data visualization using graphs and plots
- Interpretation of customer buying patterns

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- mlxtend
- Google Colab

---

## Dataset
The dataset for this project was sourced from Kaggle. It contains retail transactional data used for identifying frequent itemsets and analyzing customer purchasing behavior using association rule mining.

---

## Working Process
1. Imported and cleaned the dataset
2. Converted transactional data into basket format
3. Applied Apriori Algorithm to generate frequent itemsets
4. Generated association rules using support, confidence, and lift
5. Visualized relationships and patterns using graphs

---

## Key Concepts

### Support
Measures how frequently an itemset appears in the dataset.

### Confidence
Measures how often items in Y appear in transactions containing X.

### Lift
Measures the strength of association between two items and indicates how strongly they are related.

---

## Output
The project generates:
- Frequent itemsets
- Association rules
- Scatter plots
- Bar graphs
- Insights into customer purchasing behavior

---

## Future Improvements
- Build an interactive dashboard
- Deploy using Streamlit
- Compare Apriori with FP-Growth Algorithm
- Add recommendation system features

---

## Author
Sanya Bakshi
