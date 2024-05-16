# Flight-Fare-Predictor
![Python 3.7](https://img.shields.io/badge/Pyhton-3.7-blue) ![Flask](https://img.shields.io/badge/Flask-1.1-orange) ![Heroku](https://img.shields.io/badge/AWS-Deployment-brightgreen)

## Objective

The objective of this project is to calculate the fare of a flight journey based on various parameters such as source,destination,no. of stops, etc.


https://github.com/irinkesh/Flight-Fare-Predictor/assets/159822614/098df84b-2a41-4518-801d-da9e7d88ad9b


### Glimpse of the Web App
It is a system to predict flight fares. It considers factors like number of layovers, travel date, and airline (including Air India and Indigo) along with departure and arrival cities. To achieve the best results, the model is trained with "random forest regression" and then further optimized its performance through hyperparameter tuning. Finally, the system is saved and deployed as a web application using Flask on an Amazon Web Services (AWS) server instance.

## Directory Tree 
```
├── data
├── static 
│   ├── style.css
├── templates
│   ├── home.html
├── Flight_Fare_Prediction.ipynb
├── README.md
├── app.py
├── requirements.txt
```

## Dataset

Dataset Kaggle link <a href="https://www.kaggle.com/nikhilmittal/flight-fare-prediction-mh">here</a>.

