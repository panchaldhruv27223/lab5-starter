# Lab-05: Text Classification using Machine Learning

**Course:** DS605 Fundamentals of Machine Learning  
**Academic Year:** 2025-26 (Autumn)  
**Lab Type:** Text Classification with Multiple ML Algorithms

---

## Today’s Motivation

"Success doesn't come from what you do occasionally, it comes from what you do consistently" ~ Dhruv Panchal

---

## Lab Overview

This lab provides a comprehensive introduction to text classification using machine learning techniques. Students will learn how to preprocess text data, extract features, train multiple classification models, and evaluate their performance using various metrics and visualizations.

## Learning Objectives

By the end of this lab, students will be able to:

1. **Load and explore text datasets** using scikit-learn's built-in datasets
2. **Preprocess text data** using TF-IDF vectorization with advanced parameters
3. **Split data properly** using train-validation-test methodology
4. **Implement multiple classification algorithms** (Naive Bayes, Logistic Regression, SVM, Random Forest)
5. **Evaluate model performance** using comprehensive metrics (accuracy, precision, recall, F1-score)
6. **Visualize results** through confusion matrices, performance comparisons, and feature importance plots
7. **Analyze model interpretability** and make predictions on new text samples
8. **Perform cross-validation** for robust model evaluation

## Dataset: 20 Newsgroups

The lab uses the famous **20 Newsgroups dataset**, which contains approximately 20,000 newsgroup documents across 20 different categories including:
- Computer technology (comp.graphics, comp.os.ms-windows.misc, etc.)
- Recreation (rec.sport.baseball, rec.autos, etc.)
- Science (sci.med, sci.electronics, etc.)
- Politics and religion (talk.politics.misc, talk.religion.misc, etc.)

## Lab Structure

### Files in this Lab:
- `Text_Classification_Lab.ipynb` - Main lab notebook with comprehensive text classification workflow
- `README.MD` - This documentation file

### 🔧 Technologies Used:
- **Python 3.x**
- **scikit-learn** - Machine learning algorithms and preprocessing
- **pandas** - Data manipulation and analysis
- **numpy** - Numerical computations
- **matplotlib & seaborn** - Data visualization
- **TF-IDF Vectorization** - Text feature extraction


### Machine Learning Concepts:
- **Text Vectorization**: Converting text to numerical features using TF-IDF
- **Feature Engineering**: N-gram extraction, frequency filtering
- **Model Selection**: Comparing multiple algorithms
- **Evaluation Metrics**: Beyond accuracy - precision, recall, F1-score
- **Cross-Validation**: Robust model evaluation technique


## Prerequisites

### Required Knowledge:
- Basic Python programming
- Understanding of machine learning concepts
- Familiarity with pandas and matplotlib

### Required Libraries:
```bash
pip install scikit-learn pandas numpy matplotlib seaborn jupyter
```

## Lab Execution

1. **Open Jupyter Notebook**: Launch `Text_Classification_Lab.ipynb`
2. **Run cells sequentially**: Execute each cell in order
3. **Observe outputs**: Pay attention to metrics, visualizations, and insights
4. **Experiment**: Try the additional exercises provided

## Additional Exercises

The lab includes extension exercises for advanced learning:
1. **Hyperparameter tuning** with GridSearchCV
2. **Additional model implementations** (Gradient Boosting, KNN)
3. **Error analysis** and misclassification patterns
4. **Custom dataset creation** and classification