# accuracy_fairness_metric
We propose a selection criterion which allows us to obtain machine learning models with both high fairness and high accuracy.

Given the uncertainty surrounding the subject of algoritmic fairness, we aim to investigate the apparent trade-off between accuracy 
and fairness by comparing the effect of regularisation strength on both. 

We first investigate this in the context of standard machine learning models, before going on to analyse how this model selection strategy might
change with fairness-based algorithms. Finally, we propose a selection criterion which allows us to obtain models with both high fairness and high accuracy.

We use two datasets from the AIF360 library in order to perform our analysis. 

1. The ‘Adult’ dataset (with 48842 data-points), which includes census data from 1994  and the prediction task is to classify whether a person earns over $50k p.a. or not. 

2. The ‘German’ dataset (with 1000 data-points) and the task is to predict whether people have a good or a bad credit score based on a set of attributes. 

These can be retrieved here:
https://archive.ics.uci.edu/ml/datasets/adult
https://archive.ics.uci.edu/ml/datasets/statlog+(german+credit+data)


Both datasets include sensitive attributes: ‘sex’ in the Adult dataset and ‘age’ in the German dataset - both of which fall under the category of
legally protected characteristics in many countries. There is an inherent bias towards the more privileged group in both datasets for male and aged individuals respectively

See ML_project_report.pdf for write up of results.
