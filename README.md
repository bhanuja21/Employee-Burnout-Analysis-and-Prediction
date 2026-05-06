# Employee Burnout Analysis and Prediction

Employee burnout is a serious psychological condition characterized by chronic workplace stress and emotional exhaustion. It occurs when an employee experiences prolonged exposure to excessive work demands, leading to a state of physical, emotional, and mental depletion.

This project aims to analyze the factors contributing to employee burnout and build machine learning models to predict the burnout rate based on various features such as resource allocation, mental fatigue score, company type, and work-from-home setup availability.

## Features

- **Exploratory Data Analysis (EDA)**: Visualizing and understanding the dataset to find correlations between variables and the target variable (`Burn Rate`).
- **Data Preprocessing**: Handling missing values, encoding categorical variables, and scaling features.
- **Machine Learning Models**: Training predictive models including:
  - Linear Regression
  - Support Vector Regression (SVR)
  - Random Forest Regressor
- **Model Evaluation**: Using metrics like Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared (R2) score.

## Technologies Used

- **Python**: Core programming language.
- **Pandas & NumPy**: For data manipulation and numerical operations.
- **Scikit-learn**: For building and evaluating machine learning models.
- **Matplotlib & Seaborn**: For data visualization.
- **Jupyter Notebook**: For interactive development and analysis.

## Project Structure

```text
Employee-Burnout-Analysis-And-Prediction-main/
├── Final_Employee_Burnout.ipynb    # Main Jupyter Notebook containing EDA, preprocessing, and ML models
└── README.md                       # Project documentation
```

## Getting Started

1. Clone or download the repository to your local machine.
2. Install the required libraries:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Final_Employee_Burnout.ipynb
   ```
4. Run the cells in the notebook to view the analysis and train the models. Ensure the dataset (`employee_burnout_analysis-AI.xlsx`) is available in the correct path as specified in the notebook.
