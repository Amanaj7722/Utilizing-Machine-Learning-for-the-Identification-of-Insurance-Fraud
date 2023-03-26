## UTILIZING MACHINE LEARNING FOR THE IDENTIFICATION OF INSURANCE FRAUD

- Insurance fraud is any act committed to defraud an insurance process. It occurs when a claimant attempts to obtain some benefit or advantage they are not entitled to, or when an insurer knowingly denies some benefit that is due. False insurance claims are insurance claims filed with the fraudulent intention towards an insurance provider. Fraudulent claims account for a significant portion of all claims received by insurers, and cost billions of dollars annually. Types of insurance fraud are diverse and can range in severity, from slightly exaggerating claims to deliberately causing accidents or damage. Insurance fraud poses a significant problem, and governments and other organizations try to deter it.

## DATASET
- Dataset Consist of 1001 row and dataset contains a variety of information about each claim, including the claimant's demographic information (such as age, gender, and marital status), policy details (such as the type of policy and coverage amount, policy_number, policy_bind_date, fraud_reported), and claim information (such as the type of claim and amount requested). There are also some additional features that provide information on the claimant's past behavior, which can be useful in identifying potential fraud.

## MODELLING
Build predictive models and compared their performance by calculation of confusion matrix then it is evaluated on various performance measuring parameters like accuracy, precision, recall, F1 score, and also on AUC curve. SVM (Support Vector Machine) and XG Boost (Extreme Gradient Boosting), K-Nearest Neighbor, Decision Tree Classifier, Random Forest Classifier, Ada Boost Classifier, Gradient Boosting Classifier, CatBoost Classifier.

- Compersion all the Models

![image](https://user-images.githubusercontent.com/68366503/227795800-bccef63c-269d-41aa-b7b9-f1dc2742e3ab.png)

After model evaluation, we select the best model for prediction. In this project using this dataset we found Decision Tree and XGboost performing better than other models. 

## CONCLUSION
- In this study, we imported the relevant dataset which correlated to the problem statement then we used various Machine learning techniques predictive models.
- These models were undergone a model evaluation process to estimate accuracy, precision, recall, f1 score, error rate, and also AUC rate. By comparing the models on basis of the result of model evaluation.





