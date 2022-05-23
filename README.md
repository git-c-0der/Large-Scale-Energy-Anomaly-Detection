# Large-Scale-Energy-Anomaly-Detection
Competitions motive was to build a model which can predict based on certain indicators whether a building is showing some anomalous behavior or not so, that the reasons for the same can be identified and then required rectifications can be made so, that the energy wastage can be reduced significantly.


<p align="center">
  <img src="https://user-images.githubusercontent.com/77848178/169818904-fa9211b1-b59a-4c63-9186-f8ba3eb5fcde.png" />
</p>

Although the data which was provided to us was already been cleaned but still there was very **high correlation between features** which can significantly effect the learning process of a model and would have become one of the reason's for the unstability of the model.

During the **exploratory data analysis** it has been observed that based on the purpose for which the buildings are getting used have different mean usage of the power. Also, like during weekend's mean power usage is more than that is being used during the week day's.

As this was a **anomaly detection** competition **data imbalance** was prevelant and only **2%** of the training data was for the positive examples feeding this data as it is will result into having hard time for the moel to generalize on the postive examples which is the main motive. So, by suitable **preprocessing methods** data has been balanced and normalized for stable and fast learning of the model.

**Different Models Performance:**
|                     | Validation Accuracy | Test Accuracy |
|---------------------|:-------------------:|:-------------:|
| Logistic Regression | 64%                 | 65%           |
| XGBClassifier       | 99%                 | 88%           |
| Neural Network      | 99%                 | 81%           |
| Auto ML             | 99%                 | 83%           |
         
In this project I learned different methods how can we should approach an imbalanced data set and brushed up my **Data Analysis** and **model development** skills.

<a href='https://www.kaggle.com/code/abhishek123maurya/2-anomaly-detection-features-csv', target='_blank'>Notebook</a> on Kaggle.

Thank You for Reading This.
