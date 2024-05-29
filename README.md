# flavors

#DRAFT! created by AI
models and notebook names all subject to change

This repository contains the data and code used to predict beer and food pairings. The project is based on two papers:
1.	Schreurs, Michiel, et al. "Predicting and improving complex beer flavor through machine learning." Nature Communications 15.1 (2024): 2368.
2.	Park, Donghyeon, et al. "FlavorGraph: a large‐scale food‐chemical graph for generating food representations and recommending food pairings." Scientific Reports 11.1 (2021): 931.
The first paper, Schreurs et al. (2024), uses machine learning to predict beer flavor and consumer appreciation from the chemical properties of the beer. The authors collected data on 250 commercial Belgian beers, including their chemical composition, sensory attributes (as assessed by a trained tasting panel), and consumer reviews. They then trained a variety of machine learning models to predict sensory attributes and consumer appreciation from the chemical data. The best-performing model was a Gradient Boosting Regression model, which was able to accurately predict consumer appreciation.
The second paper, Park et al. (2021), introduces FlavorGraph, a large-scale graph network of food ingredients and chemical compounds. The authors used a graph embedding method to learn food representations from FlavorGraph. These food representations were then used to recommend food pairings. The authors showed that their method outperformed other methods in a node clustering task, which involves categorizing features of food.
This project will use the data and methods from both papers to predict beer-food pairings. The data from Schreurs et al. (2024) will be used to train a model to predict beer flavor from chemical data. The data from Park et al. (2021) will be used to train a model to predict food pairings from food representations. These two models will then be combined to predict beer-food pairings.
The code for this project is written in Python. The main libraries used are scikit-learn, XGBoost, and PyTorch. The code is organized into the following files:
●	data_processing.py: This file contains code for processing the data from both papers.
●	beer_flavor_model.py: This file contains code for training and evaluating the beer flavor model.
●	food_pairing_model.py: This file contains code for training and evaluating the food pairing model.
●	beer_food_pairing_model.py: This file contains code for combining the beer flavor model and the food pairing model to predict beer-food pairings.
To run the code, you will need to have Python 3.6 or later installed. You will also need to install the following libraries:
●	scikit-learn
●	XGBoost
●	PyTorch
Once you have installed the required libraries, you can run the code by executing the following command in your terminal:


python beer_food_pairing_model.py

This will train the models and predict beer-food pairings. The results will be saved to a file called beer_food_pairings.csv.
I hope this README is helpful. Please let me know if you have any questions.
