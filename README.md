# Patient-Survival-Prediction
Patient survival prediction using machine learning

**Introduction**

This project addresses the imperative of enhancing patient survival prediction through advanced machine learning techniques, emphasizing dimensionality reduction and classification. Motivated by seminal works such as "The use of data mining techniques to predict mortality and length of stay in an ICU" by Alramzana Nujum Navaz et al., "Predicting ICU death with summarized patient data" by K.M.D. Muthumali Karunarathna, and "A Comparison of Intensive Care Unit Mortality Prediction Models through the Use of Data Mining Techniques" by Sujin Kim et al., the focus centres on the Kaggle dataset "Patient Survival Prediction" (91,713 rows, 85 columns) from MIT’s GOSSIS (Global Open Source Severity of Illness Score) initiatives. By optimizing classification models through dimensionality reduction, we aim to overcome challenges posed by high-dimensional medical datasets, contributing to healthcare analytics research with potential positive implications for clinical decision-making.

**Final Results**

![image](https://github.com/user-attachments/assets/511c9460-714b-45d0-99da-acd3459c2a9d)

The project aimed to enhance patient survival prediction in intensive care units (ICUs) through the application of data mining techniques. Three different approaches were explored: baseline models, machine learning models with SMOTE data, and ML models after principal component analysis. The results revealed notable improvements in predictive performance across all models with the use of SMOTE data and PCA.
In the baseline models, Random Forest and XGBoost demonstrated the highest F1-scores of 0.68 and 0.71, respectively, with ROC AUC scores of 0.88 for both models. Logistic Regression performed slightly lower, with an F1-score of 0.66 and ROC AUC of 0.86.

After applying SMOTE to address class imbalance, substantial improvements were observed in all models. Random Forest achieved the highest F1-score of 0.96, accompanied by an impressive ROC AUC of 0.99. Logistic Regression showed improvement (less extent) with an F1-score of 0.79 and ROC AUC of 0.87. XGBoost maintained its high performance, with an F1-score of 0.96 and ROC AUC of 0.99.

Following PCA to reduce dimensionality, Random Forest and XGBoost models maintained their excellent performance, achieving F1-scores of 0.96 and ROC AUC of 0.99. However, Logistic Regression exhibited a decrease in performance, with an F1-score of 0.75 and ROC AUC of 0.83.

In conclusion, the project demonstrates the effectiveness of data mining and machine learning approaches in predicting patient survival in ICU settings. By addressing class imbalance and reducing dimensionality, significant improvements in predictive accuracy were achieved. These findings underscore the potential of advanced analytics techniques in assisting healthcare professionals in making informed decisions and improving patient outcomes in critical care environments.

