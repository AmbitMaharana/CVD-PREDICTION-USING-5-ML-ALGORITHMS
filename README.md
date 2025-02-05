# CVD-PREDICTION-USING-5-ML-ALGORITHMS

Overview
Cardiovascular disease (CVD) is a leading cause of mortality worldwide, making early detection critical. This project aims to predict the likelihood of heart disease using five machine learning algorithms. By analyzing medical data, the system provides an estimate of heart disease risk, aiding both individuals and healthcare professionals in early diagnosis.

Features
Machine Learning Models: Utilizes Logistic Regression, K-Nearest Neighbors (KNN), Support Vector Machine (SVM), Decision Tree, and Random Forest.
User-Friendly Interface: Built with Flask, allowing users to input medical data and receive predictions.
Data-Driven Insights: Uses a dataset from Kaggle to train and validate the models.
Accuracy Analysis: Compares model performance to determine the most effective approach.
Technologies Used
Programming Language: Python
Frameworks: Flask (for the web interface)
Libraries: Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
Frontend: HTML, CSS
Installation & Usage
Prerequisites
Python 3.x
Required libraries (install using pip install -r requirements.txt)
Running the Project
Clone the repository:
sh
Copy
Edit
git clone https://github.com/your-username/CVD-Prediction.git
Navigate to the project directory:
sh
Copy
Edit
cd CVD-Prediction
Install dependencies:
sh
Copy
Edit
pip install -r requirements.txt
Run the Flask application:
sh
Copy
Edit
python app.py
Open http://127.0.0.1:5000/ in your browser.
Dataset
The dataset is sourced from Kaggle and consists of 14 attributes, including:

Age
Sex
Blood Pressure
Cholesterol
Max Heart Rate
ST Depression
Chest Pain Type, etc.
Model Performance
Algorithm	Accuracy
Logistic Regression	82%
KNN	64%
SVM	79%
Decision Tree	74%
Random Forest	82%
Future Work
Improve model accuracy by feature selection and hyperparameter tuning.
Integrate deep learning models for better prediction.
Expand dataset for better generalization.
Enhance the frontend for a better user experience.
Contributing
Contributions are welcome! Feel free to fork the repository and submit a pull request.

