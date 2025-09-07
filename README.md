# Customer Churn Prediction using Random Forest

This repository contains a Python project to predict customer churn for an energy company using a Random Forest classifier. The project includes data preprocessing, feature engineering, exploratory data analysis, model training, evaluation, and feature importance analysis.

## 📂 Project Structure

- `Customer_Data.csv` – Sample customer data including usage, signup date, region, and customer type.
- `Pricing_Data.csv` – Sample pricing data including variable price per kWh and fixed fees.
- `Churn_Indicator.csv` – Sample churn labels indicating whether a customer churned.
- `feature_engineering.py` – Python script to create new features and merge datasets for modeling.
- `Churn_RandomForest.ipynb` – Jupyter Notebook to train a Random Forest classifier, evaluate performance, and visualize feature importance.
- `README.md` – Project overview and instructions.

## 🚀 Getting Started

1. Clone the repository**
```bash
git clone https://github.com/yourusername/Churn_Prediction_RF.git
cd Churn_Prediction_RF
Install required packages

bash
Copy code
pip install pandas numpy scikit-learn matplotlib seaborn
Run feature engineering script

bash
Copy code
python feature_engineering.py
This will generate Feature_Engineered_Data.csv with all the new features ready for modeling.

Open and run the Jupyter Notebook

bash
Copy code
jupyter notebook Churn_RandomForest.ipynb
The notebook trains a Random Forest classifier to predict churn, evaluates the model using metrics, and visualizes feature importance.

📊 Model Evaluation
Metrics Used: Accuracy, Precision, Recall, F1-score

Why these metrics:

Accuracy: Overall correctness of predictions

Precision: How many predicted churned customers actually churned

Recall: How many actual churned customers were correctly predicted

F1-score: Balances precision and recall for an overall metric

Feature Importance: Visualizes which features contribute most to predicting churn.

📝 Notes
The datasets are sample datasets for demonstration purposes.

Feature engineering includes creating date-based features, average daily usage, monthly cost, and encoding categorical variables.

The Random Forest model can be tuned for better performance with more data or hyperparameter optimization.

📌 Author
Your Name

Your sg6165@srmist.edu.in / 


