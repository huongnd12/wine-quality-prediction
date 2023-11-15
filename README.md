This project aims to predict quality of wine classes using tree-based argorithms which are Random Forest and XGBoost.

The two datasets are related to red and white variants of the Portuguese "Vinho Verde" wine.

- Number of Instances: red wine - 1599; white wine - 4898.
- Input variables (based on physicochemical tests):
   1 - fixed acidity
   2 - volatile acidity
   3 - citric acid
   4 - residual sugar
   5 - chlorides
   6 - free sulfur dioxide
   7 - total sulfur dioxide
   8 - density
   9 - pH
   10 - sulphates
   11 - alcohol
   Output variable (based on sensory data): 
   12 - quality (score between 3 and 9)
The classes are ordered and not balanced (e.g. there are much more normal wines than excellent or poor ones)

In this project, I will divide the dataset into 3 classes:
- Poor: quality 3 to 4
- Average: quality 5 to 6
- Good: quality 7 to 9

Evaluation of models in this project is summarized as below table:
![image](https://github.com/huongnd12/wine-quality-prediction/assets/57044034/08cc0660-7878-463e-83ac-af904a7afd75)
