# Deployment of Salary Prediction Model on Heroku 

## Instructions for Running the project:

1	Create the machine learning model by running below command :

- python model.py

This would create a serialized version of our model into a file model.pkl

2	Run app.py using below command to start Flask API :

- python app.py

By default, flask will run on port 5000.

Navigate to URL http://localhost:5000

*You can also send direct POST requests to FLask API using Python's inbuilt request module :

- python request.py


### Credit: 
https://www.youtube.com/watch?v=UbCWoMf80PY&ab_channel=KrishNaik
