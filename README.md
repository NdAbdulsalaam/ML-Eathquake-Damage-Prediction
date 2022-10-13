<img src = "https://th.bing.com/th/id/OIP.HhUfenLp_nZ-QGte3_O1twHaE7?pid=ImgDet&rs=1" width = "1500">
<h1 align = 'center', style = 'font-size:48px'><strong>Earthquake Damage in Kavrepalanchok</strong></h1>

## Overview
In this notebook, I developed a model aimed at predicting eathquake in [Kavrepalanchok.](https://en.wikipedia.org/wiki/Kavrepalanchok_District). The purpose is to obtain the best model and the best depth for the prediction and to emphasize on the various steps needed to build such a model. I also explained the possible methods to deploy the model, these include wrapping the model in a function so that a programmer can provide inputs and then receive a prediction as output or creating an interactive dashboard, where a user can supply values and receive a prediction.

## About the data:
The was queried from a database comprising of four tables (id_map, building_structure, building damage and household_demographics) and four districts labelled 1 to 4. Myagdi is 1, Ramechhap is 2, and Gorkha is 4 of [Nepal Districts.](https://en.wikipedia.org/wiki/List_of_districts_of_Nepal). Then, What's the district ID for Kavrepalanchok? Did you say 3?! Yes, you are right. Kavrepalanchok is district ID 3 according to our database.

Since you may not have access to this database, I have saved the results of my query as `kavrepalanchok_raw.csv` which can the be wrangled (cleaned). The cleaned data, `kavrepalanchok_clean.csv`, gotten from my wragle function has also been provided for you to make use of - this as been made specifically for this project. Finally, `kavrepalanchok_test.csv` is also available to check for model performance.

## Algorithms Used
- Linear Regression
- Decision Tree Classifier
   
## Acknowledgment
- [WorldQuant University](https://www.wqu.edu/)

## Access on
[![Kaggle Badge](https://img.shields.io/badge/-Kaggle-0e76a8?style=flat&labelColor=0e76a8&logo=dev.to&logoColor=white)](https://www.kaggle.com/code/nurudeenabdulsalaam/weratedogs-twitter-analysis)