## Project Title
Spam-Filters
## Software Used
Data Analysis: Python and Orange

Profit Model: Excel
## Introduction
The purpose of our analysis is to find a model that would allow us to filter out spam text messages. We used the perspective of a phone company that will make profit from filtering out spam messages but will lose money filtering our legitimate messages. We used a dataset of text messages labeled as spam or legitimate to build our models. We tested seven different model types on the data set and evaluated those models on AUC. While all our models had impressive results, Naïve Bayes and Random Forest models stood out as the top two predictive models. We found that the Random Forest model was the best model to predict and filter out spam messages based on our profit and lift curves.
## Dataset Description
This dataset represents 5,572 instances of English text messages collected by the University of California Irvine (UCI) for SMS spam research. Each message is tagged as either ham (legitimate) or spam. According to UCI, these messages were sourced from a variety of areas ranging from the United Kingdom to Singapore. There are only two features for this dataset—the text of the SMS message and its spam (0) or ham (1) tag. 
