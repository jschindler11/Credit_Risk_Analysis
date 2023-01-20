# Credit_Risk_Analysis

## Overview of the analysis
The purpose of this analysis is to apply machine learning to predict the risk of approving credit. Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, we will employ different techniques to train and evaluate models with unbalanced classes. 


## Results

### Naive Random Oversampling
<img width="714" alt="Screen Shot 2023-01-20 at 11 27 21 AM" src="https://user-images.githubusercontent.com/111151454/213788507-2e76fd98-508a-49ca-93fe-48e3b4ce8f15.png">


* Balanced Accuracy Score: 0.6742571941946299
* Precision Scores: The precision score is low (0.01) for high-risk loans and is high (1.00) for low-risk loans 
* Recall Score: The recall score is 0.74 for high-risk loans and 0.61 for low-risk loans

### SMOTE Oversampling
<img width="714" alt="Screen Shot 2023-01-20 at 11 27 51 AM" src="https://user-images.githubusercontent.com/111151454/213788527-957f47e9-ece9-42e1-856d-99d552beaf98.png">


* Balanced Accuracy Score: 0.6623356588465208
* Precision Score: The precision score is low (0.01) for high-risk loans and is high (1.00) for low-risk loans 
* Recall Score: The recall score is 0.63 for high-risk loans and 0.69 for low-risk loans

### Undersampling
<img width="714" alt="Screen Shot 2023-01-20 at 11 28 02 AM" src="https://user-images.githubusercontent.com/111151454/213788555-67a5072d-5be5-4c3d-99d6-284d2bacee39.png">


* Balanced Accuracy Score: 0.5442661782548694
* Precision Scores: The precision score is low (0.01) for high-risk loans and is high (1.00) for low-risk loans 
* Recall Score: The recall score is 0.69 for high-risk loans and 0.40 for low-risk loans

### Combination (Over and Under) Sampling
<img width="714" alt="Screen Shot 2023-01-20 at 11 28 13 AM" src="https://user-images.githubusercontent.com/111151454/213788587-9a983f13-7eeb-451d-86eb-77d8d3394f64.png">


* Balanced Accuracy Score: 0.6433860645185192
* Precision Score: The precision score is low (0.01) for high-risk loans and is high (1.00) for low-risk loans 
* Recall Score: The recall score is 0.71 for high-risk loans and 0.57 for low-risk loans

### Balanced Random Forest Classifier
<img width="713" alt="Balanced Random Forest Classifier" src="https://user-images.githubusercontent.com/111151454/212764428-c55134e4-6276-44d9-9b69-504a5e873d65.png">

* Balanced Accuracy Score: 0.7877672625306695
* Precision Score: The precision score is low (0.04) for high-risk loans and is high (1.00) for low-risk loans
* Recall Score: The recall score is 0.67 for high-risk loans and 0.91 for low-risk loans

### Easy Ensemble AdaBoost Classifier
<img width="715" alt="Easy Ensemble AdaBoost Classifier" src="https://user-images.githubusercontent.com/111151454/212764406-6320fe8f-5cb1-4a5d-bd44-fb2020c8185f.png">

* Balanced Accuracy Score: 0.925427358175101
* Precision Score: The precision score is low (0.07) for high-risk loans and is high (1.00) for low-risk loans
* Recall Score: The recall score is 0.91 for high-risk loans and 0.94 for low-risk loans


Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

## Summary
Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
