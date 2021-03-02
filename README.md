![GitHub forks](https://img.shields.io/github/forks/ifyoungnet/ChemSweet.svg?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/ifyoungnet/ChemSweet.svg?style=social)
![GitHub repo size](https://img.shields.io/github/repo-size/ifyoungnet/ChemSweet.svg)

# ChemSweet
## How to form your own prediction pipeline:
The details of constructing your own workflow are shown in Figure 1 and Figure2. 
Explanation of workflow: 
### 1) The local model file is read by the Model Reader node above, while the below reads the model-Normalizer.zip file for normalizer; 
### 2) The node of File Reader is used to read the data that needs to be predicted; 
### 3) Convert numbers of label to strings using Number to String node is required in classification models; 
### 4) Select the corresponding prediction node according to the model read by the model reader;
### 5) Output for the prediction result. In addition, evaluation nodes can be chosen according to your task.
