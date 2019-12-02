# deploy_machine_learning

https://github.com/karanmurthy7/machine-learning-flask-example

machine-learning-flask-example
This project demonstrates how to train and deploy a simple model. Using a pima indians diabetes dataset, I create a model that can predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset. Other applications can use this model through a single route server. This project is composed of two python files: a model training script and the web server.

# model
diabetes-classification-model.py trains and saves the model to the disk.

# server
server.py contains all the requiered for flask and to manage APIs.

# request
request.py contains the python code to process POST request to server.

# deploy model in pythonanywhere.com
I deployed machine learning model about diabetes prediction into pythonanywhere.com.


If you want to try how the model work, you can use my url in the postman and input the following data:

Url: http://jokopram.pythonanywhere.com/api

Input example: { "pregnancy":6, "glucoes":148, "bloodpres":72, "skin":35, "insulin":0, "bmi":33.6, "diabetesPedi":0.627, "age":50
}
