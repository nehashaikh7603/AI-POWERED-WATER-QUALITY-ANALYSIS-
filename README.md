# Water Quality Prediction Using Machine Learning

## Project Overview

This project focuses on predicting water potability using Machine Learning classification algorithms. It analyzes different water quality parameters to determine whether water is suitable for drinking or not.

The project uses data analysis, visualization, preprocessing, and multiple machine learning models to compare their prediction performance.

## Dataset Description

The dataset contains **3,276 records** and 10 columns, including 9 water quality features and 1 target variable.

### Features Used

- pH
- Hardness
- Solids
- Chloramines
- Sulfate
- Conductivity
- Organic Carbon
- Trihalomethanes
- Turbidity

### Target Variable

- **Potability**
  - 0 – Not Potable
  - 1 – Potable

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Machine Learning Algorithms

The following classification algorithms are implemented and compared:

1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier
4. K-Nearest Neighbors (KNN)

## Project Workflow

1. Data Loading and Exploration
2. Data Cleaning and Preprocessing
3. Handling Missing Values
4. Exploratory Data Analysis (EDA)
5. Data Visualization
6. Feature Scaling
7. Model Training
8. Model Evaluation
9. Accuracy Comparison

## Project Structure

```text
Water-Quality-Prediction-ML/
│
├── water_potability_main.ipynb
├── water_potability.csv
├── model_accuracy_comparison.png
├── requirements.txt
└── README.md
```

## Installation and Execution

**Step 1: Clone the repository**

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

**Step 2: Navigate to the project folder**

```bash
cd Water-Quality-Prediction-ML
```

**Step 3: Install the required libraries**

```bash
pip install -r requirements.txt
```

**Step 4: Run the Jupyter Notebook**

```bash
jupyter notebook
```

Open `water_potability_main.ipynb` and run the cells.

## Project Outcome

The project compares multiple Machine Learning classification algorithms to predict water potability based on water quality parameters. It also provides visual analysis and model accuracy comparison to understand the performance of different algorithms.

## Author

**Neha A Shaikh**

Computer Science and Engineering Graduate

---

*This project was developed as part of an academic Machine Learning project.*
