# P Abhilash Goud — Customer Churn Prediction

## Project
AI Predicts What Happens Next: Customer Churn Prediction.

## Objective
Identify customers who may be at risk of churn using historical transaction behaviour, RFM features and Logistic Regression.

## Method
- Historical cutoff: 14-May-2026
- Features: Recency, Frequency, Monetary and Avg_Order_Value
- Model: Logistic Regression
- Churn: no purchase during the future observation period
- Low Risk: <40%
- Medium Risk: 40% to <70%
- High Risk: >=70%

## Reported Results
- Accuracy: 67.24%
- Precision: 68.75%
- Recall: 70.97%

## Files
- `P_Abhilash_Goud_Customer_Churn_Prediction.ipynb`
- `requirements.txt`
- `P_Abhilash_Goud_ProjectReport.docx`
- `README.md`
- `P_Abhilash_Goud_Customer_Churn_Output.xlsx`
- `data/cleaned_customer_transactions.csv`

## Run
```bash
pip install -r requirements.txt
jupyter notebook P_Abhilash_Goud_Customer_Churn_Prediction.ipynb
```
