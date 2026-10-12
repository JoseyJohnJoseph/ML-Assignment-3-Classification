# ML Assignment 3 – Classification

## Objective
To apply supervised learning techniques to the Breast Cancer Wisconsin dataset available in Scikit-learn and compare the performance of five classification algorithms.

## Dataset
- **Source:** Scikit-learn
- **Samples:** 569
- **Features:** 30 numerical features
- **Target classes:** Malignant and Benign

## Algorithms Implemented
1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier
4. Support Vector Machine (SVM)
5. k-Nearest Neighbors (k-NN)

## Preprocessing
- Checked for missing values and duplicate records.
- Used median imputation to handle missing numerical values.
- Split the dataset into 80% training data and 20% testing data.
- Standardized features using StandardScaler for scale-sensitive algorithms.

## Model Evaluation
The models were evaluated using accuracy, precision, recall, and F1-score.

| Algorithm | Accuracy |
|---|---:|
| Logistic Regression | 98.25% |
| Decision Tree | 91.23% |
| Random Forest | 95.61% |
| SVM | 98.25% |
| k-NN | 95.61% |

**Best-performing models:** Logistic Regression and SVM, tied at 98.25% accuracy.

**Lowest-performing model:** Decision Tree, with 91.23% accuracy.

## Tools and Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab / Jupyter Notebook

## Conclusion
Logistic Regression and SVM achieved the highest test accuracy in this experiment. Decision Tree achieved the lowest accuracy among the five models.

## Notebook
See `ML_Assignment_3_Classification.ipynb` for the implementation, evaluation metrics, and results.
