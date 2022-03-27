# Fish Species Prediction

The goal of the project is to build a web application that outputs the fish species when a set of features are provided as input.

Features:
- weight
- length1
- length2
- length3
- height
- width

Link to dataset: https://www.kaggle.com/aungpyaeap/fish-market

### Installation:

    1. Clone the repo to the local.
    2. Create a virtual environment.
    3. Run the requirements.txt file to install the dependencies.

### Application run:
 
    1. Run main.py.
    2. Go to the link provided in output.
    3. Insert necessary values for prediction.

### Main tools:

* flask - Web framework
* XGBoost - Classification algorithm
* scikit-learn - Machine Learning library

### Python runtime version:
python-3.7.13

### Deployment:

The application is deployed on Heroku (Platform as a Service).

The Procfile facilitates the deployment process and runtime file creates the specified python environment.

The deployed application can be accessed here. https://fish-species-classification.herokuapp.com/

### Model:

Model is trained using "Heroku_JugnuShefin.ipynb" file.

Dataset used for training is "Fish.csv".

An already trained model, "model.pkl", is uploaded in the repo.

The model was trained using "XGBClassifier" and obtained an accuracy score of 77.5 %.

The model is loaded when the flask service comes up.
