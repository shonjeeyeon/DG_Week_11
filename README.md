# Data Glacier Week 11: Persistency of a Drug (continued)

**Summary of the EDA**

1) Region plays a role in persistence level.
2) Prescribers with certain specializations are associated with higher persistence level.
3) Taking DEXA scan during the therapy is associated with higher persistency.
4) Having at least one risk factor, comorbidity, and/or concomitant therapy is related to higher persistency.
5)All of the comorbidities and concomitant therapies, as well as some of the risk factors, are associated with difference in persistency (p values < 0.05).

**Recommendations**

Categorization models should be used for the project.
To save computational efforts, simpler models, such as decision tree, linear regression, or Naive Bayes should considered first, prior to trying more complex models such as SVM, MLP or XGBoost.
This dataset has a substantial number of features, so for application development, using PCA or RFE to select the most important features is strongly recommended.
