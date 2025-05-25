Prediction of Diabetes Using Machine Learning
This project aims to predict whether a person is likely to have diabetes based on several medical attributes. The model uses a dataset from the Pima Indian Diabetes Database and applies machine learning techniques to build a predictive system.

📁 Project Structure
prediction of diabetes.ipynb: Jupyter notebook containing data preprocessing, visualization, model training, and evaluation.

README.md: Project overview and documentation.

📊 Dataset
The dataset contains medical information for Pima Indian females over the age of 21. It includes the following features:

Pregnancies

Glucose

BloodPressure

SkinThickness

Insulin

BMI

DiabetesPedigreeFunction

Age

Outcome (1 = diabetic, 0 = non-diabetic)

Workflow Overview
Data Loading: Import and inspect the dataset.

Exploratory Data Analysis (EDA): Understand data distributions and correlations.

Data Preprocessing:

Handling missing values

Feature scaling using StandardScaler

Splitting dataset into training and test sets

Model Training:

Support Vector Machine (SVM) with linear kernel

Model Evaluation:

Accuracy score

Confusion matrix

Prediction System: Accepts new input and predicts diabetes risk.

🧪 Model Performance
Accuracy Score (Test Set): ~77%

The model performs reasonably well in predicting diabetes from medical attributes using a simple linear SVM.

🛠️ Requirements
Python 3.x

Jupyter Notebook

NumPy

Pandas

Matplotlib

Scikit-learn

Install dependencies using:

bash
Copy
Edit
pip install numpy pandas matplotlib scikit-learn
📌 How to Use
Clone this repository:

bash
Copy
Edit
git clone https://github.com/your-username/diabetes-prediction.git
Open the notebook:

bash
Copy
Edit
jupyter notebook "prediction of diabetes.ipynb"
Run the notebook cells to explore the workflow and test the prediction system.

📷 Sample Prediction
Example input:
[4, 148, 72, 35, 0, 33.6, 0.627, 50]
Prediction: The person is diabetic

📚 References
Pima Indian Diabetes Dataset - Kaggle
