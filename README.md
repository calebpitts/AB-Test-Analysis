# AB-Test-Analysis

## Introduction
I am assuming the fictitious role of Principle Data Scientist at X Corporation. I collected a dataset of nearly 300,000 users who either visited X Corporation's main website or new test website. The dataset also shows whether a user "converted," which means they bought something off the website.

Given this dataset, I've outlined a statistical representation showing whether the new test website has a higher conversion rate than the old main website. 

Before I spoil the mystery however, I want to show how I arrived at my conclusion. First, I will examine the conversion rates in the expiremental and control groups. I will also add conditional probalities of conversion under certain conditions. Then, I will simulate many random samplings with replacement (bootstrapping) to calculate a p-value that provides insight as to whether the difference in conversion rates is significant. Finally, I will use logistic regression to determine the relationship between variables and whether each explanatory variable is significant enough to predict the response variable (conversion rate). 

Enjoy!
