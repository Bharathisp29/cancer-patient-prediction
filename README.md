# cancer-patient-prediction
This project uses machine learning techniques to predict whether a patient is likely to have cancer based on health, lifestyle, and genetic risk factors. It utilizes a structured dataset of 1,500 patients with 9 key features such as age, BMI, physical activity, smoking habits, and cancer history.

📁 Dataset Description
The dataset Cancer dataset.csv contains the following columns:

Age: Patient's age

Gender: 1 = Male, 0 = Female

BMI: Body Mass Index

Smoking: 1 = Yes, 0 = No

GeneticRisk: 1 = High, 0 = Low

PhysicalActivity: Scale of physical activity level

AlcoholIntake: Level of alcohol consumption

CancerHistory: 1 = Has family/personal cancer history, 0 = No

Diagnosis: 1 = Cancer Positive, 0 = Cancer Negative (Target Variable)

🧠 Project Workflow
Data Preprocessing

Load and inspect the dataset

Normalize numerical features using MinMaxScaler

Split into training and test datasets

Model Building

Train classification models such as:

Logistic Regression

Random Forest

Support Vector Machine (SVM)

K-Nearest Neighbors (KNN)

Evaluate performance using accuracy, precision, recall, and F1-score

Visualization

Visualize feature distributions, correlation heatmaps, and confusion matrices

🛠 Technologies Used
Python 3.x

Pandas, NumPy

Scikit-learn

Matplotlib, Seaborn

Jupyter Notebook

🚀 How to Run
Clone this repository:

Install required libraries:

pip install -r requirements.txt
Run the notebook:

jupyter notebook
✅ Output
The final output is a trained ML model that predicts whether a patient is likely to be diagnosed with cancer based on the input features.

