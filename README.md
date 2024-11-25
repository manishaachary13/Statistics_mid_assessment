# Customer Purchase Behavior Analysis

This project involves analyzing customer purchasing behavior using descriptive statistics, probability distributions, customer segmentation, and insights to enhance marketing strategies and decision-making. The dataset used includes various customer demographic details and their spending habits, and the analysis focuses on understanding key patterns and factors influencing purchasing behavior.

## Project Overview

The goal of this project is to perform a comprehensive analysis of customer behavior data from a marketing campaign to help optimize marketing efforts and improve offer acceptance rates. Key areas of focus include:

- **Data cleaning and preprocessing**
- **Descriptive statistics**
- **Probability distributions**
- **Customer segmentation**
- **Key insights and actionable recommendations**

## Dataset

The dataset contains the following columns:

- **Response**: Whether the customer accepted the offer in the last campaign (1 = accepted, 0 = not accepted)
- **ID**: Unique identifier for each customer
- **Year_Birth**: Age of the customer
- **Complain**: Whether the customer complained in the last 2 years (1 = yes, 0 = no)
- **Dt_Customer**: Date when the customer enrolled with the company
- **Education**: Level of education of the customer
- **Marital**: Marital status of the customer
- **Kidhome**: Number of children under 18 in the customer's household
- **Teenhome**: Number of teenagers in the customer's household
- **Income**: Yearly income of the customer
- **MntFishProducts**: Spending on fish products in the last 2 years
- **MntMeatProducts**: Spending on meat products in the last 2 years
- **MntFruits**: Spending on fruits products in the last 2 years
- **MntSweetProducts**: Spending on sweet products in the last 2 years
- **MntWines**: Spending on wine products in the last 2 years
- **MntGoldProds**: Spending on gold products in the last 2 years
- **NumDealsPurchases**: Number of purchases made with a discount
- **NumCatalogPurchases**: Number of purchases made through a catalog
- **NumStorePurchases**: Number of purchases made directly in stores
- **NumWebPurchases**: Number of purchases made through the company's website
- **NumWebVisitsMonth**: Number of visits to the company's website in the last month
- **Recency**: Number of days since the last purchase

## Project Structure

```
├── data/               # Contains the dataset file
├── notebooks/           # Jupyter Notebooks with detailed analysis and code
│   ├── data_cleaning.ipynb
│   ├── descriptive_stats.ipynb
│   ├── probability_distribution.ipynb
│   └── customer_segmentation.ipynb
├── src/                # Contains Python scripts for data processing
│   ├── data_preprocessing.py
│   └── analysis.py
└── README.md           # Project description and instructions
```

## Key Tasks

### Task 1: Data Cleaning and Preprocessing
- Cleaned and preprocessed the dataset by handling missing values, ensuring consistent data types, and correcting any inconsistencies.
- Performed data type conversion for columns like `Dt_Customer` and created new variables (e.g., `Customer_Tenure`).

### Task 2: Descriptive Statistics
- Calculated measures of central tendency (mean, median, mode) and measures of dispersion (variance, standard deviation) for key variables.
- Identified and handled outliers if necessary.

### Task 3: Probability Distributions
- Analyzed variables to determine suitable probability distributions (e.g., Binomial, Normal).
- Calculated probabilities and expected values for relevant variables based on identified distributions.

### Task 4: Insights and Customer Segmentation
- Explored relationships between customer demographics and spending behavior.
- Performed customer segmentation using clustering techniques (e.g., KMeans clustering) based on spending habits and other characteristics.

### Task 5: Conclusion and Recommendations
- Presented clear visualizations to summarize the insights.
- Provided actionable recommendations for the company to optimize marketing strategies based on customer behavior.

## Tools and Libraries Used

- **Python**: Main programming language used for analysis
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computations
- **Matplotlib & Seaborn**: Data visualization
- **Scikit-learn**: Machine learning (for clustering)
- **SciPy**: Statistical analysis and probability distribution calculations

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Customer-Purchase-Behavior-Analysis.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Customer-Purchase-Behavior-Analysis
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Open the Jupyter notebooks located in the `notebooks/` directory for detailed analysis and visualization.

## Future Work

- Further exploration of customer behavior using advanced segmentation techniques (e.g., hierarchical clustering).
- Integration of more advanced statistical models to predict customer behavior in future campaigns.
- Expansion of data sources to include additional customer attributes and external factors (e.g., seasonal influences on purchase behavior).

