# Machine Learning Project: Bank Subscription Prediction

This project involves predicting whether a client will subscribe to a term deposit based on various client attributes. The dataset used is the "bank-full" dataset, which includes client data and the target variable indicating subscription status.

## Dataset

The dataset contains the following columns:

1. **age**: Numeric age of the client
2. **job**: Type of job (categorical: admin, blue-collar, entrepreneur, housemaid, management, retired, self-employed, services, student, technician, unemployed, unknown)
3. **marital**: Marital status (categorical: divorced, married, single, unknown)
4. **education**: Education level (categorical: basic.4y, basic.6y, basic.9y, high.school, illiterate, professional.course, university.degree, unknown)
5. **default**: Credit in default (categorical: no, yes, unknown)
6. **balance**: Average yearly balance in euros (numeric)
7. **housing**: Housing loan status (categorical: no, yes, unknown)
8. **loan**: Personal loan status (categorical: no, yes, unknown)
9. **contact**: Type of communication contact (categorical: cellular, telephone)
10. **day**: Last contact day of the month (numeric 1-31)
11. **month**: Last contact month of the year (categorical: jan, feb, mar, …, nov, dec)
12. **duration**: Last contact duration in seconds (numeric; note: highly affects the output target)
13. **campaign**: Number of contacts performed during this campaign (numeric)
14. **pdays**: Days since the client was last contacted from a previous campaign (numeric; 999 means client was not previously contacted)
15. **previous**: Number of contacts performed before this campaign (numeric)
16. **poutcome**: Outcome of the previous marketing campaign (categorical: failure, nonexistent, success)
17. **target**: Subscription to a term deposit (binary: yes, no)

## Installation

To run this project, you need to install the following Python packages. Use `pip` to install them:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn imbalanced-learn xgboost
```
## Usage

To use this project, follow these steps:

### 1. Clone the Repository

```bash
git clone https://github.com/FarahElshenawi/bank-subscription-prediction.git
```
### 2. Navigate to the Project Directory

```bash
cd bank-subscription-prediction
```
### 3. Install Dependencies

Ensure you have the required Python packages installed:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn imbalanced-learn xgboost
```
### 4. Run the Jupyter Notebook

Launch Jupyter Notebook and open `notebooks/ml_project_notebook.ipynb`:

```bash
jupyter notebook
```

## Analysis

The analysis consists of the following key steps:

### Data Preprocessing
- Load and inspect the dataset.
- Clean the data, handle missing values, and encode categorical variables.
- Prepare the data for modeling by splitting it into training and test sets.

### Model Building
- Train various classifiers such as Logistic Regression, Random Forest, XGBoost, etc.
- Perform a detailed statistical analysis.

### Dimensionality Reduction
- Apply techniques to improve model performance and interpretability.

### Evaluation
- Evaluate models using performance metrics like accuracy, precision, recall, and confusion matrices.

## Results

The results of this project include:

### Statistical Summary
- Overview of dataset statistics.

### Correlation Analysis
- Heatmaps and visualizations showing feature correlations.

### Model Performance
- Evaluation metrics including accuracy and confusion matrices.

### Feature Analysis
- Insights into feature impacts on the target variable.

## Contributing

Contributions are welcome! If you want to contribute to this project, please:

1. Fork the repository.
2. Create a new branch for your changes.
3. Make your modifications and test them.
4. Submit a pull request with a clear description of your changes.

For more details on contributing, please refer to `CONTRIBUTING.md` (create this file if needed).
