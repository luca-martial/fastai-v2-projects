# Tabular Playground Series - Mar 2021 (Kaggle)

## Predicting A Binary Target

The goal of this project was to build machine learning models to predict a binary target in a tabular dataset, as part of the March 2021 version of the monthly [Tabular Playground Series Kaggle competition](https://www.kaggle.com/c/tabular-playground-series-mar-2021/overview). I experimented with decision trees, random forests, neural networks and ensembling. 

The dataset used for this competition is synthetic but based on a real dataset and generated using a CTGAN. The original dataset deals with predicting the amount of an insurance claim. Although the features are anonymized, they have properties relating to real-world features. My best submission scored a AUC-ROC of 0.88675 on the private leaderboard, placing me in the top 700.

Notebooks contained in this repo:

| Notebook                                                                                                                                                          | ML Model         | Details                                                          | Public Leaderboard Score (25% data) | Private Leaderboard Score (75% data) |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------|-------------------------------------------------------------------|--------------------------|---------------------------|
| [tabular_playground_DT001_83506.ipynb](https://github.com/luca-martial/fastai-v2-projects/blob/main/march-tabular-challenge/tabular_playground_DT001_83506.ipynb) | Decision Tree  | Validation set not used in final model training.  | 0.83506                  | 0.83892               |
| [tabular_playground_DT002_83476.ipynb](https://github.com/luca-martial/fastai-v2-projects/blob/main/march-tabular-challenge/tabular_playground_DT002_83476.ipynb) | Decision Tree  | Validation set     used in final model training.  | 0.83476                  | 0.83978               |
| [tabular_playground_DT003_83384.ipynb](https://github.com/luca-martial/fastai-v2-projects/blob/main/march-tabular-challenge/tabular_playground_DT003_83384.ipynb) | Decision Tree  | Validation set used in final model training, added smoothing of final predictions.  | 0.83384                  | 0.83871               |
| [tabular_playground_RF001_87874.ipynb](https://github.com/luca-martial/fastai-v2-projects/blob/main/march-tabular-challenge/tabular_playground_RF001_87874.ipynb) | Random Forest  | Validation set not used in final model training.  | 0.87874                  | 0.88396               |
| [tabular_playground_RF002_ 87943.ipynb](https://github.com/luca-martial/fastai-v2-projects/blob/main/march-tabular-challenge/tabular_playground_RF002_87943.ipynb) | Random Forest  | Validation set used in final model training.  | 0.87943                  | 0.88443               |
| [tabular_playground_NN001_88487.ipynb](https://github.com/luca-martial/fastai-v2-projects/blob/main/march-tabular-challenge/tabular_playground_NN001_88487.ipynb) | Neural Network  | Validation set not used in final model training. Layers 500, 250.  | 0.88487                  | 0.89040               |
| [tabular_playground_NN002_88446.ipynb](https://github.com/luca-martial/fastai-v2-projects/blob/main/march-tabular-challenge/tabular_playground_NN002_88446.ipynb) | Neural Network  | Validation set used in final model training. Layers 500, 250.  | 0.88446                  | 0.89065               |
| [tabular_playground_NN003_88449.ipynb](https://github.com/luca-martial/fastai-v2-projects/blob/main/march-tabular-challenge/tabular_playground_NN003_88449.ipynb) | Neural Network  | Validation set not used in final model training. Layers 200, 100.  | 0.88449                  | 0.89019               |
| [tabular_playground_NN004_88600.ipynb](https://github.com/luca-martial/fastai-v2-projects/blob/main/march-tabular-challenge/tabular_playground_NN004_88600.ipynb) | Neural Network  | Validation set used in final model training. Layers 200, 100.  | 0.88600                  | 0.89128               |
| [tabular_playground_NN005_88557.ipynb](https://github.com/luca-martial/fastai-v2-projects/blob/main/march-tabular-challenge/tabular_playground_NN005_88557.ipynb) | Neural Network  | Validation set used in final model training. Layers 200, 100. Feature engineering added.  | 0.88557                  | 0.89158               |
| [tabular_playground_ENS001_RF002_NN005.ipynb](https://github.com/luca-martial/fastai-v2-projects/blob/main/march-tabular-challenge/tabular_playground_ENS001_RF002_NN005.ipynb) | Ensemble  | Random Forest & Neural Network  | 0.88675                  | 0.89229               |


