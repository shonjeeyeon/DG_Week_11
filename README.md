# Data Glacier Week 11: Persistency of a Drug (continued)

** Business Problem **

Medication persistence refers to a patient’s continued action of taking medications for the duration instructed by the prescriber. Therefore, persistency of a drug is a critical factor which contributes to industry profits as well as patient outcomes. Using data in real cases, a machine learning model can learn relationships between target variables (persistence) and dependent variables, such as patient related variables, prescriber attributes, and indicators of disease severity (e.g.: DEXA scans, t-scores of the bone, and history of bone fractures) at the beginning and during the therapy. Eventually, the model will be able to predict whether the patient will be persistent in medication therapy, given the values of dependent variables.

** Project Description **

A model will be established and deployed to automate identifying persistency of a certain pharmaceutical product. Records of 3,424 patients who take the medication will be used for analysis, and correlation between medication persistency and other factors such as patient demographics, provider attributes, clinical factors, and disease factors will be investigated. Finally, an optimal model to predict persistency based on above features will be selected and developed.

**Summary of the EDA**

1) Region plays a role in persistence level.
2) Prescribers with certain specializations are associated with higher persistence level.
3) Taking DEXA scan during the therapy is associated with higher persistency.
4) Having at least one risk factor, comorbidity, and/or concomitant therapy is related to higher persistency.
5) All of the comorbidities and concomitant therapies, as well as some of the risk factors, are associated with difference in persistency (p values < 0.05).

**Recommendations**

1) Categorization models should be used for the project.
2) To save computational efforts, simpler models, such as decision tree, linear regression, or Naive Bayes should considered first, prior to trying more complex models such as SVM, MLP or XGBoost.
3) This dataset has a substantial number of features, so for application development, using PCA or RFE to select the most important features is strongly recommended.
