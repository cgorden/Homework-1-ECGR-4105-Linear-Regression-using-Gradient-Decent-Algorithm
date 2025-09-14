# Linear Regression with Gradient Descent

This project implements linear regression using gradient descent from scratch (without using ML libraries) for a machine learning homework assignment.

## Requirements

- Google Colab (recommended) or Jupyter Notebook
- Python libraries: `numpy`, `pandas`, `matplotlib`
- Dataset: `D3.csv` file

## Setup and Execution

1. **Open Google Colab**
   - Go to [colab.research.google.com](https://colab.research.google.com)
   - Click "New notebook"

2. **Upload Your Dataset**
   - Upload `D3.csv` to your Google Drive
   - Note the file path (e.g., `/content/drive/MyDrive/D3.csv`)

3. **Run the Code**
   - Copy the entire code into a Colab cell
   - **IMPORTANT**: Update the file path in this line:
     ```python
     file_path = '/content/drive/MyDrive/D3.csv'  # Update this path!
     ```
   - Run the cell (Shift + Enter)
   - Authenticate Google Drive access when prompted

## What the Code Does

### Problem 1: Individual Variable Analysis
- Implements simple linear regression (y = θ₀ + θ₁x) for each explanatory variable (X1, X2, X3) separately
- Tests multiple learning rates (0.01, 0.05, 0.1)
- Generates:
  - Regression line plots for each variable
  - Cost evolution plots over iterations
  - Identifies best performing single variable

### Problem 2: Multiple Variable Analysis
- Implements multiple linear regression (y = θ₀ + θ₁X1 + θ₂X2 + θ₃X3)
- Tests different learning rates
- Generates:
  - Cost evolution plots
  - Model performance comparison
  - Predictions for new data points: (1,1,1), (2,0,4), (3,2,1)

## Expected Output

The code will generate:
- Multiple plots showing regression lines and cost evolution
- Model equations for each variable combination
- Performance metrics and comparisons
- Predictions for specified test points
- Comprehensive analysis summary

## Key Results

After running, you'll have all the information needed to answer:
1. Linear model equations for each variable
2. Best performing single variable (lowest cost)
3. Impact of different learning rates
4. Multiple regression model equation
5. Predictions for new data points
6. Comparative analysis between single vs. multiple variable models
