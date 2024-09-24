[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/R1vgPUT1)


**OSE PROJECT**

Name : Sneha Roy 

Matriculation number : 50078578

**OVERVIEW OF THE PROJECT**

Dataset : I have used the nlu_evaluation_dataset from HuggingFace Library which consists of 25 715 non-zero examples belonging to 18 scenarios and 68 intents for the evaluation Natural-Language Understanding systems. The dataset is divided into train, cross validation and test set in the ratio of 18 : 1: 1.

Task at hand : To perform intent classification on the train dataset, cross validating it on the cross validation dataset and evaluating different model's performance on unseen test data and custom text.

The project is structured in 2 parts.

Part 1 : In the first part, I have used my dataset to train different sk-learn models and evaluate it's performance.

Part 2 : In the second part, I have introduced the different transformers model for my task at hand and to see how much improvement the transformer models are able to give me over the traditional sk-learn models.

**STRUCTURE OF THE REPOSITORY** :

1. README.md : It contains a basic overview of what I have tried to done, the structure of the repository and structure of my Project

2. OSE_document.pdf : I have given a detailed explanation of all the models and the workings in the 3 page document, trying to document and highlight my motivations, the resulys , analysis and conclusion.

3. Sneha_Final_Notebook.ipynb : I have created one notebook that contains both the tasks sequentially. But it is impotant to run the notebook sequentially because of many imports that are usually done in the beginning of each model are not done later, if the same imports are required.

I have provided text codes and explanations throughout my notebook for enhanced readibility.

4. OSE_Questions_Answers.pdf : My pdf file where I have written the question and answers of all the questions given.

5. environment.yml : It comprises of the packages that I would be needing to run my project

The pdfs which are uploaded sometimes can show an error when trying to open. However, refreshing the page is solving the problem.

**ENVIRONMENT**

I have run the project with the following versions:

torch==1.9.1

transformers==4.10.2

tokenizers==0.10.3

numpy==1.21.2

pandas==1.3.3

tensorflow==2.6.0

So my results will be best reproduced if the project is ran with these versions, which I have also specified in my code. However, torch and tensorflow of these versions are not supported by jupyter notebook. Hence for torch and tensorflow, the rwecent most versions will be used, which might yeild slightly different results from my documentation( not more than 1 percentage point).