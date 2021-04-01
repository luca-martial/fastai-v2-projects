# Tabular Playground Series - Mar 2021 (Kaggle)

## Predicting A Binary Target

The goal of this project was to build machine learning models to predict a binary target in a tabular dataset, as part of the March 2021 version of the monthly [Tabular Playground Series Kaggle competition](https://www.kaggle.com/c/tabular-playground-series-mar-2021/overview). I experimented with decision trees, random forests, neural networks and ensembling. 

The dataset used for this competition is synthetic but based on a real dataset and generated using a CTGAN. The original dataset deals with predicting the amount of an insurance claim. Although the features are anonymized, they have properties relating to real-world features. My best submission scored a AUC-ROC of 0.88675 on the private leaderboard, placing me in the top 700.

Notebooks contained in this repo:

| Notebook                                                                                                                                                          | ML Model         | Details                                                           | Public Leaderboard Score | Private Leaderboard Score |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------|-------------------------------------------------------------------|--------------------------|---------------------------|
| [tabular_playground_DT001_83506.ipynb](https://github.com/luca-martial/fastai-v2-projects/blob/main/march-tabular-challenge/tabular_playground_DT001_83506.ipynb) | Decision Tree  | Validation set not used in final model training.  | 0.83506                  | 0.83892               |
| [tabular_playground_DT002_83476.ipynb](https://github.com/luca-martial/fastai-v2-projects/blob/main/march-tabular-challenge/tabular_playground_DT002_83476.ipynb) | Decision Tree  | Validation set     used in final model training.  | 0.83506                  | 0.83892               |
