# StudentGradesPredictionUsingML
A Machine Learning project that predicts student academic performance using multiple regression algorithms. The project includes data preprocessing, exploratory data analysis (EDA), model training, evaluation, and comparison of different machine learning techniques for predicting student grades.

📌 Project Overview

Educational institutions can leverage machine learning to identify factors affecting student performance and forecast academic outcomes. This project explores student data and builds predictive models to estimate student grades based on study habits and other relevant features.

The notebook demonstrates the complete machine learning workflow:

Data collection and preprocessing
Exploratory Data Analysis (EDA)
Feature selection
Model training
Model evaluation
Performance comparison
Grade prediction
🎯 Objectives
Analyze factors influencing student performance.
Build predictive models for grade forecasting.
Compare different regression algorithms.
Evaluate model accuracy and reliability.
Generate actionable insights from educational data.
🛠️ Technologies Used
Programming Language
Python
Libraries
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Development Environment
Jupyter Notebook
📂 Project Structure
StudentGradesPredictionUsingML/
│
├── AppliedAICW (1).ipynb     # Main notebook
├── Dataset.csv               # Student dataset
├── README.md
└── Images/
    └── visualizations.png
📊 Exploratory Data Analysis

The project includes:

Data Inspection
Dataset overview
Data types analysis
Missing value detection
Statistical summaries
Data Visualization
Correlation analysis
Feature distributions
Scatter plots
Heatmaps
Performance trends

These visualizations help identify relationships between study-related factors and academic outcomes.

🤖 Machine Learning Models

The notebook evaluates multiple machine learning algorithms, including:

Linear Regression

Used as a baseline regression model for predicting student grades.

Support Vector Regression (SVR)

Captures complex non-linear relationships within the dataset.

Stochastic Gradient Descent Regressor (SGD)

Efficient regression model for larger datasets and iterative learning.

The models are trained and compared based on prediction performance.

🔄 Machine Learning Workflow
1. Data Preprocessing
Cleaning data
Handling missing values
Encoding categorical variables (if applicable)
Feature scaling
2. Train-Test Split

The dataset is divided into:

Training set
Testing set
3. Model Training

Multiple regression algorithms are trained using the training data.

4. Evaluation

Models are evaluated using performance metrics such as:

Mean Absolute Error (MAE)
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
R² Score
5. Prediction

The trained models predict student grades based on input features.

📈 Sample Use Case

The system can predict expected grades based on factors such as:

Study hours
Attendance
Previous academic performance
Learning habits
Other educational indicators

Example:

study_hours = 9.25
predicted_grade = model.predict([[study_hours]])
🔍 Key Insights
Study time strongly influences academic performance.
Certain behavioral and academic factors contribute significantly to grade prediction.
Regression models can effectively estimate student outcomes.
Model comparison helps identify the most accurate prediction approach.
🚀 How to Run
Clone the Repository
git clone https://github.com/M-FATEH/StudentGradesPredictionUsingML.git
Navigate to the Project
cd StudentGradesPredictionUsingML
Install Dependencies
pip install pandas numpy matplotlib seaborn scikit-learn
Launch Jupyter Notebook
jupyter notebook

Open:

AppliedAICW (1).ipynb
📚 Dataset

The project uses a student performance dataset containing academic and study-related variables used to predict student grades.

Typical features may include:

Study hours
Attendance
Previous grades
Educational background
Student engagement metrics
📊 Future Improvements
Hyperparameter tuning
Cross-validation
Ensemble learning methods
Feature engineering
Deployment using Flask or Streamlit
Real-time prediction interface
👨‍💻 Author

Fateh Mohammed

GitHub: M-FATEH GitHub Profile

⭐ Support

If you found this project useful:

⭐ Star the repository
🍴 Fork the project
📢 Share it with others
