# Churn Detection: A Classification Competition

***
This DS project is a result of the 8th [FLAI](https://www.flai.com.br/) Machine Learning Competition. 
The aim of the contest was to build a model that detects employee churn with the highest f1 score.

This model got 3rd place 🥉 in the Competition.

For a better understanding, this was divided in 4 parts: 3 notebooks containing the Data Analysis(EDA) and one showing the Machine Learning Algorithm. At the first stage (EDA), the goal was to understand the datasets.

---

1.	Exploratory Data Analysis: [EDA - Part 1](https://github.com/camilamaestrelli/Employee-Churn-Classification-Competition/blob/main/EDA1_8th_FLAI_ML_Competition.ipynb)
2.	Exploratory Data Analysis: [EDA - Part 2](https://github.com/camilamaestrelli/Employee-Churn-Classification-Competition/blob/main/EDA2_8th_FLAI_ML_Competition.ipynb)
3.	Exploratory Data Analysis: [EDA - Part 3](https://github.com/camilamaestrelli/Employee-Churn-Classification-Competition/blob/main/EDA3_8th_FLAI_ML_Competition.ipynb)
4.	ML: [Algorithm](https://github.com/camilamaestrelli/Employee-Churn-Classification-Competition/blob/main/ALGORITHM_8FLAI_GIT.ipynb)

Following the EDA, a pre-processing was carried out. Thereafter, randomized searches using OPTUNA were carried out for a hyperparametrization.
Finally, a voting classifier using the best models was the one employed to predict the churn. After that, the best threshold was found to reach a higher f1.



Things I learned in this competition:
-	OPTUNA for hyperparameter optimization
-	Clustering using K-means (I used k-means on my 9th submission but didn't get the expected result)


