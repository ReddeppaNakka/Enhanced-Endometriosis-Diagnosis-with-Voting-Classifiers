 Endometriosis Diagnosis Using a Voting Classifier (SVM, Gradient Boosting, Decision Tree)
 Overview
Endometriosis is a chronic condition affecting millions of women globally, often causing pain and infertility. Accurate diagnosis is essential yet remains challenging. This project leverages machine learning to build a robust diagnostic model using a Voting Classifier that combines the strengths of Support Vector Machine (SVM), Gradient Boosting, and Decision Tree classifiers to enhance diagnostic accuracy and reliability.

 Objective
The primary aim is to improve clinical diagnosis of endometriosis by:

Reducing diagnostic delays

Increasing prediction accuracy

Combining multiple ML models to make more reliable decisions

 Dataset
A binary clinical dataset was created and preprocessed, containing:

Patient symptoms

Medical history

Labels: 0 for non-endometriosis, 1 for endometriosis

Preprocessing Steps:
Handling missing values

Normalization

Feature selection

 Methodology
Models Used:
SVM: Handles high-dimensional data well

Gradient Boosting: Reduces bias and variance

Decision Tree: Easy to interpret and fast

Voting Mechanism:
Soft Voting: Averages predicted probabilities

Hard Voting: Uses majority vote from models

The final classifier aggregates predictions from all three models to improve accuracy.

📊 Evaluation Metrics
Accuracy

Precision

Recall

F1-Score

The voting classifier showed improved performance over individual models across all metrics.

 Tech Stack
Python

Scikit-learn

Pandas / NumPy

Matplotlib / Seaborn (for visualization)

Jupyter Notebook

 Results
The integrated model demonstrated:

Higher diagnostic accuracy

Better robustness and reliability

Clinical potential in assisting with early and accurate diagnosis

 Future Work
Expand the dataset with more patient records

Include additional clinical features

Explore deep learning models (e.g., CNNs, LSTMs) for enhanced performance

 How to Run
Clone the repository

Install required libraries:

bash
Copy
Edit
pip install -r requirements.txt
Run the main notebook:

bash
Copy
Edit
jupyter notebook endometriosis_voting_classifier.ipynb
 Acknowledgments
This project highlights the role of machine learning in medical diagnostics and demonstrates how model integration can lead to better clinical tools.

