## LSML2

FINAL PROJECT: FRUIT AND VEGETABLE CLASSIFICATION

The app is supposed to predict the fruit or vegetable by its image.

Images:
web: flask web app
worker: celery
model: flask restful web service, trained model
redis: message broker

docker-compose.yaml is supposed to manage the containers

## Model: 
optimizer: adam, loss: CrossEntropyLoss, metric: Accuracy
Trained model is already included into model image.

## DATASET

The dataset has 3 folders: 
* train (100 images each), 
* test (10 images each), 
* validation (10 images each).

Each folder contains subfolders with images of the following food items:

fruits- banana, apple, pear, grapes, orange, kiwi, watermelon, pomegranate, pineapple, mango.
vegetables- cucumber, carrot, capsicum, onion, potato, lemon, tomato, raddish, beetroot, cabbage, lettuce, spinach, soy bean, cauliflower, bell pepper, chilli pepper, turnip, corn, sweetcorn, sweet potato, paprika, jalepeño, ginger, garlic, peas, eggplant.

Kritik Seth, "Fruits and Vegetables Image Recognition Dataset," Kaggle 2020 
[https://www.kaggle.com/kritikseth/fruit-and-vegetable-image-recognition]

