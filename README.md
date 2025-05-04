# 💼 Salary Prediction based on Demographics

This project aims to predict the salary of individuals from various countries and racial backgrounds based on demographic and professional attributes. It uses machine learning models to uncover patterns in income influenced by factors such as occupation, age, gender, experience, education, etc.

## 📊 About the Dataset

The dataset used in this project is sourced from Kaggle and contains:
- **6703 rows** and **8 columns**

This dataset provides a rich set of features allowing analysis and prediction of salary based on:
- Age
- Gender
- Education level
- Job title
- Country
- Race
- Years of experience

### 🔍 Data Dictionary

| Column               | Description                                      |
|----------------------|--------------------------------------------------|
| Age                  | Age of the employee                              |
| Gender               | Gender of the employee                           |
| Education Level      | Education level of the employee                  |
| Job Title            | Job title of the employee                        |
| Years of Experience  | Years of experience of the employee              |
| Salary               | Salary of the employee                           |
| Country              | Country of the employee                          |
| Race                 | Race of the employee                             |

## 🧹 Data Preprocessing

- Dropped rows with null/missing values due to their minimal count.
- Encoded categorical variables such as race, education, and country.
- Handled imbalances and standardized numerical features for better model performance.

## 🤖 Model Building

Machine learning models applied:
- **Random Forest Regressor**
- **Decision Tree Regressor**
- **Support Vector Regressor**

### 📈 Evaluation Metrics

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)

Each model was evaluated to determine its effectiveness in predicting salaries based on the given features.

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn (for visualizations)
- Jupyter Notebook

## 🚀 How to Run

1. Clone this repository.
3. Open the notebook: `DS_Salary_Prediction.ipynb`
4. Run all cells to reproduce the results.

## 📬 Group Members

For questions or feedback, feel free to reach out:
- Shayan Haider 21K-3211
- Ahmed Ali     21K-3212
- Asad Noor     21K-4678
