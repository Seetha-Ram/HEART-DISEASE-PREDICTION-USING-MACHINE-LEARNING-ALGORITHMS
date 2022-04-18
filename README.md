                                                        # HEART-DISEASE-PREDICTION-USING-MACHINE-LEARNING-ALGORITHMS
                                                        
                                                        
                                                        
                                                        
                                                        
                                                        
                                                        
Introduction:

Heart disease is the most common disease in India. Earlier people were not aware of the food  they are eating which is supposed to be oily, sweet, salty, sour which in future may lead to  affecting our body system by consumption of more. Earlier if people are eating so much oily  food then too they were working hard so the chances of getting digest the food is more were  as now more people are just sitting in one place or one chair whole with eating the same food  which may lead to the disease. Earlier people were not aware of this but now as they are  educated and the health system is also improvised so they are getting to know about this in  earlier phases. Then too some people are ignoring this and eating a lot of unhealthy and junk  food which is causing the disease. 


In some cases, before the person gets to know about this  the people lose their lives.  Heart disease refers to any condition affecting the heart. There are many types, some of  which are preventable while in some cases the exact cause of CVD isn't clear, but there are  lots of things that can increase your risk of getting it. The main risk factors for CVD are High  Blood Pressure, High Cholesterol, Diabetes, Inactivity, and Obesity.0 Murray CJ and Lopez  AD in their study ‘Alternative projections of mortality and disability by cause 1990-2020:  Global Burden of Disease Study, Lancet. 24 May 1997, projected that the annual number of  deaths due to cardiovascular diseases would rise from 2.26 million (1990) to 4.77 million  (2020)


OBJECTIVE/SCOPE:
                                                                                             The dataset currently has 14 anatomical factors that are going to be used to create a machine learning model. However, when undergoing assessment for heart disease, there are multiple factors that need to be reviewed. Like high cholesterol levels, stress levels play a significant role in heart disease detection. Food habits constitute the risk of heart diseases. This study would generate an equation that individuals can use to assess themselves and understand where they stand in terms of heart disease. The 14 factors from the dataset are not empirical and therefore the solution provided by the study would be one of the solutions for detecting 
heart disease and not the only solution.


RESEARCH METHODOLOGY:
![image](https://user-images.githubusercontent.com/103196322/163829626-f4bc622c-5d41-468e-9eed-194b41483153.png)




Data Pre-processing:
In this step, Researchers will transform the dataset suitably and make it appropriate for model development. They need to implement this step prior to model creation or even the univariate or bivariate analysis. The dataset processing includes the following steps:


Null value treatment – In this step, they check through the dataset if they are able to find any null values. When found, they deal with each variable individually and treat them by imputing Mean or Median in the case of numerical variables and Mode or category creation for Categorical variables.


Outlier treatment – There are two steps to conduct this step. In the first approach, Researchers check the statistics for the numerical variables. If the difference between the maximum value and 75% quartile value is extremely high, then they say that outliers exist. In the second approach, they plot a box plot for the variable. If there exist any points beyond the whiskers, it's evident that outliers exist.


Data type formatting – If variables in the dataset are incorrect or are in a different format, Researchers need to convert them to an appropriate format. Say, the sex variable was written as F and M for female and Male respectively, then they have to transform the variable by imputing 0 for female and 1 for male or vice versa.


Dataset Splitting - In this step, the dataset is split into 70%-30% split, where 70% is for training and the rest 30% is for validating the results. If Researchers were to train the model on the entire data, it will learn all the values and thus lead to overfitting.Model creation and Evaluation:Now that data is transformed and ready for analysis, they go ahead with model creation. Multiple models will be created and one of the efficient ones will be finalized. Recursive feature elimination or RFE will also be used to understand the variables suitable for analysis.


Evaluation metrics:F1 score is the harmonic mean of precision and recall. Researchers have used the F1 score as an evaluation metric. More focus is given to precision and recall as the study is based on predicting heart disease. Even the tiniest possibility of heart vulnerability shouldn’t be missed and therefore F1 score will provide the best analysis of the model.


CONCLUSION :


Based on the anatomical factors, researchers were able to predict the target variable, i.e. whether an individual is vulnerable to a heart-related disease with an outstanding F1 score of 83%. Healthcare is one of the largest domains and therefore for someone with a chronic disease condition, medical treatment and assessments would cost a fortune. The study, therefore, comes in as a savior by giving the individual an equation that he can use to self-assess and avoid undergoing any further expensive assessments. Since there exists no cure for chronic disease, anyone with even the slightest vulnerability should be treated and given utmost attention. This is the reason the study has emphasized the F1 score metric and not the Accuracy. Analysis and prediction of heart disease through logistic regression was successful 
and could be refined further by adding multiple variables and improving dataset size.


REFERENCES :


1.Murray CJ, Lopez AD. Alternative projections of mortality and disability by cause 1990-2020: Global Burden of Disease Study. Lancet. 1997 May 24;349(9064):1498-504. DOI: 10.1016/S0140-6736(96)07492-2. PMID: 9167458. 


2.Gupta R, Joshi P, Mohan V, Reddy KS, Yusuf S. Epidemiology and causation of coronary heart disease and stroke in India. Heart. 2008 Jan;94(1):16-26. 
DOI: 10.1136/hrt.2007.132951. PMID: 18083949.


3.Gupta, R., Misra, A., Vikram, N. K., Kondal, D., Gupta, S. S., Agrawal, A., & Pandey, R. M. (2009). Younger age of escalation of cardiovascular risk factors in Asian Indian subjects. BMC cardiovascular disorders, 9, 28. https://doi.org/10.1186/1471-2261-9-28



                                                        

