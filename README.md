# International-Recipes-Predictive-Model

The dataset contains almost 40,000 recipes from 20 different countries.

In the exploratory data analysis section, distributions of the different recipes and ingredients are presented. In almost all cuisines a maximum of 5 ingredients for each of those, seems to be sufficient to identify the kind of cuisine. Even though, many cuisines share basic ingrendients so, a deeper analysis is required.

Data transformation has been required using Multibinarizer algorithm. This allows to created multiple bins containing each of those one particular ingredient. Each of these bins has then been used as a feature in the machine learning models.  

Two different classification algorithms have been tested: Logistic Regression and Random Forest Classifier. The first appears to perform slightly better and after hyperparameters tuning has been selected as best model and saved.
