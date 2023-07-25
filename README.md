# Healthy Eating in Dining Halls

One major issue college students face is the "freshman 15", a saying expressing the weight gain of college freshman due to the sudden exposure to large amounts and types of food in the dining halls. Although colleges have made an effort to try to include healthier options in their dining halls, there are ultimately some foods that have horrible nutritional values that are being served to many students each day. This project utilizes a linear regression model to predict the healthiness of foods at Northeastern University dining halls. The model was trained on a dataset from OpenFoodFacts, the leading nutritional information database in Europe. Our model is able to predict "NutriScore", a nutritional evaluation score created by the french government.

## Why (does this project exist)?

### The Problem

Maintaining a healthy lifestyle is not a simple task. It takes years to master a routine that will make you feel good, active, and healthy. Within dining halls, the seemingly unlimited food makes it hard for students to make healthy choices. This only negatively contributes to a students struggle to maintain a healthy lifestyle. Although there has been a slight attempt to inform students about the nutritional information about what they are eating, the lack of complete nutritional information in dining halls (usually only calories are displayed; sometimes the wrong amount) makes it extremely difficult for students to know what they are putting in their bodies. This contributes to issues such as bloating and upset stomachs.

### The Impact of This Project

We hope this project will be able to help students who wish to lead a healthy lifestyle, and those who wish to not eat high fat, low nutrtitional value, foods. We hope by giving students the convenient option to see what foods are good to eat in dining halls, we can bring some attention to the foods themselves, and hopefully change dining hall foods for the better. This project is very expandable, so we hope to be able to implement this in dining halls around the country.

## How (do we fix it)?

We decided to use machine learning and a linear regression model to predict the healthiness of foods in dining halls. This will hopefully give students a better idea of whether or not the food they are eating holds good nutritional value. The model was trained on a dataset from OpenFoodFacts, a major provider of nutritional information in Europe. The model is trained to predict a value called "Nutriscore", a metric developed by the french government to determine the healthiness of foods.

### OpenFoodFacts

OpenFoodFacts is a website that has a wide variety of food items, as well as all there nutritional information and their Nutriscores. [https://world.openfoodfacts.org](See it!)

### Nutriscore

A Nutriscore is a score developed by the French Government to assign a value to the healthiness of foods. [https://en.wikipedia.org/wiki/Nutri-Score](Learn more!)
 
## What is next?

A major drawback with our model is the model was very unsuccesful in predicting the nutriscore of fruits. It would often place fruits as one of the most unhealthy option. We believe this to be the case because we had no way of quantifying the percentage of fruits in our testing data, but in the data from "OpenFoodFacts", this metric was included. We ended up having to scratch the column from our final training set to accomodate for this. We hope to fix this issue sometime in the future by quantifying a percentage of fruit based of of the name of the item (for our testing set).

Want to see more? You can see a detailed report (here)[https://github.com/MrPeterss/healthy-dining/blob/03a2683454b1c563a35f4475d818b734aac0b535/FinalReport.ipynb]

