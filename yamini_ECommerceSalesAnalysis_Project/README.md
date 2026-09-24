# E-Commerce Product Sales & Demand Analysis

## Project Overview
This project analyzes an e-commerce product dataset to understand sales patterns, category performance, product ratings, pricing, discounts, and demand levels. It also demonstrates a Random Forest classification model for predicting product demand.

## Dataset
Dataset file: `ecommerce_dataset.csv`

The dataset contains 300 synthetic product records. It is created for academic/project demonstration and should not be treated as real customer or company data.

### Main Columns
- `Product_ID` - Unique product identifier
- `Category` - Product category
- `Product_Name` - Product name
- `Brand` - Brand name
- `Price_INR` - Product price in INR
- `Rating` - Product rating
- `Reviews` - Number of reviews
- `Units_Sold` - Number of units sold
- `Discount_Percent` - Discount percentage
- `Demand` - Low, Medium, or High demand
- `In_Stock` - Product stock status

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Structure
```text
ECommerceSalesAnalysis/
│
├── Yamini_ECommerceSalesAnalysis.ipynb
├── ecommerce_dataset.csv
├── requirements.txt
├── README.md
└── Yamini_ECommerceSalesAnalysisReport.docx
```

## Setup Instructions

### 1. Install Python
Install Python 3.10 or later.

### 2. Install dependencies
Open a terminal in the project folder and run:

```bash
pip install -r requirements.txt
```

### 3. Start Jupyter Notebook
```bash
jupyter notebook
```

Open:
`Yamini_ECommerceSalesAnalysis.ipynb`

### 4. Run the notebook
Run the cells from top to bottom.

## Machine Learning
The project uses a Random Forest Classifier to classify product demand into:
- Low
- Medium
- High

The model is intended as an educational demonstration.

## Key Outputs
The notebook generates:
1. Dataset overview
2. Missing-value and duplicate checks
3. Category-wise sales analysis
4. Average rating analysis
5. Price vs sales visualization
6. Correlation heatmap
7. Demand distribution
8. Random Forest demand classification
9. Classification report
10. Confusion matrix
11. Sample demand prediction

## Important Note
The dataset is synthetic and was generated for an academic e-commerce analytics project. Results should not be interpreted as real-world market findings.
