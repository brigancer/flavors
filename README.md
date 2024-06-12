# Lessons in Chemisty and Beer Pairing

Project Overview
This project aims to develop a machine-learning model that can recommend personalized beer and food pairings based on the chemical properties of beers and the flavor profiles of foods. The model leverages insights from two key research papers:

This repository contains the data and code used to predict beer and food pairings. The project is based on two papers:
	
	1. Schreurs, Michiel, et al. "Predicting and improving complex beer flavor through machine learning." Nature Communications 15.1 (2024): 2368.

	
	2. Park, Donghyeon, et al. "FlavorGraph: a large‐scale food‐chemical graph for generating food representations and recommending food pairings." Scientific Reports 11.1 (2021): 931.
	
**Schreurs et al.** (2024): This study used machine learning to predict beer flavor and consumer appreciation from the chemical composition of beers. It analyzed 250 commercial Belgian beers, measuring over 200 chemical properties and incorporating sensory analysis from a trained tasting panel and over 180,000 consumer reviews. The study found that a Gradient Boosting Regression model could accurately predict consumer appreciation and identified specific compounds as drivers of beer flavor.
  	
**Park et al.** (2021): This study introduced FlavorGraph, a large-scale graph network of food ingredients and chemical compounds. The graph was constructed using data from food databases and recipe co-occurrence information. The authors used a graph embedding method called metapath2vec to learn food representations that capture both chemical similarity and recipe co-occurrence information. These representations were then used to recommend food pairings.

By combining the chemical data from Schreurs et al. (2024) with the FlavorGraph representations from Park et al. (2021), this project aims to create a model that can suggest beer-food pairings that are both chemically compatible and likely to be enjoyed by consumers.

**Repository Contents**

**Data:** Contains the datasets used in the project, including the beer chemical data from Schreurs et al. (2024) and the FlavorGraph data from Park et al. (2021).

**Notebooks:** Jupyter notebooks detailing the data processing, exploratory data analysis (EDA), vectorization, dimensionality reduction, and model development steps.

**Slides:** A presentation summarizing the project's background, methodology, results, and potential applications.

I hope this README is helpful. Please let me know if you have any questions.



