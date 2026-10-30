# 🏥 Insurance Charges Prediction | Machine Learning

My first Machine Learning model, built using **Linear Regression**, to predict insurance charges based on customer and healthcare-related information.

This project marks my entry into practical Machine Learning, where I explored the complete model-building workflow, from Exploratory Data Analysis (EDA) and data preprocessing to model training and evaluation.

## 🎯 Project Objective

The objective of this project is to develop a regression model that estimates insurance charges based on multiple independent features, including age, BMI, smoking status, number of children, medical consultations, hospital expenditure, and other relevant factors.

## 🛠️ Technologies & Libraries Used

- **Python** – Core programming language
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical computations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical data visualization
- **Scikit-learn** – Machine Learning model development
- **Statsmodels** – Multicollinearity analysis using VIF
- **Jupyter Notebook** – Development environment

## 📊 Machine Learning Workflow

The project follows these major steps:

1. **Data Loading & Inspection**
   - Imported the dataset using Pandas.
   - Examined dataset dimensions, columns, data types, and statistical summaries.
   - Checked for missing values and duplicate records.

2. **Exploratory Data Analysis (EDA)**
   - Explored numerical and categorical features.
   - Used statistical summaries and visualizations to understand the dataset.

3. **Data Preprocessing**
   - Handled missing values using mean and mode imputation.
   - Detected outliers using boxplots.
   - Applied the Interquartile Range (IQR) method for outlier filtering.
   - Performed categorical encoding using Label Encoding.

4. **Feature Analysis**
   - Investigated multicollinearity using Variance Inflation Factor (VIF).
   - Examined relationships among numerical independent features.

5. **Model Building**
   - Selected independent variables (X) and the target variable (y).
   - Split the dataset into training and testing sets (80:20).
   - Trained a Linear Regression model using Scikit-learn.

6. **Model Evaluation**
   - Generated predictions on the test dataset.
   - Evaluated model performance using the R² score.

## 📈 Model Performance

| Metric | Result |
|---|---:|
| Algorithm | Linear Regression |
| Original Dataset Size | 1,338 rows |
| Dataset After Outlier Filtering | 881 rows |
| Training Split | 80% |
| Testing Split | 20% |
| Random State | 42 |
| Test R² Score | 0.9689 |

**Initial R² Score: 96.89%**

The model achieved an R² score of approximately 0.9689 on the test set, indicating that it explained approximately 96.89% of the variance in the target variable within that test set.

*Note: This is an initial experimental result. The preprocessing was performed before the train-test split, and outlier filtering removed a substantial portion of the original dataset. Further validation and preprocessing improvements are required before considering this a reliable estimate of real-world performance.*

## 📁 Project Structure

```text
Insurance-Charges-Prediction/
│
├── Linear_Regression_Problem_Insurance_charges_prediction_1st_Model.ipynb
│
├── dataset/
│   └── new_insurance_data.csv
│
└── README.md
```

*The dataset is not included unless separately added to the repository.*

## 🚀 How to Run This Project

**1. Clone the repository**

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

**2. Navigate to the project directory**

```bash
cd Insurance-Charges-Prediction
```

**3. Install the required libraries**

```bash
pip install numpy pandas matplotlib seaborn scikit-learn statsmodels jupyter
```

**4. Open Jupyter Notebook**

```bash
jupyter notebook
```

**5. Open the notebook and execute the cells.**

Make sure the dataset is available at the file path specified in the notebook, or update the path according to your local directory.

## 🔍 Key Learnings

Through this project, I gained practical experience in:

- Understanding the end-to-end Machine Learning workflow.
- Performing Exploratory Data Analysis.
- Handling missing values and outliers.
- Understanding multicollinearity and VIF.
- Preparing data for regression algorithms.
- Training and evaluating a Linear Regression model.
- Interpreting model performance using R².

## 🔮 Future Improvements

This is my first version, and I plan to improve it continuously.

- Improve preprocessing using Scikit-learn Pipelines.
- Prevent data leakage during preprocessing.
- Explore One-Hot Encoding for categorical features.
- Evaluate performance using MAE and RMSE.
- Implement cross-validation.
- Experiment with other regression algorithms.
- Build an interactive user interface using Streamlit.
- Deploy the model as a web application.

## 💡 Project Status

**Version 1.0 – Initial Model Completed**

This project represents the beginning of my practical Machine Learning journey. I believe model building is an iterative process, and every model provides an opportunity to learn, experiment, identify limitations, and improve.

---

⭐ If you find this project interesting, feel free to explore the notebook and share your feedback!

**Learning. Building. Experimenting. Improving.**

#MachineLearning #Python #LinearRegression #DataScience #LearningJourney
