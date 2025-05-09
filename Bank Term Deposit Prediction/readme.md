🏦 Bank Term Deposit Prediction
This project aims to predict whether a client will subscribe to a bank term deposit based on data from direct marketing campaigns conducted by a Portuguese banking institution. It applies various machine learning techniques—especially ensemble methods—to build accurate classification models that support better marketing decisions.

📌 Project Overview
1. Dataset: Real-world marketing data with attributes like age, job, marital status, balance, loan info, contact method, and campaign history.
2. Problem: Highly imbalanced classes (many more "no" than "yes" responses) and missing or 'unknown' values.
3. Goal: Build robust models that generalize well and give insights into customer behavior.

💻 My Contributions
1. Exploratory Data Analysis (EDA)
Explored feature distributions and customer behavior patterns.
Identified key challenges like imbalance and missing values.
Used visualizations (histograms, boxplots, correlation heatmaps) to draw insights.

2. Data Preprocessing
Label encoded categorical features (e.g., job, education).
Treated 'unknown' values as meaningful categories.
Scaled numerical features with StandardScaler.
Tested outlier mitigation techniques (mean/median replacement) with minimal effect.

3. Model Building
Trained baseline models: Logistic Regression, Naive Bayes, KNN, SVC, and Decision Tree.
Focused on ensemble models: Bagging, AdaBoost, Gradient Boosting, Random Forest.
Assessed models with and without the 'duration' feature (important but only known post-call).

4. Evaluation & Tuning
Used accuracy, precision, recall, ROC-AUC, and confusion matrix for evaluation.
Noted that SVC performed best (~90% accuracy) with 'duration'; Gradient Boosting performed best without it.
Pruned Decision Trees to improve interpretability and reduce overfitting.

🔍 Key Takeaways
Gradient Boosting gave the best trade-off between performance and generalization.
SVC excelled with 'duration' but isn’t realistic for real-time use.
Class imbalance remained a challenge; class weighting helped but future work could explore SMOTE or other sampling strategies.
Handling 'unknown' values as categories helped preserve dataset structure without adding dimensionality.

🧠 Skills Demonstrated

1. Real-world data analysis & cleaning

2. Machine learning model selection & tuning

3. Ensemble learning techniques

4. Handling class imbalance
   
5. Model evaluation & result visualization
