# asthma_attack_prediction

Dataset contains health information of patients’ diagnosis with Asthma.

It includes demographic details, lifestyle factors, environmental and allergy factors, medical history, clinical measurements and symptoms.

Modelling objective: To build a machine learning model to predict factors associated with asthma attacks.

Target variable: Diagnosis (‘Yes’ or ‘No’)

Oversampling via SMOTE is done as target variable is imbalanced, only 5.18% of the patient has asthma

As dataset is highly imbalanced, AUC and F1 score is used to decide on the accuracy of the Prediction model

AdaBoost Classifier model: AUC = 50.41%, it is selected as the final model for prediction

Predictors for Asthma attacks: 1) Chest Tightness, Coughing, Family History, Wheezing, Night time symptoms, Shortness Of Breadth
	



