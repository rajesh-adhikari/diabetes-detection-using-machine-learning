# diabetes-detection-using-machine-learning
The project predicts whether a patient is diabetic or not using Random Forest Classifier which builds multiple decision trees and merges them together to get a more accurate and stable result.
Accuracy: 0.7532
The dataset link : https://drive.google.com/file/d/1wpQ-gIrb2R0_VmG5skDIoRMkVK1Fn-7m/view?usp=sharing

A form was designed to take the inputs from the user which were passed as a parameter to our predict function which uses Random Forest Classifier (Supervised Learning) to classify the patients as diabetic or non-diabetic.The form was designed in HTML/CSS.

Following were the inputs taken from the end user :

1.	Number of Pregnancies
2.	Glucose Level
3.	Blood Pressure Level
4.	Skin Thickness
5.	Insulin
6.	BMI
GUI for end user interaction was developed using Flask Framework and HTML/CSS in the Frontend and Python in the backend for developing the controller files and model files.


Results:

Diabetic if the predicted value is ‘1’.

Non-Diabetic if the predicted value is ‘0’.


Inorder to execute it :

1] Write the following command in cmd : controller.py

2] It will start the server and provide an url i.e. "http://127.0.0.1:5000" copy it in browser and see the magic !

# Deployment on Heroku
Heroku git link:https://git.heroku.com/diabetes-prediction-4.git
