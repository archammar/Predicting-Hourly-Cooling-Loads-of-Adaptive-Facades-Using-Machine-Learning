# Predicting-Hourly-Cooling-Loads-of-Adaptive-Facades-Using-Machine-Learning


This repository contains the codes in jupyter-notebooks for the prediction tasks and the deployment within grasshopper interfance for testing the surrogate models.
The machine learning models used are Artificial Neural Network and Random Forest.


## Contents in the folder
1. The data folder contains the synthetic database generaated using simulation which used to develop the machine learning surrogate models.
2. The models folder contain the  codes of the machine learning surrogate models. 
3. The pretrained models folder contain the pretrained ML codes in jupyter-notebooks for testing and validation. 
4. The grasshopper folder contains Rhino file corresponding to the new scenarios and Grasshopper file for making the hourly cooling loads predictions using the developed surrogate model.


## Instructions to predict hourly cooling loaads in Grasshopper using GH_CPython 
1. The Rhino software version used is 5 and has to be "run as administrator" while opening.
2. The data used for machine learning model training can be downloaded from this link:

3. The pretrained neural netwrok model can be run in GH_NN_integration.ipynb for the prediction tasks. 
4. The pretrained Random Fores model can be run in GH_DT_integration.ipynb for the prediction tasks.
5. The inputs in grasshopper file can be given as a list under the variable name '_input'. 
