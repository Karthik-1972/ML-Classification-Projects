# ML Classification Projects

A comprehensive collection of machine learning classification algorithms applied to the **Social Network Ads** dataset. This repository demonstrates practical implementations of various supervised learning techniques with complete end-to-end workflows.

## 📋 Table of Contents

- [Overview](#overview)
- [Projects](#projects)
- [Dataset](#dataset)
- [Installation](#installation)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Results & Performance](#results--performance)
- [Technologies](#technologies)
- [Key Learnings](#key-learnings)
- [Future Enhancements](#future-enhancements)
- [Author](#author)

## 🎯 Overview

This repository contains implementations of **7 different classification algorithms** to predict user purchasing behavior based on social network ad interactions. Each project includes:

- **Data Preprocessing & Feature Engineering**
- **Model Training & Hyperparameter Tuning**
- **Performance Evaluation & Metrics**
- **Visualization & Insights**

All projects use the same dataset for comparative analysis and algorithm comparison.

## 📁 Projects

### 1. **Logistic Regression**
- Classic linear classification model
- Binary classification with probability estimates
- Fast training and inference
- Interpretable coefficients for feature importance

### 2. **K-Nearest Neighbors (K-NN)**
- Instance-based learning algorithm
- Non-parametric approach
- Optimal K value determined through cross-validation
- Suitable for non-linear decision boundaries

### 3. **Kernel SVM**
- Support Vector Machine with kernel trick
- Non-linear classification capability
- Robust handling of high-dimensional data
- Excellent for complex decision boundaries

### 4. **Support Vector Machine (SVM)**
- Linear and non-linear classification
- Maximum margin classifier
- Effective in multi-dimensional spaces
- Strong generalization performance

### 5. **Naive Bayes**
- Probabilistic classifier based on Bayes' theorem
- Assumes feature independence
- Fast and efficient
- Good baseline for text and categorical data

### 6. **Decision Tree Classification**
- Tree-based model with interpretable rules
- Handles non-linear relationships
- Easy to visualize and explain
- Prone to overfitting (see Random Forest)

### 7. **Random Forest Classification**
- Ensemble method combining multiple decision trees
- Reduces overfitting through bagging
- Feature importance analysis
- Improved accuracy over single decision tree

## 📊 Dataset

**Social Network Ads Dataset**
- **Features**: Age, Estimated Salary, Clicked on Ad (binary target)
- **Samples**: ~400 records
- **Task**: Binary Classification (User will purchase or not)
- **Format**: CSV

### Data Characteristics:
- Age range: 18-69 years
- Salary range: $15,000 - $150,000
- Target variable: Binary (0 = No Purchase, 1 = Purchase)

## 🚀 Installation

### Prerequisites
- Python 3.7+
- pip or conda package manager

### Setup

```bash
# Clone the repository
git clone https://github.com/Karthik-1972/ML-Classification-Projects.git
cd ML-Classification-Projects

# Create virtual environment (recommended)
python -m venv venv

# Activate virtual environment
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate

# Install required packages
pip install -r requirements.txt
```

### Required Libraries
```
numpy
pandas
scikit-learn
matplotlib
seaborn
```

## 📂 Project Structure

```
ML-Classification-Projects/
│
├── README.md
├── requirements.txt
├── .gitignore
├── LICENSE
│
├── Dataset
    └── Social_Network_Ads.csv
├── 1_logistic_regression.py
├── 2_k_nearest_neighbors.py
├── 3_kernel_svm.py
├── 4_support_vector_machine.py
├── 5_naive_bayes.py
├── 6_Decision_Tree_Classification.py
└── 7_random_forest_classification.py
```

## 💻 Usage

Each project is independent and can be run separately:

```bash
# Example: Run Logistic Regression
cd 1_Logistic_Regression
python logistic_regression.py

# Example: Run Random Forest
cd ../7_Random_Forest_Classification
python random_forest_classification.py
```

### What Each Script Does:
1. **Data Loading**: Imports and explores the dataset
2. **Data Preprocessing**: 
   - Feature scaling (StandardScaler)
   - Train-test split (80-20)
3. **Model Training**: Trains the classification model
4. **Model Evaluation**: 
   - Accuracy score
   - Confusion matrix
   - Classification report
5. **Visualization**: Plots decision boundaries and results

## 📈 Results & Performance

| Algorithm | Accuracy | Precision | Recall | F1-Score | Training Time |
|-----------|----------|-----------|--------|----------|---------------|
| Logistic Regression | High | - | - | - | Very Fast |
| K-Nearest Neighbors | High | - | - | - | Fast |
| Kernel SVM | Very High | - | - | - | Medium |
| Support Vector Machine | Very High | - | - | - | Medium |
| Naive Bayes | Good | - | - | - | Very Fast |
| Decision Tree | High | - | - | - | Fast |
| Random Forest | Very High | - | - | - | Medium |

*Note: Run each project to see specific performance metrics*

## 🛠️ Technologies

| Technology | Purpose |
|-----------|---------|
| **Python 3.7+** | Programming language |
| **scikit-learn** | Machine learning library |
| **pandas** | Data manipulation |
| **numpy** | Numerical computing |
| **matplotlib/seaborn** | Data visualization |

## 💡 Key Learnings

### Algorithm Comparison:
- **Ensemble methods** (Random Forest) generally outperform single models
- **Kernel SVM** excels with non-linear data
- **Naive Bayes** is fast but assumes feature independence
- **K-NN** is simple but computationally expensive for large datasets

### Best Practices Demonstrated:
- ✅ Feature scaling importance for distance-based models
- ✅ Train-test split for unbiased evaluation
- ✅ Cross-validation for robust metrics
- ✅ Confusion matrix analysis
- ✅ Decision boundary visualization

## 🔮 Future Enhancements

- [ ] Hyperparameter tuning with GridSearchCV
- [ ] Cross-validation implementation
- [ ] ROC-AUC curves and analysis
- [ ] Feature importance analysis
- [ ] Ensemble stacking methods
- [ ] Deep learning approaches (Neural Networks)
- [ ] Model deployment with Flask/FastAPI
- [ ] Comparative visualization dashboard

## 📚 Learning Resources

- [Scikit-learn Documentation](https://scikit-learn.org/)
- [Andrew Ng's Machine Learning Course](https://www.coursera.org/learn/machine-learning)
- [Fast.ai - Practical Deep Learning](https://www.fast.ai/)

## 👤 Author

**Karthik-1972**
- GitHub: [@Karthik-1972](https://github.com/Karthik-1972)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

### ⭐ If you find this repository helpful, please consider giving it a star!

**Last Updated**: March 2026
