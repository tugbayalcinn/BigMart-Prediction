# BigMart Sales Prediction

This project uses machine learning to predict the sales of various items in different BigMart outlets.

## Dataset
The dataset contains information about items and outlets, including:
- Item type
- Item price (MRP)
- Outlet size and type
- Item fat content
- And more...

## Models Used
Two models were trained and evaluated in this notebook:
1. **Linear Regression**
2. **Random Forest Regressor** (final model used for submission)

The Random Forest model performed better, so it was used to generate the final predictions (`submission.csv`).

## Files
- `submission.csv`: Contains predicted sales for the test set using the Random Forest model.
- (Optional) `bigmart_models.ipynb`: Jupyter Notebook with full code, data processing, training, and evaluation of both models.

## How to Run
You can run the notebook in Jupyter or Google Colab with the provided dataset files.
