# Task 3: Natural Language Processing

```
Prediction of star ratings from E-Commerce customer reviews using Natural Language Processing techniques.

* Started on:   12/12/2022
* Closes on:    16/01/2023
```

## Provided files
List of files provided by the lecturer that are required to define and accomplish the given task.

📄 [ML2022_Milestone_3_Task_Definition.pdf](https://github.com/schmidt-marvin/ESI_2022_TecAA/tree/main/task03/provided_files/ML2022_Milestone_3_Task_Definition.pdf)<br>
🗄️ [products.csv](https://github.com/schmidt-marvin/ESI_2022_TecAA/tree/main/task03/provided_files/products.csv)<br>


## Submitted files
List of files handed in for evaluation as a result of the performed task. 

📄 [TecAA_NLP_Report.pdf](https://github.com/schmidt-marvin/ESI_2022_TecAA/blob/main/task03/submission/TecAA_NLP_Report.pdf)<br>
A detailed report discussing the obtained results and techniques within the NLP exercise. Provides summaries and more detailed explanations about the steps performed within each Colab notebook listed below. <br>

📃 [Task03_NLP_Preprocessing_Barba_Guerrero_Schmidt.ipynb](https://github.com/schmidt-marvin/ESI_2022_TecAA/blob/main/task03/submission/Task03_NLP_Preprocessing_Barba_Guerrero_Schmidt.ipynb)<br>
This document imports the input dataset and performs a data extraction to retrieve their contents. The preprocessing steps as defined within task 1 of the task definition are implemented and the results are exported for use within the upcoming steps. <br>

📃 [Task03_NLP_VectorizationFeatureSelection_Barba_Guerrero_Schmidt.ipynb](https://github.com/schmidt-marvin/ESI_2022_TecAA/blob/main/task03/submission/Task03_NLP_VectorizationFeatureSelection_Barba_Guerrero_Schmidt.ipynb)<br>
With the preprocessed csv, in this colab we fix some errors (Reviews with wrong scores, numbers in reviews) in order to apply a proper vectorization following 4 different configurations (TFIDF, TFIDF + n-grams with n = 2, TFIDF + n-grams + POS tagging to count number of adjectives, TFIDF + n-grams + POS tagging + other features as the number of words or sentences). Finally we apply feature reduction to each configuration to remove 70% of the features. <br>

📃 [Task03_NLP_Algorithms_Barba_Guerrero_Schmidt.ipynb](https://github.com/schmidt-marvin/ESI_2022_TecAA/blob/main/task03/submission/Task03_NLP_Algorithms_Barba_Guerrero_Schmidt.ipynb)<br>
The google colab file applies two different algorithms, SVM and XGBoost, on each of the four configurations created previously. After the execution of the algorithms, we obtained a results table that we used to compare the different algorithms, for the sake of determining the best algorithm and configuration.<br>