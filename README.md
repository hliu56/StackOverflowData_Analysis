# StackOverflowData_Analysis
## Table of Contents
1. Installation
2. Project Motivation
3. File Descriptions
4. Results
5. Licensing, Authors, and Acknowledgements

## Installation
This repository is just show the analysis for StackOverflow data for 2017. Users can just run the jupyter notebooks After intall anaconda3 and jupyter extension.

## Project Motivation
In this project, we tried to focus on the factors that can affect or decide the salary, which people care more about. Thus we ask these 3 questions after observing the data.
- 1. What's the relationship between EmploymentStatus and Salary
- 2. What's the relationship between Country and Salary
- 3. What's the factor is the most important features that decide salary

## Gather Data and Asses Data
- The data is from Stack Overflow, it can be download form [here](https://www.kaggle.com/stackoverflow/so-survey-2017/data)
- Then we use pandas to read the csv file, we see there are 12891 samples, and 21107 features. And in this dataset, it has nan values and catergorical and numeric values.
- There is only one notbooks in the repository. It show all the results and analysis process. Feel free to run and repeat the analysis!

## Prepare Data
- we basically clean the data by remove nan values in the Salary column, since it's the property that we are interested.
- Secondly, we change catergorical features to numeric by using 'get_dummies' function in pandas

## Modeling
- We firstly split data to training set and testing set, and then use training set to train the linear model by using scikit learn library.
- Once we trained the model, we can use the model to predict values in testing set, and evaluate model by showing R2

## Results
The main results are summarized in the post of medium, please find it [here](https://medium.com/@hliu56buffalo/analysis-for-stack-overflow-salary-2017-data-dcf6b46707e9).

## Licensing, Authors, and Acknowledgements
This repository is on MIT license. We thank StackOverflow providing this data set. You can find the data in [here](https://www.kaggle.com/stackoverflow/so-survey-2017/data).
