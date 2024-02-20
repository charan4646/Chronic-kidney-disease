Chronic Kidney Disease (CKD) Analysis using Machine Learning
Overview
This project aims to predict the presence of chronic kidney disease (CKD) in patients using machine learning techniques. CKD is a critical health condition, and early detection is crucial for effective management. By analyzing relevant features from patient data, we build a predictive model to assist healthcare professionals.

Dataset:
We used the Chronic Kidney Disease dataset from the UCI Machine Learning Repository.
The dataset contains various health-related features, including age, blood pressure, serum creatinine, and more.
The target variable is binary: 1 for CKD and 0 for non-CKD.


Project Structure:-
data/: Contains the dataset files.
notebooks/: Jupyter notebooks for data exploration, preprocessing, and model development.
src/: Python scripts for utility functions and model training.
models/: Saved trained models.
requirements.txt: Dependencies for running the code.

Getting Started:-
Clone this repository
git clone https://github.com/yourusername/ckd-analysis.git
cd ckd-analysis

Install dependencies:-
pip install -r requirements.txt

information:-
Explore the Jupyter notebooks in the notebooks/ directory to understand the data and model development process.


Model Training:-
We experimented with three classifiers: Logistic Regression, Decision Tree, and Support Vector Machine (SVM).
The Decision Tree achieved the highest accuracy (95.92%) on the test set.


Usage:-
Preprocess your own data (if not using the provided dataset).
Train the model using the chosen classifier.
Make predictions on new patient data.


Results:-
The trained model can assist healthcare professionals in identifying patients at risk of CKD.
Regular model evaluation and updates are essential to maintain accuracy.


Contributors:-
A. Saicharan (sahithya4646@gmail.com)

Acknowledgments:-
UCI Machine Learning Repository for providing the CKD dataset.
