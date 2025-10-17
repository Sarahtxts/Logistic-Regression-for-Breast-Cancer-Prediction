***

# Logistic Regression for Breast Cancer Prediction

This project demonstrates the use of **Logistic Regression** to classify breast cancer based on a provided dataset, using scikit-learn and visualization libraries for analysis and reporting.

## Purpose
- To build a simple, interpretable machine learning model for breast cancer diagnosis using logistic regression.
- To visualize and evaluate the model’s predictive accuracy and performance.

## Dataset
- Assumes you have a file named `BreastCancer.csv` containing the dataset.

## Requirements
- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

You can install dependencies with:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

## Usage
1. Place `BreastCancer.csv` and `logisticregression_cancer.py` in the same directory.
2. Run the script:
```bash
python logisticregression_cancer.py
```
3. The script:
   - Reads and preprocesses the dataset.
   - Handles missing values and exploratory data analysis.
   - Trains a logistic regression model.
   - Splits data into training and test sets (70:30), stratified by class.
   - Evaluates model performance (confusion matrix, classification report, accuracy).
   - Plots classification graphs and ROC curve for visual evaluation.

## Output
- **Model accuracy** on test data
- **Confusion matrix**
- **Classification report** (precision, recall, F1-score)
- **ROC curve plot**

## Main Steps
- Data loading and cleaning
- Exploratory visualization (line plot, scatter plot, grouped plot)
- One-hot/dummy encoding for categorical variables
- Train-Test split
- Model training and prediction
- Evaluation metrics & ROC Curve visualization

## 👩‍💻 Author  
**Sarah S V**  
B.Tech – Artificial Intelligence & Data Science  
Rajalakshmi Institute of Technology, Chennai  
📧 [sarahsv.codes@gmail.com]
📧 [https://www.linkedin.com/in/sarahsv3107/]

## 📚 References
- [scikit-learn documentation](https://scikit-learn.org/)
- [USArrests dataset](https://vincentarelbundock.github.io/Rdatasets/datasets.html)
- [King County Housing Data](https://www.kaggle.com/harlfoxem/housesalesprediction)
- [Matplotlib documentation](https://matplotlib.org/)
  
***
