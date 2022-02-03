# The Raven Test - In Search for Group Differences

![](https://img.shields.io/badge/Academical%20Project-Yes-success)
![](https://img.shields.io/badge/Made%20With-Python-blue)
![](https://img.shields.io/badge/License-Free%20To%20Use-green)
![](https://img.shields.io/badge/Maintained-No-red)

## Description 

The search for trustworthy methodologies of determining a measurable intelligence index has been a quest of our brightest minds for decades.
Raven matrices tests have proved to have widespread practical use as a measure of intelligence.
They are a source of data for many studies on the general population as they seem promising tools for contexts such as psychometric tests or clinical assessment.

In one study on the application of these matrices to groups of students from different backgrounds, questions emerged regarding the possibility of clear differences between Multimedia and Informatics students. 
This repository contains the source code that supports our paper on the statistical analysis applied to the test results with the help of Machine Learning (ML) classification techniques in search for determining whether any of the two groups showed significant advantages over the other.

The dataset used suffered a preprocessing stage for normalization and removal of outliers. 
2D projections were generated to search for clear group differences.
Five different ML models were used and compared in terms of performance.

## Repository Structure

/RAVEN - contains the dataset used for training and testing the models

/report - contains the paper written on the statistical analysis to the Raven test results

/src - contains the Jupyter Notebooks developed by us and the requirements for their execution

/workPlan - contains the formal definition of the work plan made before developing our solutions

 ## Instructions on how to run our code

1. Install necessary requirements:
```
$ pip3 install -r requirements
```

2. Launch the Jupyter server:
```
$ cd src
$ jupyter-notebook .
```

## Authors

The authors of this repository are Filipe Pires and João Alegria, and the project was developed for the Data Mining Course of the Master's degree in Informatics Engineering of the University of Aveiro.

For further information, please read our [report](https://github.com/FilipePires98/RavenTests-DataMining/blob/master/report/recpad_review.pdf) or contact us at filipesnetopires@ua.pt or joao.p@ua.pt.
