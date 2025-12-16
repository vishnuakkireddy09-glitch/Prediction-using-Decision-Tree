Bank Marketing Decision Tree Classifier
📌 Project Overview

This project implements a Decision Tree Classifier to predict whether a customer will subscribe to a term deposit based on demographic and behavioral data. The model is trained using the Bank Marketing dataset from the UCI Machine Learning Repository
.

The purpose of this project is to help banks improve their marketing strategies by targeting potential customers more effectively.

🗂 Dataset

Source: UCI Bank Marketing Dataset

File used: bank-full.csv

Number of instances: 45,211

Features:

Demographic: age, job, marital status, education, etc.

Behavioral: contact method, last contact duration, previous campaigns, etc.

Target variable: y (yes → subscribed, no → not subscribed)

🛠 Tech Stack

Python 3.x

Libraries:

pandas – Data manipulation
📈 Results

Accuracy: Example ~90% (depends on preprocessing)

Precision, Recall, F1-score: Evaluates model performance for both classes (yes and no)

Confusion Matrix: Shows true vs predicted classifications graphically

🔧 How to Run

Clone the repository:

git clone <your-repo-link>


Navigate to the project folder:

cd bank-marketing-decision-tree


Install dependencies:

pip install -r requirements.txt


Place bank-full.csv in the project folder.

Run the Python script or notebook:

python decision_tree_bank.py

📌 Future Improvements

Tune hyperparameters (max_depth, min_samples_leaf) to reduce overfitting

Handle class imbalance with SMOTE or class_weight='balanced'

Compare with other classifiers (Random Forest, Logistic Regression)

Visualize the decision tree for interpretability

Deploy as a web application for real-time predictions

📚 References

UCI Bank Marketing Dataset

scikit-learn Decision Tree Documentation

pandas Documentation

⚖ License

This project is open source under the MIT License.

scikit-learn – Machine Learning (Decision Tree, preprocessing, evaluation)

matplotlib – Visualization
