# IT-Purple-Hack

*MISIS and Mr. Smith team*

Team Members:
1) **Артем Плужников** @TheTom205
2) **Глеб Трушков** @aegon7n
3) **Егор Гречин** @who_is_sleep
4) **Кирилл Рыжичкин** @polnostju
5) **Александр Груздев** @TheStrangerOne

Project Presentation: [Link](https://drive.google.com/file/d/1ucRX8dw9aV_eVGB8hxRUbAOmlbirIGks/view?usp=sharing)


This repository contains Jupiter notebooks for training machine learning models created to solve the Sberbank case problem “Predicting the outflow of a salary client of a private individual” as part of the hackathon “IT Purple Hack”

To install all the necessary libraries you need to run

```sh
pip install -r requirements.txt
```

Max metrics obtained (with use different models):
* ROC_AUC = 0.77268
* F1 (for churn class) = 0.2

## Content

1) [Main_Workflow_and_submissions.ipynb](https://github.com/gruzdev-as/IT-Purple-Hack/blob/main/Main_Workflow_and_submissions.ipynb)

Contains the main pipeline for creating and training a model (data analysis, feature selection, building and optimizing models, etc.) as well as theories and hypotheses that were tested and formed the basis for constructing the final solution

Models can be obtained by executing the code in these files. In the future, it is planned to upload the trained models to the repository. You can create a submission file there. The laptop contains the necessary comments and is designed in accordance with best practices in the field

2) [ideas_testing.ipynb](https://github.com/gruzdev-as/IT-Purple-Hack/blob/main/ideas_testing.ipynb)

Contains hypotheses, methods (VIF, PCA etc) and models that did not form part of the final solution, but may be interesting from the point of view of finding a solution and for further work.

## Business Application 

Business ideas for using the models will be proposed in the final presentation and will not be disclosed until the public presentation. This fragment will be added later.


