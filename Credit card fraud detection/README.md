
💳 Credit Card Fraud Detection
Detecting anomalies in financial transactions using Support Vector Machines (SVM)

🔎 Project Overview
This project addresses the detection of fraudulent credit card transactions—a vital application in the financial industry. Using a dataset of 284,807 transactions (with only 0.173% labeled as frauds), I implemented a Support Vector Machine (SVM) model to identify anomalous behavior while handling extreme class imbalance.

🧠 My Role & Contributions
📂 Data Exploration & Preprocessing
Loaded creditcard.csv (284,807 rows × 31 columns).

Verified no missing values; recognized PCA-transformed features V1–V28.

Noted severe class imbalance: 492 frauds vs. 284,315 normal.

Applied StandardScaler to normalize features, essential for SVM.

Performed train-test split, ensuring fair fraud representation.

🤖 Model Implementation: Support Vector Machine
Used sklearn.svm.SVC to classify transactions.

Tuned model to handle high-dimensional, imbalanced data.

Focused on maximizing recall for the fraud class without overfitting.

📊 Performance Evaluation
Confusion Matrix: Detected 182 out of 199 frauds in the test set.

Accuracy: 94.19% overall, but not reliable due to imbalance.

Recall (Fraud Detection Rate): 91.46%, a strong indicator of success.

Custom Metric: Designed a score prioritizing fraud detection:

Combined accuracy + 4× recall for frauds

Final score: 92.00%

⚠️ Challenges Tackled
Handled severely imbalanced data using metric-driven evaluation.

Managed SVM’s high computational complexity on large datasets.

Focused on reducing false negatives, crucial in fraud detection.

🔍 Insights & Future Work
Standard metrics like accuracy can be misleading—custom evaluation is essential.

SVM showed strong fraud detection (91.46% recall) but is resource-intensive.

Future improvements:

Try SMOTE for oversampling minority class.

Explore ensemble or anomaly-based methods like Isolation Forest.

Aim to reduce false negatives (17 missed frauds) further.
