# Fashion Retail Data Analysis & Expansion Strategy

A Python-based data analytics project exploring fashion retail performance and identifying potential expansion opportunities through statistical analysis and machine learning.

## Project Overview

This project analyzes a global fashion retail dataset to uncover patterns in sales performance, product demand, store activity, and geographic markets.

The analysis combines exploratory data analysis, statistical methods, geographic analysis, and K-Means clustering to identify different store performance profiles and support data-driven business and expansion decisions.

## Key Analysis

- Data cleaning and preprocessing
- Exploratory data analysis
- Sales and product performance analysis
- Store and geographic performance comparison
- Statistical and regression analysis
- K-Means store segmentation
- Elbow Method and Silhouette Score for cluster selection
- Expansion strategy analysis

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Statsmodels
- Jupyter Notebook

## Key Findings

The clustering analysis identified **two distinct store performance profiles**, with **k = 2** achieving the highest Silhouette Score of **0.614**.

A smaller group of high-value stores generates substantially higher total revenue and average transaction revenue compared with the standard store profile. Discount levels remain similar across both groups, suggesting that discount intensity is not a major factor differentiating the clusters.

The regression analysis identified statistically significant associations between quantity, discount, and transaction revenue. However, the model has relatively low explanatory power, indicating that additional factors are likely to contribute substantially to revenue variation.

Overall, the analysis demonstrates how retail data can be used to compare store performance, identify different commercial profiles, and support strategic expansion decisions.

## Dataset

This project uses the **Global Fashion Retail Sales** dataset available on Kaggle.

The dataset contains synthetic transactional data representing two years of sales activity for a multinational fashion retailer.

Due to GitHub file size limitations, the complete dataset is not stored directly in this repository.

To reproduce the analysis, download the dataset from Kaggle and place the CSV files inside the `data/` directory.

Additional dataset information and download instructions are available in [`data/README.md`](./data/README.md).

**License:** CC BY 4.0

## Project Structure

```text
Fashion-Retail-Data-Analysis/
│
├── fashion_retail_analysis.ipynb
├── README.md
└── data/
    └── README.md
```

## How to Run

1. Clone or download this repository.
2. Download the dataset using the instructions in `data/README.md`.
3. Place the required CSV files inside the `data/` directory:
   - `transactions.csv`
   - `stores.csv`
   - `products.csv`
4. Open `fashion_retail_analysis.ipynb`.
5. Install the required Python libraries if necessary.
6. Run the notebook cells sequentially.

## Purpose

This project was developed as part of my data analytics portfolio and demonstrates the application of Python, statistical analysis, data visualization, and machine learning-based segmentation to a real-world retail business scenario.
