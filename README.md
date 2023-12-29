# DDoS Detection using Machine Learning

## Introduction

In the realm of cybersecurity, the threat of Denial of Service (DoS) and Distributed Denial of Service (DDoS) attacks poses a significant risk to the availability of online platforms. This project explores the use of Machine Learning (ML) to autonomously identify and respond to potential DDoS threats. Leveraging the [apaddos-dataset](https://www.kaggle.com/datasets/yashwanthkumbam/apaddos-dataset/data), our goal is to fortify systems against disruptive forces, safeguarding against potential disruptions to essential services.

## Data Exploration and Preprocessing

### Exploratory Data Analysis (EDA)

Exploratory Data Analysis is a foundational step in data science, providing insights into data distribution, relationships, and potential issues. In this project, we utilized EDA to:

- Check for null values and duplicates
- Explore relationships between features
- Visualize the correlation matrix
- Drop unnecessary columns for model training

![download](https://github.com/Roon311/DDoS-Detection-and-Mitigation-using-Machine-Learning/assets/75309751/f8703566-34d1-4190-bf58-65f5fe4e9edf)
### Data Preprocessing

- Encoded the target variable 'Label' into numerical values using Label Encoding
- Utilized One-Hot Encoding for categorical columns ('ip.src', 'ip.dst')
- Split the dataset into training and testing sets

## Model Building

### Decision Tree Classifier

A Decision Tree model was trained and evaluated for its accuracy in classifying DDoS attacks. Confusion matrix visualization provided insights into model performance.

### Random Forest Classifier

A Random Forest model was implemented to enhance predictive accuracy. Precision-Recall and F1 Score curves demonstrated the model's balanced trade-off between precision and recall.
<div style="display: flex; justify-content: space-between;">
    <img src="https://github.com/Roon311/DDoS-Detection-and-Mitigation-using-Machine-Learning/assets/75309751/e512c3dc-4816-4967-b5fd-86a9149c0bf1" style="width: 40%;">
    <img src="https://github.com/Roon311/DDoS-Detection-and-Mitigation-using-Machine-Learning/assets/75309751/bb782150-61ab-4236-a8a6-b373bcf8a7e5" style="width: 40%;">
</div>


### XGBoost Classifier

XGBoost, an efficient and scalable ML algorithm, was employed to further improve model performance. Feature importance was visualized, and ROC-AUC curve illustrated the model's ability to discriminate between benign and DDoS instances.

<div style="display: flex; justify-content: space-between;">
    <img src="https://github.com/Roon311/DDoS-Detection-and-Mitigation-using-Machine-Learning/assets/75309751/1a636a4f-55c1-441a-b3ea-1572ca5e56ba" style="width: 41%;">
    <img src="https://github.com/Roon311/DDoS-Detection-and-Mitigation-using-Machine-Learning/assets/75309751/4d7767fb-8b39-488f-9b19-107a4d6d4003" style="width: 40%;">
</div>


## Conclusion

The implemented machine learning models showcase promising results in detecting and classifying DDoS attacks. The precision-recall curves and feature importance analysis provide valuable insights into model behavior. This project contributes to the ongoing efforts to enhance cybersecurity measures, ensuring the integrity and availability of online platforms in the face of evolving threats.


