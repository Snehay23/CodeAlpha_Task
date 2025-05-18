# CodeAlpha_Task
Task-1: Credit risk prediction using Decision Tree and Random Forest (ML Project)

# 💳 Credit Scoring Model (Machine Learning Project)

This project is a simple and beginner-friendly machine learning model to **predict credit risk** — whether a person is a "Good" or "Bad" credit risk — based on their financial data. It uses two classification algorithms: **Decision Tree** and **Random Forest**.

## 📌 Project Objective

To build a model that helps financial institutions or banks **decide whether to approve a loan**, using historical customer data.

## 🧰 Tools and Technologies Used

- Python
- Google Colab
- Pandas & NumPy
- Scikit-learn (sklearn)
- Decision Tree Classifier
- Random Forest Classifier
- Matplotlib / Seaborn (optional for visualization)

## 📁 Dataset Information

- The dataset used is **German Credit Data**
- Features include:
  - Age, Job, Housing, Savings account, Checking account, Credit amount, Duration, Purpose, etc.
- Target column: `Risk` (Good or Bad)

## 🧪 Model Building Steps

1. **Import libraries**
2. **Load and inspect data**
3. **Preprocess data**:
   - Encode categorical features
   - Scale numerical features
4. **Split data into training & testing sets**
5. **Train using Decision Tree & Random Forest**
6. **Evaluate model using accuracy, confusion matrix, and classification report**

## 📊 Results

| Model           | Accuracy |
|----------------|----------|
| Decision Tree  | 62%      |
| Random Forest  | 71%      |

👉 Random Forest performed better in terms of precision, recall, and f1-score.

## 📚 What I Learned

- Handling and preprocessing real-world datasets
- Applying classification algorithms in scikit-learn
- Evaluating models using accuracy, confusion matrix, and classification report
- Improving performance using ensemble methods

## ✅ Future Improvements

- Add more models (e.g., Logistic Regression, XGBoost)
- Hyperparameter tuning for better accuracy
- Visualization of decision boundaries

## 📎 How to Run

1. Clone the repository or open the notebook in [Google Colab](https://colab.research.google.com/)
2. Upload the dataset file (CSV)
3. Run all code cells step by step

## 💡 Credits

- Dataset: [German Credit Data](https://www.kaggle.com/datasets/laotse/german-credit)


