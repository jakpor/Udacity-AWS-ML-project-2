# Disclaimer
This project was conducted for the AWS Udacity Machine Learning Engineer Nanodegree. If you copy too much from this project you could be chased for plagiarism.

Udacity does not have any public course review, so I would like to express that I do not recommend attending this particular Udacity course. I paid for it so I had to finish it, but both AWS and ML part of the course was bad. The course starter and example files had multiple bugs (typos, outdated API, missing lines of code). The AWS part of the course is already outdated. Course was released 11.2021, now it is 05.2022 and AWS UI already evolved in some parts making course tutorials unusable. The Udacity team is also struggling to provide support for students. I had some AWS access issue which wasn't solved for over a month - I had to complete it using personal account and additional budget. For the ML part, the course provide just bullet points, without any thorough explanation - you should be familiar with ML concepts in order to start this course.

# Udacity-AWS-ML-project-2
This is my submission to the AWS Machine Learning nanodegree  - project 2

## Project structure
Main Python notebook for the project is named [`starter.ipynb`](./starter.ipynb)

AWS lambda functions are in three python files: 
* [`serializeImageData.py`](./serializeImageData.py),
* [`classifyimageData.py`](./classifyimageData.py),
* [`filterLowConfidence.py`](./filterLowConfidence.py)

Step function code file: [`stateMachine.json`](./stateMachine.json). Graph:

![stateMachine](./stepfunctions_graph.png)

