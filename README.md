# Optum-Stratethon-Season4
HEALTHCARE-WEB-APP

It uses ML algorithms to build powerful and accurate models to predict the risk (High / Low) of the user of having a Heart Attack or Breast Cancer based on the user's specific attributes like age, sex, heart rate, blood sugar, etc.

MODEL BUILDING
1. Logistic Regression 
2. KNN
3. SVM 
4. Decision Trees 
5. Random Forest 
6. Gradient Boosting 
7. XGBoost

An interactive side-dashboard is created using the streamlit st.sidebar call which enables the user to do the following:

Choose dataset - Heart Attack / Breast Cancer
Choose algorithm - Logistic Regression , KNN , SVM , Decision Trees , Random Forest , Gradient Boosting , XGBoost.
Change the important parameters for each model - Learning Rate, Random State, Regularization Coeff, Gamma, Kernel, n_estimators etc.
After training using the parameters selected by the user, the tuned model is built and ready to be tested on our testing data. The classification plot and confusion matrix is displayed for the model selected along with the model metrics: Accuracy, Precision, Recall, F1-Score, Mean Squared Error, Execution Time. The user can observe real-time changes in the plots and metrics as they change the model parameters further.

This is a great way to understand the different ML algorithms and how they are influenced by tuning the hyperparameters.

The 7 models (optimum tuning) performed as follows:
Criterion: Accuracy

USER PREDICTION

In this section, the user can use any model developed above to predict their status (High Risk / Low Risk) using their own values. (Either for Heart Attack or Breast Cancer)

THANK YOU!!
https://shubhamchaudhary1-optum-stratethon-season4-ml-healthcare-yedn9w.streamlitapp.com/
