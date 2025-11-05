# 📈 YouTube View Prediction — Machine Learning Project

Predicting YouTube video view counts using metadata such as title, tags, publish time and video category 🎯  
Dataset used: YouTube Trending Statistics (Kaggle)

---

## ✅ Objective
Use machine learning to predict how many views a video will receive using:
- Metadata features (category, publish time, tags)
- Numerical stats (likes, dislikes, comment count)

---

## 🧠 Machine Learning Models

| Model | Overfitting Control | Feature Selection |
|------|--------------------|------------------|
| Linear Regression | ❌ | ❌ |
| Ridge Regression | ✅ | ❌ |
| Lasso Regression | ✅ | ✅ |

---

## 📊 Evaluation Metrics

- ✅ R² Score (higher is better)
- ✅ RMSE (lower is better)
- ✅ Visualizations:
  - Actual vs Predicted Views
  - Residual Plot
  - Coefficient Importance

Results stored in `data/model_results.csv`

---

## 📂 Project Structure

YOUTUBE-VIEW-PREDICTION/
│
├── data/
│ ├── USvideos.csv
│ ├── clean_youtube_data.csv
│ ├── model_results.csv
│ └── prediction_test_set.csv
│
├── models/
│ ├── linear_regression.pkl
│ ├── ridge_pipeline.pkl
│ └── lasso_pipeline.pkl
│
├── notebooks/
│ ├── 01_data_preprocessing.ipynb
│ └── 02_regression_model.ipynb
│
├── README.md
└── requirements.txt


## Future Improvements
- Add Random Forest for better accuracy
- Deploy using Streamlit



## Author
Monum Hashmi — AI & ML Student
GitHub: (https://github.com/monum-hashmi)

