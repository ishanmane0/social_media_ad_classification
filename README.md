Social Media Ad Classification

Predicting whether a social media advertisement will convert based on user demographics such as age, estimated salary, and gender.
This project demonstrates end-to-end machine learning: from data cleaning and preprocessing to model training, evaluation, and interpretation.

Project Overview

Businesses spend billions on targeted ads — knowing which users are likely to click or convert helps optimize ad budgets.
This project builds and compares ML models to predict ad conversion likelihood, with insights that can guide marketing strategies.

⚙️ Tech Stack

Languages: Python (Pandas, NumPy)

ML & Modeling: Scikit-learn (Logistic Regression, Random Forest, SVM, KNN, etc.)

Visualization: Matplotlib, Seaborn

Development: Jupyter Notebook

 Workflow

Data Preparation
Loaded dataset (CSV)
Handled missing values
Encoded categorical features (e.g., Gender)
Scaled numerical features (Age, Salary)
Train/Test split (stratified)
Exploratory Data Analysis (EDA)
Visualized distributions of age and salary
Analyzed ad conversion rates by demographic segments
Modeling
Logistic Regression
Random Forest Classifier
Support Vector Machine (SVM)
K-Nearest Neighbors (KNN)
Evaluation
Accuracy, Precision, Recall, F1-Score
Confusion Matrix
ROC Curve & AUC

📈 Results

Best performing model: Random Forest 

Salary and Age were most predictive features.

Trade-off between precision and recall shows importance of model choice based on business needs.

🛠️ How to Run

Clone the repo:

git clone https://github.com/ishanmane0/social_media_ad_classification.git
cd social_media_ad_classification


Install dependencies:

pip install -r requirements.txt


Open Jupyter Notebook:

jupyter notebook


Run social_media_ad_classification.ipynb
