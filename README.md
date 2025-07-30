# Medicine_Recommendation_System_SVC
Medicine Recommendation System Using ML model SVC.

This project develops a machine learning-based system for disease prediction and medicine recommendation, utilizing a dataset with 5,200 records and 47 attributes, including age, gender, symptoms and medical history. The system employs the SVM algorithm, with a Decision Tree Classifier explored for comparison. Data pre-processing involves cleaning, encoding categorical features, scaling features, balancing classes using SMOTE and splitting data for training and testing. The SVC model predicts diseases by classifying input features, achieving robust performance through distance-based voting. A Flask web application deploys the pre-trained SVC model, enabling real-time predictions via a user interface. Post-prediction, the system retrieves tailored recommendations for medicines, diets, precautions, workouts and disease descriptions from supplementary CSV files, parsed using ast.literal_eval. The architecture ensures scalability and accessibility, with potential for integration into healthcare platforms. While SVC drives the deployed solution, the exploration of Decision Tree highlights the project’s emphasis on evaluating ensemble methods for enhanced accuracy. This system offers a practical approach to automated disease diagnosis and personalized treatment suggestions. 


The csv files contains several datasets that were used for the analysis and model training.
The file svc.pkl is the trained ML model.
This model was deployed to frontend using HTML, CSS & JavaScript and the files index.html , style.css & script.js are also uploaded above.
A decent and interactive frontend is the user interface of this project and it's Screenshot is added as well.
