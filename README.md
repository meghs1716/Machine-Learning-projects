# Obesity Prediction

A comprehensive machine learning project for predicting obesity levels based on lifestyle and dietary habits. This project demonstrates end-to-end ML pipeline development, from data preprocessing to model evaluation.

## 📋 Project Overview

This project aims to predict obesity levels across different individuals using various health, lifestyle, and dietary features. The model classifies individuals into obesity categories based on their physical characteristics and behavioral patterns.

## 📂 Project Structure

```
obesity-prediction/
├── README.md                    # Project documentation
├── obesity_prediction.ipynb     # Main Jupyter notebook with complete ML pipeline
└── .gitignore
```

## 🎯 Features

The dataset includes the following features:

- **Demographics**: Gender, Age
- **Physical Attributes**: Height, Weight
- **Lifestyle Factors**: 
  - Physical activity frequency
  - Time using technology devices
  - Alcohol consumption
  - Smoking habits
- **Dietary Habits**:
  - Frequent consumption of high-calorie foods
  - Vegetables intake
  - Meals per day
  - Water consumption
  - Caloric beverage intake
  - Between-meal snacking habits
- **Family History**: Family history of overweight

## 🎓 Machine Learning Pipeline

The notebook implements a complete ML workflow:

1. **Exploratory Data Analysis (EDA)**
   - Data distribution analysis
   - Feature correlations
   - Missing value detection
   - Statistical summaries

2. **Data Preprocessing**
   - Handling missing values
   - Feature scaling and normalization
   - Categorical encoding
   - Train-test split

3. **Feature Engineering**
   - Feature selection
   - Feature importance analysis
   - Dimensionality reduction (if applicable)

4. **Model Development**
   - Multiple algorithms comparison
   - Hyperparameter tuning
   - Cross-validation

5. **Model Evaluation**
   - Accuracy, Precision, Recall, F1-Score metrics
   - Confusion matrix analysis
   - ROC-AUC curves
   - Feature importance visualization

## 💻 Technologies & Libraries

- **Python 3.x**
- **Jupyter Notebook** - Interactive development
- **Pandas** - Data manipulation
- **NumPy** - Numerical computing
- **Scikit-learn** - Machine learning models
- **Matplotlib & Seaborn** - Data visualization
- **Scipy** - Statistical analysis

## 🚀 Getting Started

### Prerequisites
- Python 3.7+
- pip or conda

### Installation

1. Clone the repository:
```bash
git clone https://github.com/meghs1716/obesity-prediction.git
cd obesity-prediction
```

2. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install jupyter pandas numpy scikit-learn matplotlib seaborn scipy
```

### Usage

1. Start Jupyter Notebook:
```bash
jupyter notebook
```

2. Open `obesity_prediction.ipynb` and run the cells sequentially

3. The notebook will:
   - Load and explore the data
   - Preprocess features
   - Train multiple models
   - Evaluate and compare results
   - Generate visualizations

## 📊 Model Performance

The project evaluates multiple classification models including:
- Logistic Regression
- Decision Trees
- Random Forest
- Support Vector Machines (SVM)
- Gradient Boosting models
- Neural Networks (if applicable)

Performance metrics are calculated and visualized for model comparison.

## 📈 Results

[To be updated with your final model performance metrics, accuracy scores, and key insights]

## 🔍 Key Insights

[To be updated with your findings from the analysis]

## 🛠️ Future Improvements

- [ ] Develop a web application for real-time predictions
- [ ] Implement deep learning models (LSTM, Autoencoders)
- [ ] Add class imbalance handling (SMOTE)
- [ ] Deploy model as REST API
- [ ] Create interactive visualizations with Plotly/Dash
- [ ] Implement explainability features (SHAP, LIME)
- [ ] Add more features from additional health datasets
- [ ] Fine-tune hyperparameters with advanced techniques

## 📝 License

This project is open source and available under the MIT License.

## 👤 Author

**Meghs1716**
- GitHub: [@meghs1716](https://github.com/meghs1716)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/meghs1716/obesity-prediction/issues).

## 📚 References

- Scikit-learn Documentation: https://scikit-learn.org/
- Pandas Documentation: https://pandas.pydata.org/
- Machine Learning Best Practices: https://developers.google.com/machine-learning/crash-course

---

**Last Updated**: June 2026
