# 📱 Apple App Store Data Analysis & Content Rating Prediction (PySpark + ML)

This project performs large-scale data analysis on Apple App Store apps using **PySpark**, applies **machine learning models** to predict app content ratings, and provides an **interactive UI** for predictions.

It combines:
- Big Data processing (Spark)
- Exploratory Data Analysis (EDA)
- Machine Learning (KNN, Decision Tree, Random Forest)
- Visualization (Matplotlib, Seaborn)
- Interactive prediction UI (ipywidgets)

---

## 🚀 Features

- Data processing and cleaning using **PySpark**
- Missing value analysis & visualization
- Genre-wise and content rating analysis
- App size and pricing analysis (Free vs Paid)
- Top developers and most popular categories
- Machine Learning models:
  - KNN
  - Decision Tree
  - Random Forest
- Interactive UI to predict **Content Rating** of an app
- Visualization dashboards for insights

---

## 📊 Dataset

The dataset is too large to include in this repository.

You can download it from Kaggle:

👉 https://www.kaggle.com/datasets/gauthamp10/apple-appstore-apps

After downloading:
1. Extract the CSV file
2. Rename it to:appleAppData.csv

---
🧠 Machine Learning Models Used

K-Nearest Neighbors (KNN)
Decision Tree Classifier
Random Forest Classifier
The models are trained to predict:

📌 Content Rating (4+, 9+, 12+, 17+, Not yet rated)

----

🖥️ Interactive UI

The project includes a simple UI using ipywidgets that allows users to enter:
App Size (Bytes)
Price
Average User Rating
Current Version Score
Number of Reviews
Size in MB
…and get a predicted content rating instantly.

----
📈 Sample Visualizations

Missing values percentage per column
Distribution of content ratings
Top app genres
Free vs Paid app size comparison
Top categories in the App Store
Highest-rated genres

🏆 Key Learnings

Hands-on experience with Big Data using PySpark
Real-world data cleaning challenges
Feature engineering for ML models
Building ML pipelines
Creating interactive ML applications
----

📌 Future Improvements

Deploy as a web app using Flask or Streamlit
Add hyperparameter tuning
Add model evaluation metrics comparison
Save trained models for reuse
Automate dataset download using Kaggle API

-----
👤 Author

Sree Sushma Damineni
Computer Science Graduate | ML & Data Enthusiast

