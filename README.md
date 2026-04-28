# Heart_Attack_Prediction
This project implements a machine learning pipeline to predict the likelihood of a heart attack based on patient health metrics. By analyzing clinical data, the model identifies key risk factors and provides a classification for potential cardiac events.
<img width="2048" height="2048" alt="image" src="https://github.com/user-attachments/assets/d55ef5f4-04cb-4bcf-986e-5973561240f3" />
🔍 Overview
Heart disease remains one of the leading causes of mortality globally. This project leverages Python and Scikit-learn to build a predictive model that can assist in early detection. The workflow includes comprehensive data cleaning, exploratory data analysis (EDA), and the implementation of various classification algorithms.

📊 Dataset
The project utilizes the data.csv file included in this repository. It contains several physiological indicators, such as:

Demographics: Age, Sex.

Clinical Metrics: Chest pain type, Resting blood pressure, Cholesterol levels, Fasting blood sugar.

Cardiac Tests: Resting electrocardiographic results, Maximum heart rate achieved, Exercise-induced angina.

🛠 Technologies Used
Python 3.x

Pandas: For data manipulation and analysis.

NumPy: For numerical operations.

Matplotlib / Seaborn: For data visualization and heatmaps.

Scikit-learn: For model building, scaling, and evaluation.

🚀 Key Features
Exploratory Data Analysis (EDA): Visualizing correlations between features and the target variable.

Data Preprocessing: Handling missing values, feature scaling (StandardScaler), and encoding categorical variables.

Model Selection: Comparing multiple algorithms (e.g., Logistic Regression, Random Forest, or SVM) to find the highest accuracy.

Evaluation Metrics: Detailed reports including Confusion Matrix, Precision, Recall, and F1-Score.

📈 Results
The final model achieved an accuracy of Ensembling the accuracy score is 86.88%. Key findings suggest that exercise-induced angina, chest pain, is a major symptom of a heart attack. were the most significant predictors of heart attack risk.
