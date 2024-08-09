# tiktok-ml-video-classification

## Classifying TikTok Videos using Machine Learning

This repository contains a project focused on analyzing fictional TikTok data to determine whether a video contains a _claim_ or whether offers an _opinion_. By building a model that classifies videos accurately and efficienty, TikTok can reduce the backlog of user reports and prioritize them more efficiently. In this project, I constructed both a random forest model and an XGBoost model to solve this problem.

### Business Need and Modeling Objective 

TikTok users can report videos that they believe violate the platform's terms of service. Due to the large volume of videos created and viewed daily, individual human review of reported videos is not feasible. Analysis shows that videos violating the terms of service are more likely to present _claims_ than _opinions_. Therefore, distinguishing between _claims_ and _opinions_ is valuable.

TikTok aims to develop a machine learning model to differentiate between _claims_ and _opinions_. Videos labeled as _opinions_ will undergo less human review, while those labeled as _claims_ will be prioritized for further assessment, potentially based on the number of reports received. Implementing a machine learning model would significantly aid in presenting human moderators with videos most likely to breach TikTok's terms of service.


### Project Goal
Develop a machine learning model to classify TikTok videos as claims or opinions, aiming to automate the identification of potential violations of the platform's terms of service and prioritize videos for human review.


## Instructions
Open the .ipynb file to view the Jupyter Notebook detailing the analytical process, python code as well as the interpretation and evaluation of the predictive models, relevant data visualizations, ethical considerations related to the analysis and its implications.

Open the .csv file to view the dataset. 

## Find a bug?

If you found an issue or would like to submit an improvement to this project, please submit an issue using the issues tab above. If you would like to submit a PR with a fix, reference the issue you created!
