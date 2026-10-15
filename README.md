# Student Performance Analysis using EDA and Deep Learning

**Course:** Exploratory Data Analysis and Visualisation
**Student:** Preethi S
**Roll Number:** 23AM048
**Department:** IV CSE (AIML)
**Submission Date:** 15 October 2026

## 1. Project Overview

This project performs Exploratory Data Analysis (EDA) on the UCI Student Performance dataset and builds a Multi-Layer Perceptron (MLP) model to classify students into lower- and higher-performance groups based on their final grades.

## 2. Objectives

- Understand the dataset structure and variable distributions.
- Explore grade patterns, study time, absences, and numerical correlations.
- Check missing values, duplicate records, and potential outliers.
- Prepare numerical and categorical features for modelling.
- Train and evaluate a deep-learning classification model.
- Analyse feature importance and compare learning rates.

## 3. Dataset

The project uses the mathematics-subject subset of the UCI Student Performance dataset.

- **Records:** 395
- **Columns:** 33
- **Final grade:** `G3`, on a scale from 0 to 20
- **Lower performance:** `G3 < 10`
- **Higher performance:** `G3 >= 10`

Dataset source: [https://archive.ics.uci.edu/dataset/320/student+performance](https://archive.ics.uci.edu/dataset/320/student+performance)

## 4. Technologies Used

- Python
- Google Colab
- pandas and NumPy
- Matplotlib and Seaborn
- scikit-learn
- TensorFlow and Keras

## 5. Project Workflow

1. Load and inspect the dataset.
2. Examine missing values, duplicates, and descriptive statistics.
3. Visualize grade distributions, study time, absences, and correlations.
4. Identify potential outliers using the interquartile range (IQR) method.
5. Encode categorical features and scale numerical features.
6. Split the data into training, validation, and test sets.
7. Train an MLP classification model.
8. Evaluate performance using accuracy, precision, recall, F1-score, a confusion matrix, and ROC-AUC.
9. Calculate permutation feature importance.
10. Compare selected learning rates.

## 6. Model Results

| Metric                               | Result |
| ------------------------------------ | -----: |
| Test accuracy                        | 66.67% |
| Precision — higher-performance class | 0.7174 |
| Recall — higher-performance class    | 0.8250 |
| F1-score — higher-performance class  | 0.7674 |
| ROC-AUC                              | 0.6262 |

The model recognizes higher-performing students more effectively than lower-performing students. These results represent an educational experiment and should not be used to make consequential decisions about individual students.

## 7. Repository Contents

- `Student_Performance_EDA_Deep_Learning.ipynb` — analysis, visualizations, and model implementation.
- `PreethiS_Student_Performance_EDA_Report.pdf` — final report.
- `PreethiS_Student_Performance_EDA_Report.docx` — editable report.
- `README.md` — project overview and instructions.

## 8. How to Run

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Follow the notebook's dataset-loading instructions.
3. Run the cells in order.
4. Review the visualizations and model evaluation results.

## 9. Conclusion

The project demonstrates how EDA, data preprocessing, visualization, and deep learning can be combined to investigate student performance. The evaluation also highlights the importance of checking class-wise results instead of relying on accuracy alone.

## 10. Reference

Cortez, P., and Silva, A. (2008). *Using Data Mining to Predict Secondary School Student Performance*. Proceedings of the 5th Future Business Technology Conference.

UCI Machine Learning Repository: [https://archive.ics.uci.edu/dataset/320/student+performance](https://archive.ics.uci.edu/dataset/320/student+performance)
