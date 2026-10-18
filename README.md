# Corel Image Feature Analysis: MiniBatch K-Means

Group project for IT2011 (Artificial Intelligence and Machine Learning), SLIIT.
This repository contains my individual MiniBatch K-Means notebook.

## Problem
Group similar images using unsupervised learning on the Corel image feature
dataset (66,615 images, 89 colour, texture and layout features). No class
labels are provided, so clustering is used.

## What I did
- Loaded, cleaned and merged four feature files
- Explored the data (EDA) and standardised features
- Compared three preprocessing approaches
- Trained a baseline MiniBatch K-Means model, then tuned the number of
  clusters, batch size and reassignment ratio
- Checked stability (ARI), cluster balance and a null test
- Evaluated with Silhouette, Davies-Bouldin and Calinski-Harabasz scores

## Result
Tuning improved the Silhouette score from 0.118 to 0.145 on my modelling
sample, but the model did not meet all of my quality criteria. In the group
comparison of six clustering methods, BIRCH was selected as the final model.

## Tools
Python, scikit-learn, pandas, NumPy, Jupyter Notebook

## Data
The dataset is supplied by the university and is not included here.
