 Breast Cancer Diagnosis - ML Case Study

This project is a case study on the **Breast Cancer Wisconsin (Diagnostic) Dataset** using machine learning techniques. It involves data preprocessing, classification, evaluation using metrics like **confusion matrix** and **cross-entropy**, and performing **10-fold cross-validation**.


Dataset Info

- Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic)
- Objective: Classify tumors as **Malignant** or **Benign** based on 30 real-valued features computed from digitized images of breast masses.



 Tasks Performed

- Data loading using `sklearn.datasets.load_breast_cancer()`
- Preprocessing:
  - Null value check
  - Feature scaling with `StandardScaler`
- Categorization:
  - Mapping target values to `Malignant` and `Benign`
- Model building:
  - Logistic Regression
  - Random Forest Classifier
- Evaluation:
  - Confusion Matrix
  - Classification Report
  - Log Loss (Cross Entropy)
- Cross-validation:
  - 10-Fold Stratified Cross-Validation for Accuracy and Log Loss
- Visualizations:
  - Feature correlation heatmap
  - Feature-based scatter plots

 Visualizations Included

-  Correlation Heatmap of all features
-  Scatter Plot: Mean Radius vs Mean Texture by Diagnosis
-  Performance metrics comparison

---

 Dependencies

- Python 3.x
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn

