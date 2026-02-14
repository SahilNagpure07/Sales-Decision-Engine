# Sales-Decision-Engine

This project analyzes sales performance using CRM data to build a **Win Rate Driver Model** and generate **risk-adjusted revenue forecasts**.

## Approach (ML Model)

**Win Rate Driver Model (Logistic Regression)**  
- **Target**: `outcome` (won/lost)  
- **Features**: `industry`, `region`, `product_type`, `lead_source`, `deal_amount`, `total_days`  
- **Model**: Logistic Regression
- **Purpose**: Identify which factors increase or decrease win probability

## How to Run the Project

### 1. Install Dependencies
```bash
pip install pandas numpy scikit-learn 
```

### 2. Run the Notebook
```bash
jupyter notebook
```
