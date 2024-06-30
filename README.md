# Sentiment Analysis for Amazon Reviews Using Voting Classifier Ensemble Method
## Project Overview
In this project, we'll classify the sentiment of Amazon reviews. We'll use NLP preprocessing and TF-IDF to extract features and then create a VotingClassifier ensemble model to determine review sentiment
Out ensemble mdel will help classify reviews without relying on ratings. Providing insight into whether a customer is happy or not

## Note
- Please review the `'amaRev.ipynb'` first. It has all of the details and reasoning explained thoroughly.
- This `'README'` will just be used to showcase visuals and minimal examples of the project.

## Intro to Dataset
- Prior to balacing the dataset
<img src="images/unbalanced_dataset.png width="600"/>

- After balacing the dataset, keeping the difference of 1 star and 2 star reviews
<img src="images/balanced_datasett.png width="600"/>

## NLP Preprocessing
- These are some of the steps done for the NLP preprocessing, to see all, check `'amaRev.ipynb'`

<img src="images/NLP_basic_visualizer.png width="600"/>

## TF-IDF for Feature Extraction
<img src="images/TF-IDF_explanation.png width="600"/>

### Examples of Feature Frequency
<img src="images/frequency_top_20.png width="600"/>

## Models Results
- Logistic Regression
<img src="images/lr_CM.png width="600"/>

- Ensemble Model
<img src="images/ensemble_CM.png width="600"/>

## Conclusion
The differences in results between the logistic regression model and the ensemble model were minimal. Their metrics, including precision, recall, and F1 score, were very close. Due to the longer runtime required to train the ensemble model, logistic regression is a better choice for a company looking for a cost-efficient model
