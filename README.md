# P3 milestone

## Predicting Civil War Onset : What about other predicting methods ?

## Abstract

At the end of their paper, the authors state that "the analyses [...] show that Random Forests offers superior predictve power compared to several forms of logistic regression". Then, when we read the paper, we asked ourselves : why the authors only used Logistic Regression and Random Forest methods ?   

In this extension we will therefore try to compare Random Forest and Logistic Regression to some other methods as Support Vector Machine (SVM), Least Square, Neural Networks or Bayes classifer.   
In our analysis, we will try to compare the accuracy of our models with the models of the paper by comparing the AUCs, we will also try to compare the robustness and the complexity of all the methods to highlight the more efficient one.   

Finally, we will try to pinpoint the more important features when using our models. As a result, we will try to compare these features with the ones from Random Forests and then identify the most important ones in average.

## Research Questions

1. Do **Support Vector Machine** (SVM) and **least square** methods are more accurate and/or more robust than the three Logistic Regression models used by the authors ?

2. Is the **Random Forest** method still the best way to predict relevant data when it comes to civil war onsets ?

3. Using **SVM** and **Least Square**, what are the most important features when predicting civil war onset ?

## Proposed dataset

Knowing that our study will compare our results to the ones of the paper, we will use the exact same dataset than the authors of the paper.   
As a result, the main dataset that we will use is the one provided by the TAs, the Sambanis Civil War dataset (https://drive.google.com/file/d/173N_XoRXsJBSHcL21xl5rDpdQ9LVAmhk/view?usp=sharing).   
A PDF document, provided with the dataset, details the meaning and few characteristics of all variables.

## Methods
We are going to employ the least square regression and Support Vector Machine on the dataset with the same features as used by various authors to compare their accuracy.   
The implementations from scikit libraries are going to be used to construct the models and their regularised versions.   

## Proposed timeline
In order to carry out this project, we have chosen to develop the project with the Agile methodology (SCRUM).
So we have three weeks to complete this project, we will have 3 sprints, with Scrum Meeting between each sprint.


| Date                | 26/11                     | 27/11 - 04/12                                         | 04/12              | 04/12 - 11/12                           | 11/12              | 11/12 - 16/12                                  | 16/12                            |
| ------------------- | ------------------------- | ----------------------------------------------------- | ------------------ | --------------------------------------- | ------------------ | ---------------------------------------------- | -------------------------------- |
| Sprint / Meeting    | Scrum meeting 1           | Sprint 1                                              | Scrum meeting 2    | Sprint 2                                | Scrum meeting 3    | Sprint 3                                       | Final Scrum meeting              |
| Objectives          | Task distribution         | Understanding of the subject, start of implementation | Check all the code | Implementation and analysis of results  | Check all the code | Finish the report and analysis of the results  | Provide an update on the project |
|                     | Formulation of objectives | Data wrangling                                        | New objectives     | Data visualisation                      | New objectives     | Code cleaning                                  | Check the quality of the code    |
|                     | -                         | Data visulization                                     | -                  | Start of report writing                 | -                  | -                                              | Check the report                 |


- The objective of our **scrum meetings** will be to review the progress of the project, to be able to bring solutions to a member who would have difficulties.

- **Sprints** are periods during which each member advances on his objectives determined at the scrum meeting.

- Our objective is to complete the project by **16/12**, two days in advance.
In case of problem, delay, these two days will allow us to finalize the project correctly.

## Organization within the team

| Names         | Sprint 1                              | Sprint 2              | Sprint 3                       |
| ------------- | ------------------------------------- | --------------------- | ------------------------------ |
| Anshul        | Data wrangling                        | Analyze results       | Write report and code cleaning |
| Hugo          | Support Vector Machine                | Analyze results       | Write report and code cleaning |
| Reda          | AUC functions and least square method | Start to write report | Write report and code cleaning |


## Questions for TAs

Is it appropriate to apply the least square regression for a binary classification where there is a possibility of outliers?
