---
layout: page
title: Project 3
description: 
img: assets/img/Projects.png
#redirect: https://unsplash.com
importance: 3
category: Research Assistant
---

# Development of a quantitative tool for the assessment of motor competence using wearable technology in schoolchildren in the province of Arequipa.

Determining the classification of motor competence is an essential aspect of physical activity that must be carried out during school years. The objective is to evaluate motor competence in schoolchildren using smart bands, generate percentiles of the evaluation metrics, and classify motor performance through machine learning with hyperparameter optimization. A cross-sectional descriptive study was carried out on 764 schoolchildren (451 males and 313 females) aged 6 to 17 years. Five state schools in the city of Arequipa, Peru were evaluated. Weight, height, and waist circumference were assessed, and body mass index (BMI) was calculated. The tests evaluated in the schoolchildren measured walking and running for 6 minutes. These tests were carried out using smart bands, capturing cadence, number of steps, calories consumed, speed, stride, and heart rate. As a result, the percentiles were created through the LMS method [L (asymmetry: lambda), M (median: mu), and S (coefficient of variation: sigma)]. The cut-off points considered were <P25 (below average), p25 to p75 (average), and >p75 (above average). For classification, the machine-learning algorithms random forest, decision tree, support vector machine, naive Bayes, logistic regression, k-nearest neighbor, neural network, gradient boosting, XGBboost, LightGBM, and CatBoost were used, and the hyperparameters of the models were optimized using the RandomizedSearchCV technique. In conclusion, it was possible to classify motor competence with the tests carried out on schoolchildren, significantly improving the accuracy of the machine-learning algorithms through the selected hyperparameters, with the gradient boosting classifier being the best result at 0.95 accuracy and in the ROC-AUC curves with a 0.98. The reference values proposed in this study can be used to classify the walking motor competence of schoolchildren. Finally, the mobile software product built based on the proposed model was validated using the prototype of the Software Quality Systemic Model (SQSM) based on three specific categories: functionality, reliability, and usability, obtaining 77.09%. The results obtained can be used in educational centers to achieve the suggested recommendations for physical activity in schoolchildren.

> PI: Prof. Jose Sulla Torres.
[Reference](https://www.mdpi.com/2076-3417/14/2/707)