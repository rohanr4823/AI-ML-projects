💳 Credit Card Fraud Detection
This project focuses on identifying fraudulent credit card transactions using a Support Vector Machine (SVM) model. It addresses a critical real-world problem where detecting rare anomalies can prevent major financial losses. The dataset used consists of 284,807 transactions with 31 features, including anonymized PCA components (V1–V28), Time, and Amount. Only 0.173% of the transactions (492 cases) are fraudulent, making it a highly imbalanced classification problem.

🧠 My Contributions
🔍 Data Exploration & Preprocessing
1.Loaded the dataset (creditcard.csv) and verified no missing values.
2.Identified the extreme class imbalance (492 frauds vs. 284,315 normal).
3.Standardized all features using StandardScaler, crucial for SVM’s performance.
4.Split the data into training and testing sets, maintaining class representation.

🤖 Model Development (SVM)
1.Implemented an SVM classifier using scikit-learn, suited for high-dimensional data.
2.Tuned the model to optimize detection of rare fraud cases using kernel tricks.
3.Managed computational efficiency while training on over 280k samples.

📊 Performance Evaluation
Evaluated model using:
1.Confusion Matrix: Detected 182 of 199 frauds in the test set.
2.Accuracy: Achieved 94.19%, though dominated by non-fraud predictions.
3.Fraud Detection Rate (Recall): 91.46%—critical in minimizing missed frauds.
4.Custom Metric: Designed a composite score balancing accuracy and weighted recall, yielding 92.00%, emphasizing fraud detection.

🛠️ Challenges Tackled
1.Addressed severe class imbalance using custom metrics and evaluation strategies.
2.Managed SVM’s computational cost through efficient preprocessing and careful feature scaling.
3.Analyzed false negatives (17 missed frauds) to inform potential improvements using oversampling (e.g., SMOTE) or ensemble approaches.

🔍 Insights & Key Takeaways
1.Standard accuracy is misleading in imbalanced datasets; custom metrics matter more.
2.SVM achieved 91.46% recall for frauds, showing strong potential despite class imbalance.
3.Further improvements can include ensemble methods or lightweight anomaly detection models (e.g., Isolation Forest).

This project showcases my skills in Python, scikit-learn, pandas, and data visualization, along with the ability to address real-world ML challenges.
