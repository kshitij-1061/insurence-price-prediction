# Medical Insurance Cost Prediction using Linear Regression

## Project Overview

This project develops a **Linear Regression** model to predict an individual's **medical insurance charges** based on demographic and health-related information. The project follows the complete Machine Learning pipeline, including data understanding, exploratory data analysis (EDA), preprocessing, feature engineering, model training, evaluation, model improvement, and business insights.

This project was completed as part of the **Machine Learning (4th Year B.Tech)** coursework.

---

## Dataset

**Dataset:** Medical Cost Personal Dataset

**Target Variable:** `charges`

### Features

* `age` – Age of the individual
* `sex` – Gender
* `bmi` – Body Mass Index
* `children` – Number of dependent children
* `smoker` – Smoking status
* `region` – Residential region
* `charges` – Medical insurance cost (Target Variable)

---

## Project Workflow

1. Data Understanding
2. Exploratory Data Analysis (EDA)
3. Data Preprocessing
4. Feature Engineering
5. Linear Regression Model Training
6. Model Evaluation
7. Model Improvement (Ridge/Lasso/Polynomial Regression)
8. Business Insights
9. Conclusion

---

## Technologies Used

* Python 3.x
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Machine Learning Pipeline

* Load Dataset
* Data Exploration
* Handle Missing Values
* Encode Categorical Features
* Feature Scaling
* Train-Test Split (80:20)
* Train Linear Regression Model
* Evaluate Model
* Improve Model using Ridge/Lasso Regression
* Generate Business Insights

---

## Model Evaluation Metrics

The model was evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score
* Adjusted R² Score
* Predicted vs Actual Plot
* Residual Plot

---

## Project Structure

```text
Medical-Insurance-Cost-Prediction/
│
├── insurance.csv
├── Medical_Insurance_Prediction.ipynb
├── Medical_Insurance_Report.pdf
├── README.md
└── images/
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Medical-Insurance-Cost-Prediction.git
```

Move into the project directory:

```bash
cd Medical-Insurance-Cost-Prediction
```

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## Running the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
Medical_Insurance_Prediction.ipynb
```

Run all cells sequentially.

---

## Results

* Built a Linear Regression model to predict medical insurance charges.
* Performed complete data preprocessing and exploratory data analysis.
* Compared baseline Linear Regression with improved regression techniques.
* Identified the most influential features affecting insurance costs.
* Generated business insights for insurance premium pricing and customer risk assessment.

---

## Business Insights

* Smoking status is the strongest predictor of insurance charges.
* Older individuals generally incur higher medical expenses.
* Higher BMI is associated with increased insurance costs.
* Insurance companies can use predictive models for premium pricing, customer segmentation, and risk assessment.

---

## Future Improvements

* Hyperparameter tuning
* Cross-validation
* Feature selection
* Ensemble regression models
* Model deployment using Flask/FastAPI
* Interactive dashboard using Streamlit



## License

This project is created for academic and educational purposes.
