# Coursera_PracticalMachineLearningProject
## This repository contains the .rmd file and compiled HTML file for the project assignment of Practical Machine Learning course offered by Coursera in association with John Hopkins University.

## Below is the summary report of the model I developed. All the code and solution can be seen in the HTML file.

#### We were provided with the two files namely pml-training and pml-testing. We are supposed to train a model on pml-training dataset
#### and then make prediction on testing set.  However it can be easily seen that a lot of variables have very less data. Also many of
#### the variables are non numeric. 
#### I did some preprocessing of the data as follows,
#### 1- I removed variables having data less than in 60% rows,
#### 2- I removed all the non-numeric variables, except the variable "classe" which is to be predicted.
#### Then I splitted the training file in two files , as we have to test our model before doing final testing on testing dataset.
#### So I made two files Train and Test out of training dataset with 60% data in Train and rest in Test.
#### I then tested various models like glm, trees and random forest but I got maximum accuracy with random forest model, an accuracy of
#### approximately 99% on Test dataset.
#### Then finally I ran the model on testing dataset and printed the output vector also.

