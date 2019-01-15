# Reducing_NPA_For_Banks

The current Jupyter Notebook highlights the following:

* Introduction
    * Background
    * Objective
1. Libraries Implemented
2. Data Collection
    * 2.1 Data Source
    * 2.2 Data Loading
    * 2.3 Data Cleansing
        * 2.3.1 Removal of NAN's
3. Exploratory Data Analysis
4. Feature Engineering
5. Data Modeling
    * 5.1 Data Preparation
        * 5.1.1 Assigning 'Dependent' and 'Independent' Features.
        * 5.1.2 Data Stadardization: Dummification of Categorical Columns and Normalization of Numerical Columns
        * 5.1.3 Dividing the Data into 'Train', 'Validation' and 'Test' Sets.
    * 5.2 Model Comparison
        - Various Models are assessed based on their Recall, Precision, ROC-AUC and Accuracy.
    * 5.3 Model Selection : Logistic Regression
    * 5.4 Model Optimization
        * 5.4.1 'l2' Regularized Model
        * 5.4.2 'l1' Regularized Model
    * 5.5 Model Evaluation
6. Results    

|**Model**| **Train Accuracy**| **Test Accuracy**|
|:-------:|:-----------------:|:--------------:|
| Logistic Regression |  72% | 72% |    

   * **Test False Negative Rate** : 10%
   * **Test False Positive Rate** : 18%

7. Conclusion    

* The current model has an accuracy of 72% on unseen data.
* The Model makes a trade-off i.e., in order to reduce False-Negative, the False-Positive prediction rate increases.
