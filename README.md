# E-commerce Customer Statistics

This project analyzes customer behavior data with Python and Jupyter Notebook. It answers ten practical questions covering descriptive statistics, correlation, probability, z-scores, skewness, and confidence intervals.

## Analysis covered

- Customer age range
- Mean, median, and mode of monthly spending
- Variance and standard deviation of time spent on the site
- Interquartile range of monthly spending
- Correlation between purchases and time spent on the site
- Z-score calculation for a selected spending value
- Spending-distribution skewness
- Union probability using the addition rule
- A 95% confidence interval for average spending
- Conditional probability for cross-sell conversion

## Project structure

```text
ecommerce-customer-statistics/
|-- ecommerce_customer_statistics.ipynb
|-- data/
|   `-- README.md
|-- .gitignore
`-- README.md
```

The original dataset is intentionally excluded from version control. Place a local copy at `data/ecommerce_data.csv` before running the notebook.

## Run locally

1. Create a Python environment.
2. Install the required packages:

   ```bash
   pip install pandas numpy matplotlib jupyter
   ```

3. Add the dataset as `data/ecommerce_data.csv`.
4. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open `ecommerce_customer_statistics.ipynb` and run all cells.

## Main findings

- Customer ages span 47 years.
- Monthly spending has a mean of 238.23, a median of 200, and a mode of 240.
- Purchases and time spent on the site have a strong positive correlation of 0.9376.
- Monthly spending is right-skewed, with a skewness of 0.9581.
- The estimated 95% confidence interval for average monthly spending is 228.56 to 247.90.

## Privacy

This repository contains only the analysis and aggregate results. Customer-level source data and assignment documents are not included.
