# Credit_Risk_Analysis

## Overview

The urpose of the assignment is to learn how to use Supervised Machine Learning. In this scenario we are presented with a lending company that has tasked us to predict risck in lending to the applicant, we  evaluate indivudual applicants and decide if lending to these individuals is advisable based on the results of the evaluation conducted through machine learning. The kernel mlenv was installed in order to complete the assestment we followed the Supervised Mashine Learning Algorithms. 


  ## Results 
  
 ### *Deliverable #1*
The imbalanced-learn and scikit-learn libraries were used to evaluate data and resampling and oversampling and smote algorithms the data set is resampled to vire the count of ta rget classes, train logistic regression classifier and calculate the balanced accuracy score as wel as generate a confusion matrix abd generate a classification report.  Below are the findings: 
  
   *Accuracy Score for the Model* 
   
   
  ![image](https://user-images.githubusercontent.com/104601282/199864542-5e880528-62f8-4632-9059-742ef31cf96f.png)


  *Confusion Matrix*
  
  
 ![image](https://user-images.githubusercontent.com/104601282/199864877-4f4ee645-28ef-486f-95f1-5483946c3310.png)

  
  *Imblanced Classification report*
  
  
  ![image](https://user-images.githubusercontent.com/104601282/199864722-53ac8da0-1092-42cb-9800-22f22325f484.png)


### *Deliverable #2*

Use of Smooten to Predict Credit Risk

*Acuracy Score using SMOTEEN*

![image](https://user-images.githubusercontent.com/104601282/199865262-215f5b91-0f78-497d-b0b0-894e27df1ffe.png)


![image](https://user-images.githubusercontent.com/104601282/199865133-ec41d56b-afaa-41df-b0ab-b8e21d0196d1.png)


*Confussion Matrix*

![image](https://user-images.githubusercontent.com/104601282/199865307-26b61072-80dd-4572-a195-ef9b1b4d44c9.png)

*Imbalanced Classification Report*


![image](https://user-images.githubusercontent.com/104601282/199865376-b20ef068-471b-40c3-b18c-bd4155c4adc7.png)


### *Deliverable #3*

 Train and compare two different ensemble classifiers

**BalancedRandomForestClassifier**
   
   *Accuracy Score for the Model* 

![image](https://user-images.githubusercontent.com/104601282/199919003-2de4f18d-9345-475e-9f12-d7c433b3cf16.png)


   *Confussion Matrix*

 ![image](https://user-images.githubusercontent.com/104601282/199919042-19214bd1-5c32-4796-86b0-1d2a12e0c9d9.png)


  *Imbalanced Classification Report*
  

![image](https://user-images.githubusercontent.com/104601282/199919590-1cdaabed-1ad6-464b-a481-94b036c9a893.png)

  
  **EasyEnsembleClassifier**
    
    
    *Accuracy Score for the Model* 
    
    
    
  ![image](https://user-images.githubusercontent.com/104601282/199920694-1fbc4687-1127-4a66-9b3f-71844eaa5e8e.png)


   *Confussion Matrix*
  
  ![image](https://user-images.githubusercontent.com/104601282/199919235-6ccfb085-c108-434a-8f45-0b3b5d22d2cb.png)


  *Imbalanced Classification Report*

    

![image](https://user-images.githubusercontent.com/104601282/199919906-f168b25b-c67c-4a59-9e3f-878614dc0d84.png)

    Balance Accuracy Scores, Pressicion and Recall 
    
    The Best Accuracy scores is seen with EasyEnsemblerClassifier at 92% in comparison to the lowest held by the logistc regression model at 63% 
    The highest pressicion score is seen in resampling with BalancedRandomForestClassifier at  97% 
    The fastest recall is seen with EasyEnsemblerClassifier at 0.94 the lowest seen in Logistic Regression with a 0.54
    
    
    
    
    
    
    
