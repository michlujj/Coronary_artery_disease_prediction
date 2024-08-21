# asthma_attack_prediction

Dataset contains health information of patients’ diagnosis with Asthma.

It includes demographic details, lifestyle factors, environmental and allergy factors, medical history, clinical measurements and symptoms.

Modelling objective: To build a machine learning model to predict factors associated with asthma attacks.

Target variable: Diagnosis (‘Yes’ or ‘No’)

As dataset is highly imbalanced, AUC scores are used to decide on the accuracy of the Prediction model

XGBoost Classifier model: AUC = 0.5, it is selected as the final model for prediction

Predictors for asthma triggers are 1) Smoking, 2)Shortness of Breath, 4) Pet Allery, 5) Chest Tightness

