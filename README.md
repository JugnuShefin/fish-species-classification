# Fish Species Prediction

The goal of the project is to build a web application that exhibts the fish species when a set of features are prodvide as input.

The dataset contains features such as "weight", "length1", "length2", "length3", "height" and "width" and 7 species of fish.

Here is the link to the dataset. https://www.kaggle.com/aungpyaeap/fish-market

### Installation:

    1. Clone/Download the repo to my local.
    2. Create a virtual environment (this application is built and tested on Python 3.7)
    3. Run the requirements.txt (pip install -r requirements.txt)

### Running the application:
 
    1. After the environment is setup, Run main.py.
    2. A flask server will be running and a link to the webpage will be the output. Go to that link.
    3. Insert necessary values for the fields and click Predict.

### Deployment:

The application is deployed on Heroku (cloud Platform as a Service).

The Procfile in the repo facilitates the deployment process.

The deployed application can be accessed here, 

https://fish-species-classification.herokuapp.com/

### Main tools used:

* [flask](https://flask.palletsprojects.com/en/1.1.x/) - Web framework
* [scikit-learn](https://scikit-learn.org/0.22/getting_started.html) - Machine Learning library

Please review the requirements.txt file to see all the tools and their versions.

### Specify a Python Version:
The Python app uses the python-3.7.13 runtime version.

### ML Model:

The repo contains a jupyter notebook -> "Heroku_JugnuShefin.ipynb".

This notebook can be used to train the model.

The dataset is also present in the repo -> "Fish.csv".

A model is already trained and used currently for prediction -> "model.pkl".

The model was trained using "XGBClassifier" and obtained an accuracy score of 77.5 %.

The model is loaded when the flask server goes up.
