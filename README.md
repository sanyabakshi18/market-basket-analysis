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

## Understanding the Metrics

### Support
Support shows how frequently an itemset appears in the dataset.

Example:
If Bread and Butter appear together in 20 out of 100 transactions,
Support = 20/100 = 0.20

### Confidence
Confidence measures how often item Y is purchased when item X is purchased.

Example:
If customers buying Bread also buy Butter 70% of the time,
Confidence = 0.70

### Lift
Lift measures how strong the relationship is between two items.

- Lift > 1 : Positive association
- Lift = 1 : No association
- Lift < 1 : Negative association

  ---

## Output
The project generates:
- Frequent itemsets
- Association rules
- Scatter plots
- Bar graphs
- Insights into customer purchasing behavior

---
## Graph Interpretation

The generated graphs help visualize relationships between products and association rules.

- Scatter plots were used to compare support and confidence values.
- Bar graphs were used to display frequent itemsets.
- Higher lift values indicate stronger product associations.
- The visualizations help identify products commonly purchased together.

---
## Future Improvements
- Build an interactive dashboard
- Deploy using Streamlit
- Compare Apriori with FP-Growth Algorithm
- Add recommendation system features

---

## Author
Sanya Bakshi
