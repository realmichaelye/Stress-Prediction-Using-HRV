# Stress-Prediction-Using-HRV
Using the SWELL dataset from Kaggle, we've built 2 machine learning models to predict whether or not a person is under stress using Heart Rate Variability(HRV) which can be collected from modern wearables such as fitbit devices and apple watches.

## Data
https://www.kaggle.com/qiriro/swell-heart-rate-variability-hrv

## Models
* Standard Feed-forward Neural Network: Input Layer(34 neurons, ReLU activation), Hidden Layer(10 neurons, ReLU activation), Output Layer(3 neurons, softmax actionation)
* KNeighbors Classifer

## Applications
The goal is to provide a realtime biofeedback from the wearable when a person undergoes stress. This can be in the form of a notification on the iPhone to prompt the user to use a meditation app, or play a calm song through google home automatically. The data can also be recorded and be displayed using an app.
